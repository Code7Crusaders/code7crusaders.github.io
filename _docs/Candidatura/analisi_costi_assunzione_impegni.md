---
layout: default
title: Preventivo Costi Assunzione Impegni
---

**Code7Crusaders**\
Software Development Team\

**Analisi costi e assunzione impegni**

**Membri del Team:**\
Enrico Cotti Cottini, Gabriele Di Pietro, Tommaso Diviesti\
Francesco Lapenna, Matthew Pan, Eddy Pinarello, Filippo Rizzolo\
:::

::: center
**Versioni**\

   **Ver**   **Data**        **Autore**                                **descrizione**
  --------- ---------- ---------------------- ------------------------------------------------------------------
     0.4     30/10/24    Gabriele Di Pietro              Revisione del documento e correzione errori
     0.3     29/10/24   Enrico Cotti Cottini   Rivista analisi costo e considerazioni + Pianificazione Scadenze
     0.2     26/10/24    Gabriele Di Pietro                        Revisione del documento
     0.1     24/10/24     Tommaso Diviesti                       Prima stesura del documento
:::

# Descrizione

Il seguente documento rappresenta una dichiarazione degli impegni di
lavoro che ogni componente del Team assume in modo da riuscire a
completare al meglio il progetto entro la data di scadenza da noi
stabilita. Viene riportato il quantitativo in ore di lavoro individuale
e collettivo, in base al ruolo assunto, necessario per lo svolgimento
del progetto. Viene in seguito descritto ciascun ruolo presente per il
corretto svolgimento delle attività attraverso una serie di compiti
delegati e obbiettivi. Viene, infine, preventivato il costo finale e,
inoltre, stabilita la scadenza di consegna.

# Impegni orari {#sec:introduzione}

Tutti i componenti del Team Code7Crusaders si impegnano a dedicare un
totale di **95 ore** di lavoro effettivo partizionate settimanalmente in
base al ruolo di riferimento, allo svolgimento del capitolato **C7** di
**Ergon Informatica**. Inoltre, ciascun membro garantisce la conclusione
del progetto entro la data prevista e preventivata nel paragrafo 5 di
questo documento.\
\
Di seguito, si riporta il costo orario in base al ruolo assunto:

::: center
     **Ruolo**      **Costo orario** (€)   **per ruolo**   **Ore per membro**
  ---------------- ---------------------- --------------- --------------------
    Responsabile             30                 54                 8
   Amministratore            20                 64                 9
      Analista               25                 65                 9
    Progettista              25                 105                15
   Programmatore             15                 184                26
    Verificatore             15                 193                28
     **Totale**            12805                665                95

  : Costo orario e totale
:::

\
Ripartizione delle ore per membro del team:

::: center
        **Membro**        **Re**   **Am**   **An**   **Pj**   **Pg**   **Ve**   **Totale**
  ---------------------- -------- -------- -------- -------- -------- -------- ------------
   Enrico Cotti Cottini     8        9        9        15       26       28         95
    Gabriele Di Pietro      8        9        9        15       26       28         95
     Tommaso Diviesti       8        9        9        15       26       28         95
    Francesco Lapenna       8        9        9        15       26       28         95
       Matthew Pan          8        9        9        15       26       28         95
      Eddy Pinarello        8        9        9        15       26       28         95
     Filippo Rizzolo        8        9        9        15       26       28         95

  : Impegni orari a persona
:::

\
[Leggenda:]{.smallcaps}\
**Re** = Responsabile\
**Am** = Amministratore\
**An** = Analista\
**Pj** = Progettista\
**Pg** = Programmatore\
**Ve** = Verificatore\

# Suddivisione dei ruoli e considerazioni su essi

I ruoli in seguito descritti sono equamente divisi tra i vari componenti
del Team. Ogni ruolo possiede diversi incarichi e obbiettivi:

## Responsabile

Il **Responsabile** coordina il gruppo di lavoro, controlla le attività
e gestisce le risorse. Si occupa di garantire che il progetto venga
portato a termine nei tempi stabiliti e con le risorse disponibili.

## Amministratore

L'**Amministratore** si occupa della gestione delle risorse e delle
infrastrutture, incluso il setup degli strumenti di supporto alla
produzione del software. Garantisce inoltre l'uso corretto delle
procedure per assicurare efficienza e produttività.

## Analista

L'**Analista** gioca un ruolo fondamentale nella fase iniziale del
progetto. È responsabile della definizione dei requisiti e dell'analisi
delle funzionalità del software, delineando i casi d'uso. Essendo
necessario principalmente all'inizio del progetto, il numero di ore
assegnato al ruolo è relativamente ridotto.

## Progettista

Il **Progettista** definisce l'architettura del software, descrivendo le
componenti e le loro interazioni sulla base dei requisiti stabiliti
dall'Analista. Questo ruolo ha un numero di ore significativamente
elevato perché è essenziale per garantire una struttura solida,
soprattutto considerando l'implementazione di modelli *LLM*, che
richiedono un'architettura ben progettata e adattata a tali tecnologie.

## Programmatore

Il **Programmatore** si occupa di scrivere il codice del software
seguendo le specifiche del progettista. Il numero di ore assegnato è
alto, dato che rappresenta il cuore della fase di sviluppo. Tuttavia, il
ruolo ha leggermente meno ore rispetto al Verificatore, poiché abbiamo
scelto di adottare una metodologia incentrata sui test, che richiede
un'accurata verifica del software.

## Verificatore

Il **Verificatore** verifica che il software e la documentazione siano
conformi alle norme e alle specifiche. Questo ruolo richiede un numero
di ore superiore alla media, data la necessità di test approfonditi e
continui, in particolare per un progetto basato su *LLM*, dove ogni
componente deve essere rigorosamente validato per garantire la
precisione e l'affidabilità del sistema.

# Analisi dei rischi

In questa sezione vengono elencati i rischi che potrebbero verificarsi
durante lo svolgimento del progetto e le relative contromisure. Ad ogni
rischio è associato un **indice di Gravità e Probabilità**, in modo da
poter valutare la criticità di ciascuno di essi.

## Definizione degli indici

I valori dell'**Indice di Gravità** e dell'**Indice di Probabilità**
sono definiti come segue:

::: {#tab:definizione_indici}
   **Indice**   **Tipo**  **Gravità**                                                                                                                                                                                    **Probabilità**
  ------------ ---------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -----------------------------------------------------------------------------------------------------------------------------------
     **1**       Basso    Ha un impatto minimo o trascurabile sul progetto, come un lieve rallentamento che non incide sui tempi di consegna                                                                             Improbabile che si verifichi, ma esistono fattori che potrebbero contribuire alla sua realizzazione
     **2**       Medio    Se si concretizza, richiede risorse aggiuntive o modifica parzialmente il piano di progetto, causando impatti gestibili ma che comportano sforzi supplementari                                 C'è una possibilità realistica che l'evento di rischio si verifichi
     **3**        Alto    Causa ritardi significativi, aumento dei costi o degrado della qualità che incide sull'esperienza utente, richiedendo interventi importanti per mantenere il progetto nei tempi e nel budget   Esistono molti fattori o segni che indicano che il rischio potrebbe accadere, e il team considera probabile la sua manifestazione

  : Definizione degli Indici di Gravità e Probabilità
:::

## Rischi

::: {#tab:analisi_rischi}
  **ID**   **Rischio**                                                       **Gravità**   **Probabilità**
  -------- ----------------------------------------------------------------- ------------- -----------------
  1        Difficoltà nell'uso di nuove tecnologie                           2             3
  2        Codice non completato dal delegato                                2             2
  3        Riduzione del carico e delle ore di lavoro durante le festività   1             2
  4        Scarsa collaborazione da parte di uno o più membri del team       3             1
  5        Impegni personali e universitari                                  1             2
  6        Deviazione dai tempi e costi previsti                             3             1

  : Analisi dei rischi
:::

### Contromisura rischio 1

Il gruppo si impegnerà a studiare in modo approfondite le tecnologie
richieste dal capitolato in particolar modo lo studio dei *LLM*. E
verranno organizzati incontri di formazione interna in modo tale da
poter condividere le conoscenze acquisite per essere tutti sullo stesso
livello.

### Contromisura rischio 2

Il gruppo si impegnerà a chiedere supporto all'azienda e si cercherà di
massimizzare le risorse nel team nella soluzione di un problema.

### Contromisura rischio 3

Il gruppo cercherà di mantenere i ritmi feriali impostando un tempo
minimo di lavoro settimanale.

### Contromisura rischio 4

Il gruppo si impegna nella comprensione e nel chiarire quali siano i
ruoli, inoltre una comunicazione costante e trasparente aiuterà
sull'affrontare le diverse difficoltà e nel segnalare tempestivamente
eventuali problemi

### Contromisura rischio 5

Progettazione di un calendario condiviso dove ogni componente può
segnalare i propri impegni personali con anticipo. Di conseguenza
pianificare bene le varie attività evitando sovrapposizioni

### Contromisura rischio 6

Monitorare il progresso delle attività e svolgere frequenti riunioni per
valutare lo stato di avanzamento del progetto.

# Preventivo dei costi

In base alle valutazioni effettuate nel paragrafo 2, il costo finale del
progetto corrisponde a **12805**€.

# Pianificazione Scadenze

Il gruppo Code7Crusaders si impegna a consegnare il progetto entro il
**14/03/2025**. La pianificazione prevede *19 settimane di lavoro*,
suddivise come segue:

-   **PoC (*Proof of Concept*): 6 settimane**\
    Questa fase serve a testare rapidamente le tecnologie principali per
    verificare che siano adatte al progetto. Si sperimenteranno
    funzionalità essenziali per ridurre i rischi tecnici, specialmente
    per l'integrazione di modelli di Linguaggio di Modello (*LLM*).

-   **MVP (*Minimum Viable Product*): 13 settimane**\
    In questa fase, si svilupperà il prodotto base, con tutte le
    funzionalità principali pronte per l'uso. Verranno implementati
    anche i test necessari per garantire stabilità e usabilità, con un
    focus sui test per i modelli *LLM*.

Questa suddivisione permette di affrontare i rischi iniziali e di
completare il progetto in modo graduale e sicuro.