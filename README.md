# retail-sales-forecasting

https://github.com/MakremDJEBALI/retail-sales-forecasting

## Objectif du projet

Développer un système de détection des anomalies et de prévision des ventes quotidiennes pour les magasins Intermarché, en s’appuyant sur 10 ans de données transactionnelles (niveau ticket-ligne). L’objectif est de fournir :

- Un diagnostic précis de la qualité des données et des points aberrants  
- Une comparaison de plusieurs modèles de forecasting  
- Des recommandations pour le déploiement en production  

## Structure du projet

```
retail-sales-forecasting/
├── data/
│   └── dataset_case.csv
├── notebooks/
│   └── RetailAnalytics.ipynb
├── requirements.txt
└── .gitignore
```

## Installation

```bash
git clone https://github.com/MakremDJEBALI/retail-sales-forecasting.git
cd retail-sales-forecasting
python3 -m venv .venv
source .venv/bin/activate   # sur Linux/Mac
.venv\Scripts\activate    # sur Windows
pip install -r requirements.txt
```

## Exécution

```bash
jupyter lab
```

Ouvrez ensuite le notebook `notebooks/RetailAnalytics.ipynb` pour exécuter toutes les étapes.

## Contenu

1. Data Ingestion & Preprocessing  
2. Exploratory Data Analysis & Anomaly Detection  
3. Time Series Forecasting Models (SARIMA, SARIMAX, RandomForest, Prophet, CatBoost)  
4. Industrialization & Deployment Plan  
5. Risk Assessment & Customer Recommendations  

---

**Contact**  
Makrem DJEBALI – [GitHub](https://github.com/MakremDJEBALI)
