---
layout: default
title: Verbale esterno Ergon 18/10/2024
---

**Code7Crusaders**\
Software Development Team\

**Incontro del 18/10/2024 con Ergon**\

**Membri del Team:**\
Enrico Cotti Cottini, Gabriele Di Pietro, Tommaso Diviesti\
Francesco Lapenna, Matthew Pan, Eddy Pinarello, Filippo Rizzolo\
:::

::: center
**Versioni**\

   **Ver**    **Data**         **Autore**                          **Descrizione**
  --------- ------------ ---------------------- ------------------------------------------------------
     1.0     28/10/2024     Filippo Rizzolo                     Approvazione documento
     0.3     22/10/2024     Filippo Rizzolo      Prima revisione del documento e controllo ortografia
     0.2     21/10/2024   Enrico Cotti Cottini                    Aggiunte Presenze
     0.1     18/10/2024      Eddy Pinarello                  Prima stesura del documento
:::

# Registro Presenze

**Piattaforma della riunione:** Zoom\
**Ora di Inizio** 11:00\
**Ora di Fine** 12:00\
\

      **Componente**        **Ruolo**      **Presenza**
  ---------------------- ---------------- --------------
   Enrico Cotti Cottini    Responsabile      Presente
    Gabriele Di Pietro      Redattore        Presente
     Tommaso Diviesti       Redattore        Presente
    Francesco Lapenna      Verificatore      Assente
       Matthew Pan         Verificatore      Assente
      Eddy Pinarello        Redattore        Presente
     Filippo Rizzolo      Amministratore     Presente

\

       **Nome**              **Ruolo**
  ------------------- ------------------------
   Gianluca Carlesso   Rappresentante Azienda
      Anna Tieppo      Rappresentante Azienda

# Verbale dell'incontro

## Utilizzo di .NET MAUI

**Domanda:** L'utilizzo di .NET MAUI è un vincolo obbligatorio oppure ci
sono altre alternative? *Risposta:* No, è facoltativo. Utilizzate ciò
che è più comodo per voi per ottenere il risultato.

## Fornitura di informazioni all'LLM

**Domanda:** Come possiamo dare le informazioni all'LLM? Ci verrà
fornita un'API o della documentazione? *Risposta:* Noi vi forniamo un
file contenente le informazioni del contesto di lavoro da cui l'AI
apprenderà. Possiamo concordare il formato e saremo noi a recuperare le
informazioni dai nostri clienti, che potrete utilizzare.

## Domande frequenti per l'allenamento dell'AI

**Domanda:** Quali sono le domande più frequenti su cui l'AI deve essere
allenata? *Risposta:* A livello di domande, si può strutturare la
chatbot in due modalità: una parte con domande predefinite, in cui l'AI
deve comprendere e rispondere, e una seconda parte con l'AI generativa,
dove l'LLM elabora la risposta basandosi solo sulla domanda.

## Chiarimento sull'AI

**Domanda:** L'AI che useremo è già pre-addestrata? *Risposta:* Sì, l'AI
è già pre-addestrata. I modelli vengono allenati su grandi moli di dati.
Nel nostro caso, la conoscenza fornita verrà trasmessa ai modelli, che
analizzeranno ed elaboreranno le risposte.

## Utilizzo di modelli proprietari

**Domanda:** Possiamo utilizzare modelli AI diversi da quelli
consigliati, ad esempio modelli proprietari? *Risposta:* Sì, potete
utilizzare altri modelli. Vi proponiamo quelli perché sono progetti
italiani e potrebbe essere interessante approfondirli. Se scegliete
modelli proprietari, dovrete usare strumenti black box. Non c'è un
vincolo specifico su queste tecnologie, ma noi consigliamo di usarle.

## Modello embedded a pagina 5

**Domanda:** Come funziona il modello embedded descritto a pagina 5?
*Risposta:* Gli LLM utilizzano database vettoriali. Il testo fornito per
l'apprendimento viene tokenizzato e rappresentato come un vettore, che
poi viene salvato nel database vettoriale. Successivamente, l'LLM
apprende da dati esterni che vengono forniti, a seconda del modello
scelto. Gli API ricevono le domande dagli utenti, le tokenizzano e le
passano all'LLM, che estrae le risposte dal database vettoriale. L'LLM
utilizza un modello probabilistico per definire il contesto della
domanda e fornire una risposta.

## Utilizzo di RAG come database vettoriale

**Domanda:** Consigliate di usare RAG come database vettoriale?
*Risposta:* Sì, consigliamo RAG perché è uno dei più diffusi e ha molta
documentazione disponibile. Posso eventualmente suggerirvi altri
database.

## Rappresentazione dei dati in formato JSON

**Domanda:** Nell'intermezzo tra database e LLM, è possibile
rappresentare i dati sotto forma di JSON? *Risposta:* Sì, questa è una
possibilità che offre maggiore libertà. Avendo i dati in formato JSON,
dovrete costruire l'interfacciamento e far comunicare i sistemi.
Tuttavia, i dati forniti dall'azienda potrebbero non essere perfetti,
quindi sarà necessaria una fase di pre-processing per eliminare
eventuali dati anomali, dopo di che potete salvarli nel formato che
preferite.

## Fasi di testing del prodotto

**Domanda:** Nelle specifiche del progetto sono richieste anche delle
fasi di testing del nostro prodotto. Ci sono delle linee guida o degli
strumenti che ci consigliate? *Risposta:* È preferibile fare i test
durante lo sviluppo del progetto. Avrete domande con risposte attese e
potrete creare test-set per verificare che il modello non presenti
problemi di overfitting.

## Strumenti per colloqui e chiarimenti

**Domanda:** Quale strumento usa l'azienda per eventuali colloqui e
chiarimenti specifici, o ci si può incontrare dal vivo? *Risposta:*
Possiamo utilizzare Zoom per i colloqui o incontrarci in sede. Negli
anni scorsi, i gruppi richiedevano incontri via Zoom e poi sono venuti
anche in sede.

## Esperienza con i gruppi precedenti

**Domanda:** Siccome non è il primo anno che proponete progetti ai
nostri ex-colleghi, ci sono state difficoltà particolari per loro?
*Risposta:* Non hanno avuto grosse difficoltà. Sono sempre stati
abbastanza autonomi e ci siamo sentiti settimanalmente via mail. Non ci
sono state particolari difficoltà, anzi, siamo stati molto soddisfatti
dal lavoro svolto.

  -------- --
  Data:    
           
           
  Firma:   
  -------- --
