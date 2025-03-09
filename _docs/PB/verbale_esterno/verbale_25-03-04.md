---
layout: default
title: Verbale_25-03-04_v1.0
permalink: docs/PB/verbale_esterno/verbale_25-03-04.html
---

<h2>Download</h2>

<a href="https://raw.githubusercontent.com/code7crusaders/docs/develop/pdf/3_PB/verbali_esterni/firmati/verbale_25-03-04_v1.0_firm.pdf" class="github-button" download>
    <span class="github-icon">🐙</span> 
    Scarica PDF da GitHub
</a>

# Incontro del 04/03/2025 con Ergon

**Ver.** | **Data** | **Autore** | **Verificatore** | **Descrizione**
---|---|---|---|---
1.0 | 05/03/2025 | Lapenna Francesco | Eddy Pinarello | Prima stesura e approvazione del documento

## Registro Presenze

**Piattaforma della riunione**: Piattaforma Zoom

**Ora di Inizio**: 09:30

**Ora di Fine**: 10:00

**Componente**| **Ruolo** | **Presenza**
---|---|---
Enrico Cotti Cottini | Responsabile | Presente
Gabriele Di Pietro | Redattore | Presente
Tommaso Diviesti | Redattore | Presente
Francesco Lapenna | Redattore | Presente
Matthew Pan | Verificatore | Presente
Eddy Pinarello | Redattore | Presente
Filippo Rizzolo | Amministratore | Presente

**Nome** | **Ruolo**
---|---
Gianluca Carlesso | Rappresentante Azienda

## Ordine del Giorno
- Negoziazione dei requisiti con l'azienda a causa dell'aumento del budget.
- Decisioni conclusioni sui requisiti da negoziare

## Verbale 
**Sintesi:** A causa di un aumento del budget previsto, come indicato nella correzione del colloquio RTB, sono stati negoziati alcuni requisiti con l'azienda.
In particolare i requisiti riguardanti il monitoraggio delle metriche da parte dell'amministratore, i quali sono stati ritenuti non essenziali.

**Decisioni:** I seguenti requisiti funzionali diventano facoltativi:

**Codice** | **Fonte** | **Descrizione**
---|---|---
**RFO28**|Interno| L’amministratore deve poter accedere alla dashboard di monitoraggio delle metriche.
**RFO29**|Interno| L’accesso alla dashboard delle metriche delle run è consentito solo agli utenti con ruolo di amministratore.
**RFO30**|Interno| Dopo l’accesso da parte dell’amministratore, la pagina di gestione mostra la dashboard delle metriche delle run.
**RFD31**|Interno| L’amministratore deve poter selezionare criteri di filtro per visualizzare solo le run di interesse.
**RFD32**|Interno| Il sistema deve permettere la selezione di filtri come ID, nome, input, data di inizio e fine, errore, output, tag, numero di token, costo.
**RFF33**|Interno| Una volta selezionati i filtri, il sistema deve aggiornare la visualizzazione senza ricaricare l’intera pagina.
**RFO34**|Interno| Se nessun filtro è selezionato, il sistema mostra le prime dieci run per impostazione predefinita.
**RFD35**|Interno| Dopo aver applicato i filtri, l’amministratore deve poter visualizzare le metriche principali delle run selezionate.
**RFD36**|Interno| Il sistema deve mostrare le metriche principali delle run filtrate (ID, nome, input, data di inizio e fine, errore, output, tag, token totali, costo totale).
**RFF37**|Interno| La visualizzazione deve essere chiara e strutturata, con possibilità di ordinare le colonne.
**RFD47**|Interno| Le metriche delle run del chatbot devono essere esportabili in `.JSON`.
**RFD48**|Interno| Le metriche della run devono includere ID univoco della run, nome assegnato alla sessione, dati di input elaborati dal modello, timestamp di avvio e completamento dell’esecuzione, eventuali errori incontrati, risultato generato dal modello, numero totale di token utilizzati e stima dei costi basata sul consumo di token.

<p align="center">Tabella 1: Requisiti funzionali (da Analisi dei Requisiti)</p>

### **Conclusioni**
**Prossimi Passi:** Definire l'architettura del sistema e aggiungere funzionalità all'applicazione in modo tale da soddisfare i requisiti.

