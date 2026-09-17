# Robotics AI Journey

Percorso pubblico di apprendimento verso una carriera come Robotics + AI Technical Specialist, con focus su hardware, automazione, AI applicata e sistemi autonomi.

## Contenuti

### 01 — Python Fundamentals
- Variabili, tipi di dato (`int`, `float`, `str`, `bool`)
- Conversioni esplicite di tipo e gestione dei `TypeError`
- Valori truthy/falsy e comportamento booleano

### 02 — Decision Engine (if/elif/else)
Motore decisionale per un robot simulato che valuta più letture di sensori insieme (distanza, temperatura, batteria) e determina uno stato operativo con livelli di gravità crescenti: `OK`, `ATTENZIONE`, `CRITICO`, `DOPPIO ALLARME`.

Durante lo sviluppo sono stati identificati e risolti due bug di logica:
- **Overwrite silenzioso dello stato**: due blocchi `if` indipendenti sovrascrivevano una decisione già presa
- **Branch irraggiungibile**: una condizione troppo generica, controllata per prima in una catena `elif`, impediva a un caso più specifico di essere mai raggiunto

## Prossimi passi
Loop, funzioni, liste/dizionari, poi Git/GitHub da riga di comando e primi progetti con dati reali da sensori/API.
