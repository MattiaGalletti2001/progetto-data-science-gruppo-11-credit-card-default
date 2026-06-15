# Progetto Data Science - Gruppo 11

# Titolo del progetto

Credit Card Default Prediction

# Descrizione del progetto

Questo progetto è stato realizzato per il corso di Introduzione al Pensiero Computazionale e alla Data Science.

L’obiettivo è analizzare un dataset relativo a clienti di carte di credito e costruire modelli di classificazione per prevedere se un cliente andrà in default nel pagamento del mese successivo.

Il progetto integra:
- analisi esplorativa dei dati;
- visualizzazione dei dati;
- machine learning;
- valutazione dei modelli;
- interpretazione critica dei risultati;
- documentazione tramite GitHub e LaTeX.

# Dataset

Il dataset scelto è Credit_Card_Default.

Ogni riga rappresenta un cliente titolare di carta di credito. Le variabili descrivono caratteristiche demografiche, limite di credito, storico dei pagamenti, importi delle bollette e pagamenti precedenti.

La variabile target indica se il cliente è andato in default nel mese successivo:

- 1 = default payment;
- 0 = no default payment.

# Obiettivo

L’obiettivo è prevedere il default del pagamento della carta di credito nel mese successivo.

Si tratta quindi di un problema di classificazione binaria.

# Struttura della repository

```text
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── figures/
├── report/
├── README.md
└── requirements.txt
