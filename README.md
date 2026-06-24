# AIDS Clinical Trials Group Study 175 

Progetto per il corso di Intelligenza Artificiale 2 
Autori: Martina Flores d'Arcais, Lucio Valerio Mariani

Il progetto analizza il dataset ACTG 175 con l'obiettivo di predire l'esito clinico dei pazienti (`cid`: 1 = decesso/failure, 0 = censurato) tramite modelli di classificazione binaria. Sono stati implementati e confrontati quattro classificatori: Logistic Regression, Linear Discriminant Analysis, Gaussian Naive Bayes e MLP, valutati con cross-validation stratificata a 5 fold e metriche adatte a dati sbilanciati (AUC-ROC, F1-score).

# Dataset
- Fonte:UCI Machine Learning Repository — https://archive.ics.uci.edu/dataset/890/aids+clinical+trials+group+study+175
- Istanze: 2139, Feature: 23, Target:`cid` (binario)
Il dataset viene scaricato automaticamente tramite `ucimlrepo`

# Struttura del repository
```
IA2_AIDS/
├── aids_clinicaltrials.ipynb
└── README.md
```
# Librerie
```bash
pip install pandas numpy matplotlib seaborn scikit-learn ucimlrepo
```
# Riproduzione risultati

1. Clonare il repository:
```bash
   git clone https://github.com/<username>/IA2_AIDS.git
```
2. Aprire `aids_clinicaltrials.ipynb` in Jupyter Notebook o Google Colab.
3. Eseguire le celle in ordine dall'inizio alla fine.
