---
layout: default
title: Verbale esterno AzzurroDigitale 17/10/2024
---

**Code7Crusaders**\
Software Development Team\

**Incontro del 17/10/2024 con AzzurroDigitale**\

**Membri del Team:**\
Enrico Cotti Cottini, Gabriele Di Pietro, Tommaso Diviesti\
Francesco Lapenna, Matthew Pan, Eddy Pinarello, Filippo Rizzolo\
:::

::: center
**Versioni**\

   **Ver.**    **Data**         **Autore**                          **Descrizione**
  ---------- ------------ ---------------------- ------------------------------------------------------
     1.0      28/10/2024     Filippo Rizzolo                     Approvazione documento
     0.3      22/10/2024     Filippo Rizzolo      Prima revisione del documento e controllo ortografia
     0.2      21/10/2024   Enrico Cotti Cottini                    Aggiunte Presenze
     0.1      17/10/2024      Eddy Pinarello                  Prima stesura del documento
:::

# Registro Presenze

**Piattaforma della riunione:** Google Meet\
**Ora di Inizio** 12:30\
**Ora di Fine** 13:00\
\

      **Componente**        **Ruolo**      **Presenza**
  ---------------------- ---------------- --------------
   Enrico Cotti Cottini    Responsabile      Presente
    Gabriele Di Pietro      Redattore        Assente
     Tommaso Diviesti       Redattore        Presente
    Francesco Lapenna      Verificatore      Presente
       Matthew Pan         Verificatore      Assente
      Eddy Pinarello        Redattore        Presente
     Filippo Rizzolo      Amministratore     Presente

\

        **Nome**              **Ruolo**
  -------------------- ------------------------
    Martina Daniele     Rappresentante Azienda
    Giorgio Vallini     Rappresentante Azienda
     Nicola Boscaro     Rappresentante Azienda
   Mattia Gottardello   Rappresentante Azienda

# Verbale dell'incontro

## Complessità Progetto

**Domanda:** Quali sono gli elementi di complessità maggiore nel
progetto, ovvero le parti più difficili da implementare? *Risposta:* La
gestione del backend che integra l'uso di OpenAI, la ricezione e invio
di domande e risposte, l'acquisizione di dati da diverse piattaforme, e
la gestione di un database vettoriale. Stiamo considerando PostgreSQL
come database principale.

## Piattaforma per la comunicazione

**Domanda:** Quali strumenti utilizza l'azienda per comunicare e per i
colloqui? È prevista la possibilità di incontri di persona? *Risposta:*
Usiamo Google Meet per gli incontri e per la gestione burocratica.
Questo è lo standard di comunicazione.

## Framework utilizzabili

**Domanda:** Quali framework possiamo utilizzare per lo sviluppo del
progetto? Angular è obbligatorio? *Risposta:* Se Angular non è lo
strumento con cui ci sentiamo più a nostro agio, possiamo scegliere un
altro framework, purché si raggiunga il risultato.

## Linee guida per API di terze parti

**Domanda:** Ci sono linee guida specifiche per l'integrazione di API di
terze parti? *Risposta:* Ogni piattaforma ha la propria documentazione
per le API. È utile identificare prima i servizi già esistenti con
connettori pronti, per evitare di dover creare integrazioni dirette da
zero.

## Modelli LLM utilizzabili

**Domanda:** Possiamo utilizzare modelli LLM open-source se necessario?
*Risposta:* Sì, possiamo utilizzare modelli open-source, soprattutto se
ChatGPT non soddisfa completamente i requisiti. È essenziale che le
risposte siano rapide e non abbiano latenze eccessive.

## Alternative a LangChain e OpenAI

**Domanda:** Ci sono alternative a LangChain o OpenAI per la gestione
del progetto? *Risposta:* LangChain è uno dei framework consigliati, ma
ciò che conta di più è il risultato. Se ci sono difficoltà con gli
strumenti core, si possono considerare altre soluzioni.

## Aree di maggiore focus

**Domanda:** Su quali aspetti dovremmo concentrarci maggiormente nel
progetto? *Risposta:* Concentratevi soprattutto sugli aspetti relativi
ai modelli LLM, poiché rappresentano la parte meno solida del progetto.
Il resto dovrebbe essere più agevole.

## Test e bug reporting

**Domanda:** Come gestire il testing e il reporting dei bug nel
progetto? *Risposta:* Per il bug reporting, utilizziamo la sezione
*Issues* di GitHub. Il docente richiede anche unit test per coprire il
codice. Possiamo seguire una metodologia TDD, ma l'importante è arrivare
al risultato con una copertura sufficiente del codice.

  -------- --
  Data:    
           
           
  Firma:   
  -------- --
