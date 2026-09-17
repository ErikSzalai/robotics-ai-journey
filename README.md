# Robotics AI Journey

Percorso pubblico di apprendimento verso una carriera come Robotics + AI Technical Specialist, con focus su hardware, automazione, AI applicata e sistemi autonomi.

## Contenuti

### 01 — Python Fundamentals
- Variabili, tipi di dato (`int`, `float`, `str`, `bool`)
- Conversioni esplicite di tipo e gestione dei `TypeError`
- Valori truthy/falsy e comportamento booleano

### 02 — Decision Engine (if/elif/else)
Motore decisionale per un robot simulato che valuta più letture di sensori insieme (distanza, temperatura, batteria) e determina uno stato operativo con livelli di gravità crescenti: `OK`, `ATTENZIONE`, `CRITICO`, `DOPPIO ALLARME`.

### 03 — Loops, liste e zip()
Elaborazione di serie temporali di letture sensore (non più un singolo istante). Iterazione su liste con `for`, pattern accumulatore (`+=`), e `zip()` per combinare due sensori diversi nello stesso ciclo temporale, riapplicando il motore decisionale a 4 stati a ogni coppia di letture.

Durante lo sviluppo sono stati identificati e risolti due bug di logica:
- **Overwrite silenzioso dello stato**: due blocchi `if` indipendenti sovrascrivevano una decisione già presa
- **Branch irraggiungibile**: una condizione troppo generica, controllata per prima in una catena `elif`, impediva a un caso più specifico di essere mai raggiunto

## Prossimi passi
Loop, funzioni, liste/dizionari, poi Git/GitHub da riga di comando e primi progetti con dati reali da sensori/API.
