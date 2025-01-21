---
layout: default
title: Verbale_24-11-14_v1.0
permalink: docs/RTB/verbali_esterni/verbale_24-11-14_v1.0.html
---

<h2>Download</h2>

<a href="https://raw.githubusercontent.com/code7crusaders/docs/develop/pdf/2_RTB/verbali_esterni/verbali_firmati/verbale_24-11-14_v1.0_firm.pdf" class="github-button" download>
    <span class="github-icon">🐙</span> 
    Scarica PDF da GitHub
</a>

# Incontro del 14/11/2024 con Ergon

**Ver.** | **Data** | **Autore** | **Verificatore** | **Descrizione**
---|---|---|---|---
1.0 | 20/11/2024 | Lapenna Francesco | Matthew Pan | Prima stesura del documento

# Registro Presenze
**Piattaforma della riunione:** Piattaforma Zoom

**Ora di Inizio:** 15:00

**Ora di Fine:** 16:00

**Componente** | **Ruolo** | **Presenza**
---|---|---
Enrico Cotti Cottini | Verificatore | Presente
Gabriele Di Pietro | Responsabile | Presente
Tommaso Diviesti | Redattore | Presente
Francesco Lapenna | Redattore | Presente
Matthew Pan | Verificatore | Presente
Eddy Pinarello | Redattore | Presente
Filippo Rizzolo | Amministratore | Presente

---

**Nome** | **Ruolo**
---|---
Gianluca Carlesso | Rappresentante Azienda

# Verbale
#### Preferenza tra App Mobile o Web App
**Domanda:** Preferite un’app mobile o va bene una web app?

**Discussione:** Sono state identificate due opzioni principali: Web app responsive e App mobile (consigliato l’uso di framework cross-platform come .NET MAUI).

**Conclusione:** L’azienda ha mostrato preferenza per soluzioni flessibili. È stato suggerito React come tecnologia per lo sviluppo web e, in alternativa, un’app Android se necessario.

#### Richiesta di un Dataset di Esempio2
**Domanda**: Potete fornire un dataset di esempio?

**Risposta**: Verrà fornito un database di bevande nei prossimi giorni.

#### Hardware per Modelli LLM
**Domanda**: Ci fornite una macchina per eseguire i modelli LLM? Quali specifiche hardware?

**Risposta**: L’azienda fornirà una macchina e il team di sviluppo potrà definire le specifiche hardware necessarie.

#### Requisiti Utente e Software
**Domanda**: Quali sono i requisiti utente e software?

**Risposta**: L’azienda fornirà una macchina e il team di sviluppo potrà definire le specifiche hardware necessarie.

#### PoC
**Domanda**:È sufficiente un’interfaccia da terminale che risponda per il PoC?

**Risposta**: Per la PoC è sufficiente una soluzione terminale che risponda alle domande. Una volta completata la logica del modello LLM, si procederà allo sviluppo dell’interfaccia grafica.

#### Target Di Riferimento
**Domanda**: Chi è il target?

**Risposta**: Utenti finali non esperti, come proprietari di pub o ristoranti nel settore alimentare. Attori coinvolti:
- L'azienda fornitrice che si interfaccia con la software house.
- La software house che si interfaccia con gli utenti finali

#### Unit Testing per l'LLM
**Domanda**: È necessario fare unit testing delle risposte dell’LLM?


**Risposta**: Non è possibile testare completamente le risposte dell’LLM con un altro modello. Verranno eseguiti test a livello umano per verificare la coerenza e la qualità delle risposte. L’LLM viene considerato un sistema ”Black Box” poich´e basato su modelli preaddestrati.

# Conclusioni
#### Prossimi Passi:
1. Ricevere il database di esempio dall'azienda
2. Definire le specifiche hardware per la macchina dedicata all'LLM
3. Lavorare su una PoC con interazione via terminale.
4. Identificare un approccio per raccogliere feedback utenti sulle risposte