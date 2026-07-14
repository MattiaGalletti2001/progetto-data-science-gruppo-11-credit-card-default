## Gruppo 11 - Previsione dell'Insolvenza Creditizia (Credit Card Default Prediction)

Progetto realizzato per il corso **Introduzione alla Data Science e al Pensiero Computazionale**  
Anno Accademico **2025/2026**

---

# Repository GitHub

https://github.com/MattiaGalletti2001/progetto-data-science-gruppo-11-credit-card-default

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

---

# Struttura della repository

.
|── data/
│   └── Credit_Card_Default.csv 
│
├── notebooks/
│   └── notebook_gruppo_11_credit_card_default.ipynb
│
├── report/
│   ├── Previsione_dell_Insolvenza_Creditizia__Analisi_e_Modellazione.pdf
│   ├── main.tex
│   ├── bibliografia.bib
│   └── images/
|       ├── logo_unibo.jpg
│       ├── fig1_limit_bal_boxplot.png
│       ├── fig2_pay0_default_prob.png
|       ├── fig3_correlation_matrix.png
│       ├── fig4_feature_importance.png
│       ├── fig_confusion_logistic.png
|       ├── fig_confusion_knn.png
│       └── fig_confusion_rf.png
│       
└── README.md

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
- K-Nearest Neighbors
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

# Tecnologie e strumenti utilizzati

Per lo sviluppo del progetto sono stati utilizzati:

- **Python**, eseguito tramite **Google Colab**, per l’analisi dei dati, la visualizzazione e la costruzione dei modelli di Machine Learning;
- **GitHub**, per il versionamento del codice, il lavoro collaborativo e l’organizzazione della repository;
- **LaTeX tramite Overleaf**, per la redazione del report scientifico finale.

Durante lo sviluppo del progetto sono stati utilizzati **ChatGPT (OpenAI) e Gemini (Google)** come supporto alla programmazione e alla revisione del testo.