---
layout: default
title: Verbale_24-11-29_v1.0
permalink: docs/RTB/verbali_interni/verbale_24-11-29_v1.0.html
---

<h2>Download</h2>

<a href="https://raw.githubusercontent.com/code7crusaders/docs/develop/pdf/2_RTB/verbali_interni/verbale_24-11-29_v1.0.pdf" class="github-button" download>
    <span class="github-icon">🐙</span> 
    Scarica PDF da GitHub
</a>

# Riunione Settimanale 29/11/2024

**Ver.** | **Data** | **Autore** | **Verificatore** | **Descrizione**
---|---|---|---|---
1.0 | 29/11/2024 | Enrico Cotti Cottini | Gabriele Di Pietro | Stesura verbale

# Registro Presenze
**Piattaforma della riunione:** Piattaforma Discord

**Ora di Inizio:** 14:00

**Ora di Fine:** 15:00

**Componente** | **Ruolo** | **Presenza**
---|---|---
Enrico Cotti Cottini | Verificatore | Presente
Gabriele Di Pietro | Analista | Presente
Tommaso Diviesti | Amministratore | Presente
Francesco Lapenna | Programmatore | Presente
Matthew Pan | Verificatore | Presente
Eddy Pinarello | Progettista | Presente
Filippo Rizzolo | Responsabile | Assente

# Ordine del Giorno
- Automatizzare Glossario
- Diagramma Casi D'Uso
- Aggiornamento Norme di Progetto
- Aggiornamento Piano di Progetto
- Prima Bozza di Architettura del Software e Tecnologie da utilizzare

# Verbale Retrospettiva
#### Automatizzazione link Glossario pdf
**Sintesi**: Avevamo la necessità di trovare un modo immediato per fornire le definizioni delle parole del glossario presenti in qualsiasi documento. Abbiamo risolto tramite la creazione di uno script in Python che sostituisce ogni occorrenza di una parola del glossario con un link che punta alla sua definizione presente sul glossario del sito dei Code7Crusaders (**Glossario**).
**Difficoltà**: Abbiamo riscontrato qualche problema nell’utilizzo di questo metodo come ad esempio alcune eccezzioni non gestite.
**Decisioni**: Tutto sommato il sistema funziona bene e ci permette di risparmiare tempo e fatica, in futuro pianifichiamo di migliorare la gestione delle eccezzioni, ma per ora possiamo considerare il problema risolto.

#### Diagramma dei Casi D'Uso e User stories
**Sintesi**: Dopo alcune discussioni con l’azienda e tramite analisi del capitolato, abbiamo individuato i casi d’uso e le user stories principali su cui basarci per costruire il diagramma dei casi d’uso.
**Decisioni**: Abbiamo deciso di utilizzare il software **draw.io** per la creazione del diagramma dei casi d’uso e user stories abbiamo condiviso tutto il materiale sul nostro Google Drive interno.

#### Norme di Progetto
**Sintesi**: Abbiamo ampliato le norme di progetto con nuove regole riguardanti la stesura dei documenti, incluse le regole e codifiche per la redazione dei casi d’uso all’interno dell’analisi dei requisiti.
**Decisioni**: Ci siamo accordati per decidere alcune norme riguardanti la stesura dei documenti come codifiche analisi e altro.

#### Piano di Progetto
**Sintesi**: Abbiamo iniziato ad analizzare i requisiti necessari per la redazione del piano di progetto che svilupperemo più corposamente nelle prossime settimane.
**Decisioni**: Nessuna decisione particolare presa.

#### Prima Bozza di Architettura del Software e Tecnologie da utilizzare
**Sintesi**: Durante l’analisi dei requisiti, abbiamo iniziato a delineare una prima bozza dell’architettura del software e delle tecnologie che utilizzeremo. Questo ha reso necessario un approfondimento su alcune tecnologie candidate.
**Decisioni**: Vista la necessità di approfondire alcune tecnologie, abbiamo deciso di dedicare del tempo allo studio e alla sperimentazione di queste ultime. In particolare, abbiamo realizzato un prototipo di un sistema di interrogazione basato su BLOOM eseguito in locale. Da questa esperienza, abbiamo concluso che la realizzazione con questo tipo di modello è fattibile, ma richiede ulteriori approfondimenti su modelli accessibili tramite API esterne (ad esempio GPT di OpenAI), a causa degli elevati requisiti hardware richiesti per eseguire BLOOM.

#### Conclusioni e Pianificazione
**Conclusioni**: Durante la riunione, abbiamo raggiunto diversi obiettivi, tra cui la creazione di uno script per automatizzare i link del glossario, l’elaborazione di user stories e casi d’uso principali, e la definizione di una prima bozza dell’architettura del software. Inoltre, abbiamo ampliato le norme di progetto e iniziato a strutturare il piano di progetto. Nonostante alcune difficoltà tecniche, come la gestione delle eccezioni nello script Python, il lavoro complessivo è stato positivo e ha posto le basi per sviluppi futuri.
**Pianificazione per la prossima settimana:**
- Migliorare la gestione delle eccezioni nello script Python per i link del glossario.
- Contattare l’azienda per verificare se i casi d’uso individuati soddisfano le loro esigenze.
- Contattare il Professor Cardin per analizzare la correttezza dei casi d’uso e.
- Completare (eventualmente correggere) il diagramma dei casi d’uso e consolidare le user stories, una volta approvati, ricavare i requisiti dai casi d’uso.
- Continuare a lavorare sulle norme di progetto e sul piano di progetto, aggiungendo ulteriori dettagli.Analizzare il caso OpenAI per valutare se è più adatto rispetto ad altre soluzioni, considerando i requisiti specifici del nostro progetto.

La prossima riunione è pianificata per il **06/12/2024**, con l’obiettivo di analizzare i progressi ottenuti
e pianificare i prossimi passi.