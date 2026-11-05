# Naxos Full Stack Challenge

## 🎯 Obiettivo

Questa challenge ha l'obiettivo di valutare le tue competenze Full Stack attraverso la realizzazione di una piccola applicazione.

Non è un test da completare perfettamente, ma un'occasione per capire come affronti un progetto, quali decisioni prendi e come organizzi il lavoro tra frontend, backend e database.

Ci interessa soprattutto capire il tuo approccio, le tue scelte e il modo in cui colleghi le diverse parti dell'applicazione.

## ⚙️ Contesto

La challenge parte dalla realizzazione di una piattaforma per la gestione di appuntamenti e servizi professionali.

L'idea di base è quella di un'applicazione in cui vengono offerti servizi, gestite disponibilità e prenotati appuntamenti.

Puoi scegliere liberamente il dominio applicativo e adattare il contesto alle tue esigenze, mantenendo le funzionalità principali richieste dalla challenge.

Puoi inoltre decidere come organizzare il sistema: ad esempio, prevedere un singolo professionista o una struttura con più professionisti.

Non esiste un'unica soluzione corretta: l'importante è che le scelte siano coerenti e motivate.

## 🧠 Approccio richiesto

Non è necessario completare tutto.

Ci interessa capire:

- Cosa ritieni importante realizzare.
- Come organizzi il lavoro.
- Quali scelte fai e perché.
- Come gestisci eventuali dubbi o ambiguità.
- Cosa decidi di non implementare e per quale motivo.

Non limitarti a far funzionare l'applicazione: cerca di rendere comprensibili le decisioni che prendi durante lo sviluppo.

## 📌 Minimo atteso (per orientarti)

Per avere un riferimento, la soluzione dovrebbe prevedere almeno:

- Un database per gestire utenti, servizi, disponibilità e appuntamenti;
- un sistema di registrazione e autenticazione;
- una distinzione tra clienti e professionisti, coerente con il modello scelto;
- API per consultare e gestire servizi e disponibilità;
- la possibilità di creare e consultare appuntamenti;
- un'interfaccia che permetta di utilizzare le funzionalità principali;
- integrazione coerente tra frontend e backend;
- validazioni e gestione degli errori;
- una funzionalità che impedisca la prenotazione di appuntamenti sovrapposti.

Questi punti sono un riferimento, non una lista di istruzioni da seguire obbligatoriamente alla lettera.

## 🚀 Come partecipare

1. Fai un fork di questo repository.
2. Lavora sulla tua copia del progetto.
3. Completa la challenge secondo le tue scelte.
4. Inserisci il link GitHub nel tuo profilo Naxos.

## 🧩 Task

### 1. Database, Data Modeling & Security

Progetta il database necessario per gestire le informazioni dell'applicazione.

Dovrai considerare:

- Utenti.
- Servizi.
- Disponibilità.
- Appuntamenti.

Sei libero di scegliere il tipo di database e la struttura che ritieni più adatta.

Valuteremo:

1- La coerenza del modello dei dati.

2- Le relazioni tra le diverse entità.

3 - Le scelte relative a tabelle, collezioni, chiavi e vincoli.

4 - La gestione e la protezione dei dati.

5 - Il controllo degli accessi alle risorse.

### 2. API Design & Integration

Realizza le API necessarie per collegare frontend e backend.

L'applicazione dovrebbe permettere di:

- Consultare i servizi disponibili;
- gestire i servizi offerti;
- consultare le disponibilità;
- creare appuntamenti;
- visualizzare gli appuntamenti.

Sei libero di scegliere rotte, metodi HTTP, struttura delle risposte e modalità di comunicazione tra frontend e backend.

Valuteremo la coerenza delle API, la loro organizzazione e l'effettiva integrazione con il frontend.

### 3. Authentication, Authorization & Forms

Implementa un sistema di registrazione e login.

L'applicazione dovrà prevedere almeno una distinzione tra clienti e professionisti, coerente con il modello organizzativo scelto.

Considera:

- Gestione dell'autenticazione;
- ruoli o tipologie di utenti;
- protezione delle API;
- permessi in base all'utente autenticato;
- form per le operazioni principali;
- validazione dei dati inseriti.

Le autorizzazioni devono essere gestite anche lato backend: un utente non deve poter accedere o modificare risorse di altri utenti senza averne i permessi.

### 4. UX & Frontend

Realizza un'interfaccia che permetta di utilizzare le funzionalità principali dell'applicazione.

Considera:

- Consultazione dei servizi;
- visualizzazione delle disponibilità;
- creazione e consultazione degli appuntamenti;
- gestione degli stati di caricamento;
- feedback dopo le operazioni;
- gestione degli errori e degli stati vuoti.

Sei libero di organizzare schermate e flussi come ritieni più opportuno.

### 5. Code Quality

Organizza il codice in modo chiaro e comprensibile.

Valuteremo:

- Struttura del progetto;
- separazione delle responsabilità;
- organizzazione della logica;
- riuso dei componenti e delle funzioni;
- leggibilità e manutenibilità;
- scelte architetturali coerenti con la dimensione del progetto.

Non è necessario utilizzare pattern complessi: è importante che le soluzioni adottate siano motivate e adeguate.

### 6. Appuntamenti e conflitti temporali

L'applicazione deve impedire la creazione di appuntamenti che si sovrappongono a disponibilità già occupate.

Ad esempio, se un professionista ha già un appuntamento dalle 10:00 alle 11:00, non deve essere possibile creare un altro appuntamento che si sovrapponga, anche solo parzialmente, a quello già esistente.

Il controllo deve essere effettuato lato backend.

Sei libero di scegliere come gestire questa logica. Valuteremo anche come affronti eventuali casi limite.

Non è necessario realizzare un calendario avanzato.

## 📌 Nota importante

La valutazione terrà conto dell'intero progetto e non soltanto del risultato finale.

Osserveremo in particolare:

- La progettazione del database;
- la struttura e la coerenza delle API;
- l'integrazione tra frontend e backend;
- la gestione di autenticazione e autorizzazioni;
- la validazione dei dati e la gestione degli errori;
- l'organizzazione e la qualità del codice;
- la gestione degli appuntamenti e dei conflitti temporali.

## 🧠 Prima di iniziare

Prima di iniziare lo sviluppo, dedica qualche minuto a descrivere brevemente il tuo approccio.

In 3–5 righe, raccontaci:

- Da dove partiresti.
- Quali aspetti ritieni più importanti.
- Se ci sono dubbi o ambiguità che vorresti chiarire.

Non cerchiamo una risposta giusta, ma vogliamo capire come imposti il lavoro.

## 🧠 README finale

Al termine della challenge, aggiungi un README al repository in cui descrivi brevemente:

- Le principali decisioni progettuali e il motivo delle tue scelte;
- come hai strutturato il database e perché;
- come hai organizzato frontend e backend;
- come hai gestito autenticazione e autorizzazioni;
- cosa non hai realizzato e perché;
- quali compromessi hai fatto;
- cosa miglioreresti avendo più tempo;
- se e come hai utilizzato strumenti di AI durante lo sviluppo.

Indica inoltre le istruzioni necessarie per avviare il progetto.

Non serve un documento lungo: ci interessa che le tue scelte siano comprensibili.

## ⚙️ Stack

Puoi scegliere liberamente le tecnologie da utilizzare per frontend, backend e database.

Non ci sono vincoli su linguaggi, framework o librerie.

Puoi anche utilizzare framework che integrano frontend e backend, se lo ritieni opportuno.

La valutazione non dipenderà dalla tecnologia scelta, ma da come la utilizzi e dalle decisioni che prendi.

## ⏱️ Tempo

Il tempo indicativo per realizzare una soluzione base funzionante è di 120–180 minuti.

Puoi dedicare ulteriore tempo alle rifiniture, ma non è necessario completare ogni funzionalità in modo perfetto.

L'obiettivo non è realizzare un prodotto finito, ma mostrarci come affronti un'attività Full Stack.

## 📦 Output

Assicurati che il repository contenga:

- Il codice sorgente del progetto.
- Il README con le informazioni sulle scelte progettuali e le istruzioni per avviare l'applicazione.

## 🧠 Valutazione

La challenge sarà valutata da una persona del team Naxos attraverso le seguenti categorie:

- Database, Data Modeling & Security;
- API Design & Integration;
- Authentication, Authorization & Forms;
- UX & Frontend;
- Code Quality;
- Thinking / Decision Making.

La valutazione terrà conto sia delle competenze tecniche sia della capacità di affrontare problemi, prendere decisioni e motivare le proprie scelte.

## 💬 Feedback

Dopo aver completato la challenge, ti chiediamo di condividere un breve feedback:

- Come hai trovato il livello di difficoltà?
- Le indicazioni erano sufficientemente chiare?
- La challenge ti è sembrata realistica rispetto a un'attività Full Stack?
