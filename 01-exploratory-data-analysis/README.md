# 📊 Progetto 1: Analisi Esplorativa Dataset E-commerce

## 🎯 Obiettivi del Progetto

Questo primo progetto ci introduce ai **fondamenti dell'analisi esplorativa** utilizzando un dataset di vendite e-commerce. Impareremo a:

- **Caricare e ispezionare** i dati con pandas
- **Pulire i dati** gestendo valori mancanti e duplicati
- **Calcolare statistiche descrittive** per ogni variabile
- **Creare visualizzazioni** per comprendere pattern e trend
- **Formulare insights** basati sui dati osservati

## 📋 Dataset Utilizzato

**Online Retail Dataset** - Transazioni di un negozio online UK
- **Fonte**: UCI Machine Learning Repository
- **Periodo**: Dicembre 2010 - Dicembre 2011
- **Variabili**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country
- **Dimensione**: ~540k transazioni

## 🛠 Tecnologie e Librerie

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import datetime as dt
```

## 📁 Struttura Files

```
01-exploratory-data-analysis/
│
├── README.md                    # Questo file
├── data/
│   └── online_retail.csv       # Dataset originale
├── notebooks/
│   └── eda_analysis.ipynb      # Notebook principale
├── src/
│   └── data_utils.py           # Funzioni di supporto
└── outputs/
    ├── plots/                  # Grafici generati
    └── summary_stats.csv       # Statistiche riassuntive
```

## 🔍 Fasi dell'Analisi

### 1. Data Loading & Inspection
- Caricamento dataset
- Controllo dimensioni e tipologie dati
- Prime 5 righe e informazioni generali

### 2. Data Cleaning
- Gestione valori nulli
- Rimozione duplicati
- Conversione tipi di dati appropriati

### 3. Exploratory Data Analysis
- Statistiche descrittive univariate
- Analisi distribuzione variabili numeriche
- Frequenze variabili categoriche
- Correlazioni tra variabili

### 4. Data Visualization
- Istogrammi e boxplot
- Grafici temporali vendite
- Top prodotti/clienti/paesi
- Heatmap correlazioni

### 5. Business Insights
- Trend stagionali
- Comportamento clienti
- Prodotti più performanti
- Opportunità di crescita

## 📈 Risultati Attesi

Al termine dell'analisi saremo in grado di rispondere a:
- Quale è il trend delle vendite nel tempo?
- Quali sono i prodotti più venduti?
- Come si comportano i clienti (frequenza acquisti, spesa media)?
- Ci sono pattern stagionali nelle vendite?

## 🚀 Come Eseguire

1. Clona la repository
2. Installa le dipendenze: `pip install -r requirements.txt`
3. Scarica il dataset nella cartella `data/`
4. Esegui il notebook `notebooks/eda_analysis.ipynb`

---

**📅 Data Creazione**: Settembre 2025  
**⏱ Tempo Stimato**: 4-6 ore  
**📊 Livello**: Principiante  