## Gruppo 11 - Previsione dell'Insolvenza Creditizia (Credit Card Default Prediction)

Progetto realizzato per il corso **Introduzione alla Data Science e al Pensiero Computazionale**  
Anno Accademico **2025/2026**

---

# Membri del gruppo

- **Mattia Galletti**
  - Matricola: 1216092
  - Email: mattia.galletti@studio.unibo.it

- **Jacopo Malagoli**
  - Matricola: 1226707
  - Email: jacopo.malagoli@studio.unibo.it

- **Vera Efua Van Dyke**
  - Matricola: 1216081
  - Email: veraefua.vandyke@studio.unibo.it

---

# Obiettivo del progetto

L'obiettivo del progetto è sviluppare un modello di Machine Learning capace di prevedere se un cliente andrà in **default sul pagamento della carta di credito nel mese successivo**.

L'analisi comprende tutte le principali fasi di un progetto di Data Science:

- analisi preliminare del dataset;
- data cleaning;
- analisi esplorativa (EDA);
- visualizzazione dei dati;
- costruzione e confronto di modelli di classificazione;
- valutazione critica dei risultati;
- redazione del report scientifico.

---

# Dataset

È stato utilizzato il dataset: **Credit Card Default**

contenente informazioni relative a **30.000 clienti** di un istituto bancario di Taiwan.

Le variabili descrivono:

- caratteristiche demografiche;
- limite di credito;
- storico dei pagamenti;
- importi fatturati;
- importi pagati;
- variabile target:
  - **0 = pagamento regolare**
  - **1 = default nel mese successivo**

Durante la fase di pulizia sono state rimosse le osservazioni con valori non validi nelle variabili **EDUCATION** e **MARRIAGE**, ottenendo un dataset finale di **29.601 osservazioni**.

---

# Struttura della repository

```
.
|── data/
│   └── Credit_Card_Default.csv 
│
├── notebooks/
│   └── notebook_gruppo_11_credit_card_default.ipynb
│
├── figures/
│
├── report/
│   ├── report.pdf
│   ├── relazione.tex
│   └── ...
│
└── README.md
```

---

# Librerie utilizzate

Il progetto è stato sviluppato in Python utilizzando principalmente:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

---

# Analisi svolte

Il notebook comprende:

## Analisi preliminare

- controllo tipologia variabili
- valori nulli
- valori fuori range
- pulizia del dataset
- riflessioni critiche

## Analisi esplorativa

- statistiche descrittive
- correlazioni
- distribuzioni
- confronto tra gruppi
- test statistici (χ²)
- Odds Ratio
- correlazione di Pearson
- visualizzazioni tramite heatmap, scatterplot, boxplot, pie chart e line plot

---

# Modelli di Machine Learning

Sono stati implementati e confrontati tre modelli di classificazione:

- Logistic Regression
- K-Nearest Neighbors (k = 5)
- Random Forest

Per ogni modello sono state calcolate:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

È stato inoltre effettuato un confronto finale tra i modelli e un'analisi della Feature Importance della Random Forest.

---

# Principali risultati

L'analisi ha evidenziato che:

- il dataset presenta un forte sbilanciamento della variabile target;
- lo storico dei ritardi nei pagamenti rappresenta il principale indicatore del rischio di insolvenza;
- le variabili demografiche hanno un impatto limitato;
- la **Random Forest** è risultata il modello con le migliori prestazioni complessive.

---

# Report

La cartella `report/` contiene:

- il report scientifico finale in formato PDF;
- tutti i sorgenti LaTeX utilizzati per la sua realizzazione.

---

# Repository GitHub

https://github.com/MattiaGalletti2001/progetto-data-science-gruppo-11-credit-card-default

---

# Utilizzo di strumenti di Intelligenza Artificiale

Durante lo sviluppo del progetto è stato utilizzato **ChatGPT (OpenAI) e Gemini (Google)** come supporto alla programmazione e alla revisione del testo.

L'utilizzo ha riguardato esclusivamente:

- chiarimenti concettuali;
- supporto nella scrittura di codice Python;
- revisione dei testi descrittivi;
- suggerimenti per la documentazione.

Tutto il codice inserito nel progetto è stato verificato, compreso e adattato dal gruppo, che è in grado di illustrarne il funzionamento durante la discussione orale, come richiesto dalle specifiche del corso.