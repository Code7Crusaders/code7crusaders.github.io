---
layout: default
title: Valutazione Capitolati
---

**Code7Crusaders**\
Software Development Team\

**Valutazione Capitolati**\

**Membri del Team:**\
Enrico Cotti Cottini, Gabriele Di Pietro, Tommaso Diviesti\
Francesco Lapenna, Matthew Pan, Eddy Pinarello, Filippo Rizzolo\
:::

::: center
**Versioni**\
\

   **Ver**   **Data**        **Autore**                 **descrizione**
  --------- ---------- ---------------------- -----------------------------------
     1.0     25/10/24   Enrico Cotti Cottini             Approvazione
     0.3     25/10/24     Filippo Rizzolo      Revisione e controllo ortografico
     0.2     25/10/24    Gabriele Di Pietro    Aggiunta Scelta Finale Capitolato
     0.1     21/10/24     Tommaso Diviesti        Prima stesura del documento
:::

# Introduzione

Questo documento raccoglie le considerazioni fatte dal team
Code7Crusaders riguardo ai capitolati proposti per il progetto di
Ingegneria del Software, consultabili a
<https://www.math.unipd.it/~tullio/IS-1/2024/Progetto/Capitolati.html>

Segue una descrizione dei capitolati presi in considerazione dal team
durante la fase di valutazione. Sarà presente una sezione che elenca
aspetti positivi e negativi dei vari capitolati. Infine verrà presentata
la scelta del capitolato scelto dal team.

# Descrizione dei Capitolati

## Capitolato C2 VimarGENIALE - Vimar

### Descrizione

Il capitolato **Vimar GENIALE**, proposto da Vimar S.p.A., ha come
obiettivo principale la realizzazione di un'applicazione per supportare
gli installatori nella ricerca di informazioni tecniche sui prodotti
Vimar. Il sistema sarà basato su modelli di intelligenza artificiale
(LLM) che consentiranno di rispondere a richieste in linguaggio naturale
riguardanti le specifiche tecniche e l'installazione dei prodotti.

### Dominio Applicativo

Il dominio applicativo riguarda l'ambito della **domotica** e delle
**smart home**. Vimar offre dispositivi come interruttori connessi,
termostati e comandi per tapparelle, integrabili in impianti:

-   **Tradizionali**: dispositivi controllati manualmente senza
    automazioni.

-   **Smart**: dispositivi connessi e controllabili da remoto tramite
    tecnologie wireless come Bluetooth e ZigBee.

-   **Domotici**: sistemi avanzati con automazioni e controllo remoto
    completo.

### Dominio Tecnologico

Il dominio tecnologico prevede l'uso di tecnologie **Cloud-ready** come
Docker e Terraform per la containerizzazione. L'intelligenza artificiale
sarà integrata tramite modelli LLM open source (ad es. Llama, Mistral).
L'applicazione sfrutterà tecniche di **Web Scraping** e **OCR** per
raccogliere e indicizzare informazioni tecniche dai prodotti presenti
sul sito di Vimar.

### Pro e Contro

#### Pro

-   Utilizzo di tecnologie avanzate come LLM e OCR.

-   Applicazione pratica nel settore della domotica.

-   Supporto diretto agli installatori, migliorando l'efficienza
    lavorativa.

#### Contro

-   Complessità nell'integrazione di diverse tecnologie.

## Capitolato C5 3Dataviz - Sanmarco Informatica

### Descrizione

Il capitolato, proposto da Sanmarco Informatica S.p.A., ha come
obiettivo la realizzazione di un'interfaccia web per la visualizzazione
tridimensionale di dati. Questo progetto mira a tradurre grandi volumi
di informazioni in un formato visuale interattivo, facilitando
l'interpretazione dei dati e supportando il processo decisionale.

### Dominio Applicativo

Il dominio applicativo riguarda la visualizzazione dei dati. Il sistema
consentirà di rappresentare informazioni quantitative in un ambiente 3D,
utilizzando un istogramma tridimensionale per la presentazione e
navigazione dei dati, permettendo all'utente di analizzare grandi
dataset in maniera chiara e interattiva.

### Dominio Tecnologico

Il progetto si inserisce nel dominio tecnologico dello sviluppo web,
facendo uso di tecnologie moderne per la visualizzazione grafica e
l'interazione utente. Le tecnologie principali includono *Three.js*, una
libreria JavaScript per la grafica 3D basata su WebGL, e *D3.js*,
utilizzata per produrre visualizzazioni dinamiche e interattive. Sono
suggeriti framework frontend come *React* e *Angular* per la
realizzazione dell'interfaccia utente.

### Pro e Contro

#### Pro

-   Utilizzo di tecnologie moderne come Three.js e D3.js.

#### Contro

-   Necessità di competenze avanzate in grafica 3D e sviluppo web.

-   Possibili problemi di performance con dataset molto grandi.

## Capitolato C7 Assistente Virtuale - Ergon

### Descrizione

Il progetto prevede lo sviluppo di un assistente virtuale che permetta
ai clienti di un'azienda di ricercare informazioni sui prodotti
disponibili, rispondendo alle domande più frequenti. L'obiettivo è
migliorare l'interazione uomo macchina, ottimizzando l'acquisizione
delle informazioni sui prodotti e riducendo la necessità di intervento
umano.

### Dominio Applicativo

Il dominio applicativo si colloca nelle aziende che vendono prodotti
attraverso cataloghi molto ampi e diversificati, in cui la conoscenza
approfondita dei prodotti è solitamente affidata a specialisti. Il
sistema mira a facilitare l'accesso alle informazioni sui prodotti,
migliorando la gestione delle richieste da parte dei clienti.

### Dominio Tecnologico

Il progetto sfrutta modelli linguistici di grandi dimensioni, come BLOOM
o Falcon, che permettono di elaborare e generare risposte a domande
complesse. Il sistema sarà composto da un database relazionale, un
modello LLM e un'interfaccia utente mobile che consente una facile
interazione con l'assistente virtuale, utilizzando API REST per la
comunicazione tra i vari componenti.

### Pro e Contro

#### Pro

-   Utilizzo di modelli linguistici meno conosciuti come BLOOM
    (alternative italiane).

#### Contro

-   Complessità nella gestione e integrazione dei modelli LLM.

-   Potenziali problemi di accuratezza nelle risposte generate
    dall'assistente.

## Capitolato C9 BuddyBot - AzzurroDigitale

### Descrizione

Il capitolato BuddyBot è proposto da Azzurrodigitale e prevede la
realizzazione di un assistente virtuale basato su intelligenza
artificiale. L'obiettivo principale è migliorare l'efficienza dei team
di sviluppo aziendale, centralizzando e semplificando l'accesso alle
informazioni provenienti da diverse piattaforme come GitHub, Confluence,
Jira, e Slack tramite un'interfaccia chat.

### Dominio Applicativo

Il dominio applicativo riguarda la gestione delle informazioni e delle
conoscenze all'interno di team di sviluppo software. L'assistente
virtuale mira a facilitare l'onboarding, ottimizzare i flussi di lavoro
e ridurre il tempo speso a cercare risposte attraverso la
centralizzazione delle fonti informative.

### Dominio Tecnologico

Il dominio tecnologico include l'utilizzo di tecnologie basate su
intelligenza artificiale, tra cui API di terze parti come OpenAI per la
comprensione del linguaggio naturale. Inoltre, verranno utilizzate
tecnologie web moderne come Angular per il front-end, Node/NestJS per il
back-end, e database per la persistenza delle informazioni scambiate con
l'assistente.

### Pro e Contro

#### Pro

-   Centralizzazione delle informazioni provenienti da diverse
    piattaforme.

-   Utilizzo di tecnologie moderne e API di terze parti.

#### Contro

-   Complessità nell'integrazione di diverse piattaforme.

-   Potenziali problemi di sicurezza e privacy dei dati.

# Scelta del Capitolato

Dopo la presentazione dei capitolati in aula e una discussione interna,
abbiamo concordato che il capitolato più interessante per il nostro team
fosse il **C2 VimarGENIALE** proposto da **Vimar**. Abbiamo comunque
deciso di mantenere un approccio aperto e valutare anche altri
capitolati proposti che ci sembravano interessanti, per avere una
visione più completa delle opportunità offerte dai vari progetti. Dopo
aver contattato le aziende, abbiamo organizzato degli incontri per
approfondire i dettagli dei capitolati. Ne è emerso che il capitolato
**C7 Assistente Virtuale** - **Ergon** è quello che più ci ha convinto.
Purtroppo non siamo riusciti a organizzare un incontro con l'azienda
Vimar, quindi, a parità di interesse tra i due capitolati, abbiamo
deciso di scegliere il capitolato **C7**, poiché nella valutazione
abbiamo tenuto conto anche della disponibilità dell'azienda a
collaborare con noi. Grazie a tutti gli incontri organizzati con le
aziende ci siamo fatti un idea più precisa di quali possano essere gli
strumenti e i requisiti necessari per lo sviluppo del progetto,
sopratutto per quanto riguarda il tema degli LLM trattati da 3 dei 4
capitolati che abbiamo valutato più approfonditamente. In conclusione il
capitolato scelto è il **C7 Assistente Virtuale** - **Ergon**,
concordato tramite votazione interna al team.
