# Global Salary Analysis Project

Questo progetto si concentra sull'analisi di un dataset globale dei salari, con l'obiettivo di esplorare la distribuzione dei salari medi, minimi e massimi in vari paesi e continenti. L'analisi cerca di individuare pattern significativi, identificando i paesi con le maggiori e minori disparità salariali, oltre ai paesi con i salari medi e mediani più alti.

## Dataset

Il dataset utilizzato in questo progetto è 'salary_data.csv'. Il dataset include informazioni sui salari medi, minimi e massimi di diversi paesi, suddivisi per continente.

## Obiettivi del progetto

L'obiettivo principale di questo progetto è identificare:
- I paesi con i salari medi e mediani più alti e più bassi.
- I paesi con la maggiore e minore disparità tra il salario minimo e massimo.
- La distribuzione dei salari nei diversi continenti.

## Notebook

### `salary_analysis.ipynb`

Questo notebook (realizzato con jupyter) gestisce l'importazione e l'analisi del dataset sui salari globali. Utilizza le librerie **pandas**, **numpy** e **matplotlib** per eseguire le seguenti attività:

1. **Preprocessing e caricamento dei dati**: 
   - Il dataset viene caricato in un dataframe pandas per l'analisi.

2. **Analisi esplorativa dei dati**:
   - Vengono calcolati i paesi con i salari medi e mediani più alti e più bassi.
   - Viene calcolata la disparità salariale tra il salario minimo e massimo per ciascun paese.

3. **Visualizzazione dei dati**:
   - Viene creato un istogramma che mostra la distribuzione dei salari medi nei diversi paesi, con le informazioni ordinate in base ai salari più alti.

## Funzionalità dello script

- **Identificazione dei paesi con i salari medi più alti e più bassi**:
   Lo script ordina i paesi in base al salario medio e seleziona i primi e ultimi 5 paesi.
   
- **Calcolo della disparità salariale**:
   Lo script calcola la disparità salariale (differenza tra salario massimo e minimo) e identifica i 5 paesi con la maggiore e minore disparità.

- **Visualizzazione**:
   Viene generato un grafico a barre che mostra i salari medi per paese, fornendo una chiara rappresentazione visiva delle differenze salariali globali.

## Dataset utilizzato

- Il dataset utilizzato è reperibile su Kaggle: [Global Salary Data](https://www.kaggle.com/datasets/zedataweaver/global-salary-data).

## Come usare lo script

1. Clona il repository e apri il notebook salary_analysis.ipynb in Jupyter Notebook.
2. Esegui le celle del notebook.
