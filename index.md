# BPM Business Process Modeler
- [Introduzione](https://github.com/federicobonazzi-csw/documentation/blob/7dc0a5b5e079bc2f8e4f29d438669755d40c8977/doc/BPM%20Introduzione.md)
  - [Utente](https://github.com/federicobonazzi-csw/documentation/blob/7dc0a5b5e079bc2f8e4f29d438669755d40c8977/doc/Utente.md)
  - [Operazioni](https://github.com/federicobonazzi-csw/documentation/blob/7dc0a5b5e079bc2f8e4f29d438669755d40c8977/doc/Operazioni.md)

# BPM Business Process Modeler
## Introduzione
Il BPM (Business Process Modeler) è un software che permette di mettere nero su bianco i flussi aziendali.
La costruzione dei flussi avviene graficamente attraverso un Designer, che permette di costruire veri e propri diagrammi, con componenti grafiche che sottendono a funzioni specifiche.
### Glossario

•       MODELLO DI PROCESSO insieme delle definizioni di tutte le attività che si devono eseguire e degli utenti coinvolti sia nell’esecuzione, che nella presa conoscenza delle attività e delle relative tempistiche.

•       PROCESSO singola occorrenza di un modello di processo. Contiene i dati del modello (variabili)

•       ALLEGATI insieme dei file nei diversi formati allegati alla singola istanza.

•       FILE SYSTEM: spazio su Server condiviso aziendale
## Utente

### Nuova Log In

Sezione in cui è possibile connettersi con un account diverso rispetto a quello con cui si è effettuato l’accesso, viene aperta la scheda per inserire un diverso User e Password, la funzione può essere utilizzata a patto che non si stia utilizzando altre schermate sul BPM come Home Page (to do list), configurazione etc. …

### Cambio Password

Funzione che consente all’utente di poter modificare la propria password a meno che l’autenticazione a BPM non sia fatta tramite Autenticazione Windows in tal caso la gestione delle credenziali dipendono dalle impostazioni della Active directory
### Preferenze Notifiche

In questa sezione è possibile gestire le notifiche personali che il BPM invia via mail a fronte dei flussi in cui si è coinvolti:

![image-20220323145650797](https://github.com/federicobonazzi-csw/documentation/blob/93ede05f6e38b8861e7c0903a352d517b1c22a7d/bpm3.png)
### Account Mail

 

### Visualizza Log
### Visualizza Log

### Home Page

![image-20220323151400287](https://github.com/federicobonazzi-csw/documentation/blob/e38abcf812e4b6eca4b8a55be10e8b0162de6429/BPM%20img/home%20page.png)

La prima voce del menù Operazioni denominata Home Page consente di visualizzare la To Do List del BPM, dove sono annotate tutte le attività svolte e da svolgere dell’utente e non solo.

La gestione dell’home page viene fatta tramite un menù di filtro che consente di selezionare:

**Utenti** à in base ai permessi dell’utente consente di selezionare se visualizzare solo le azioni assegnate oppure anche quelle assegnate ad altre utenti, ad esempio un utente Amministratore è in grado di vedere tutte le azioni assegnate all’interno del BPM indipendentemente dall’utente

**Responsabile/Esecutore** à in base alla selezione che si esegue su questi check, è possibile filtrare le opzioni in base al ruolo dell’utente (Esecutore, Responsabile), selezionarli entrambi o deselezionarli entrambi rende visibile tutte le azioni indipendentemente dal ruolo

**Filtro attività** à campo senza etichetta che permette di filtrare per attività aperte, attività da svolgere nella giornata corrente, nella settimana, nel mese e attività aperte all’interno di un determinato lasso temporale.

**Ambito** à

**Cerca** à inserendo un testo BPM filtrerà tutte le azioni che contengono tale testo considerando il nome del flusso l’utente esecutore/responsabile dell’azione etc. …

**Priorità** à

**Visualizza** à permette di filtrare le azioni completate / programmate / delegate /ed in cc (Copia Conoscenza)

**Modelli** à è possibile filtrare per i flussi a cui l’utente è abilitato

**Operatività** à sezione in cui è possibile Ricercare tra i Processi in corso, Iniziare un nuovo Processo e Creare un Link al Calendario della To Do List

