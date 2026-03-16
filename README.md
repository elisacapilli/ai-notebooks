# Verifica automatica e crowdsourced delle informazioni
Questo repository contiene codice Python sviluppato per tesi magistrale che esplora l'uso di **Large Language Models (LLM)** per supportare i processi di fact-checking.

Il progetto prevede due scenari sulla verifica di 100 affermazioni politiche:
1. **Scenario 1 – Autonomo**  
   Il modello (Gemma 2B o Mistral 7B) valuta le affermazioni senza alcun input esterno.  
   Il verdetto di veridicità è basato esclusivamente sulle conoscenze del modello.

2. **Scenario 2 – Supportato da crowd**  
   Il modello riceve le stesse affermazioni insieme a **5 valutazioni umane** ottenute tramite crowdsourcing.  
   L’obiettivo è determinare quanto il contributo umano migliori la capacità di fact-checking del modello.

**Tecnologie utilizzate:** Python, Jupyter Notebook, Pandas, LLMs (Gemma 2B, Mistral 7B).

Questo progetto dimostra competenze in programmazione Python, gestione dati, applicazioni AI e analisi collaborativa.

---

## Notebooks inclusi

### `10_stats_Gemma.ipynb` – 10 affermazioni con Gemma
L'obiettivo è valutare come il contributo umano possa migliorare le capacità di fact-checking dei LLM open-source.

**Tecnologie utilizzate:** Python, Jupyter Notebook, Pandas, LLMs (Gemma 2B, Mistral 7B).

Questo progetto dimostra competenze in programmazione Python, gestione dati, applicazioni di AI e analisi collaborativa.

## Notebooks inclusi
### '10_stats_Gemma.ipynb' (10 Statements con Gemma)
Seleziona 10 affermazioni a caso dal dataset e le passa al modello **Gemma 2B**.  

### '10_stats_Mistral.ipynb' (10 Statements con Mistral)
Stesso procedimento di '10_stats_Gemma.ipynb', ma con il modello **Mistral 7B**.

### '1_stat_Gemma.ipynb' (1 Statement + 5 valutazioni con Gemma)
Valuta una singola affermazione usando 5 punteggi ottenuti da crowdsourcing.

### '1_stat_Mistral.ipynb' (1 Statement + 5 valutazioni con Mistral)
Stesso procedimento di '1_stat_Gemma.ipynb', ma con il modello **Mistral 7B**.

---


