# retail-sales-forecasting

https://github.com/MakremDJEBALI/retail-sales-forecasting

## Objectif du projet

Le projet vise à mettre en place un système de prévision des ventes quotidiennes pour les magasins Intermarché avec la détection d’anomalies. Plus précisément :

1. **Assurer la qualité des données**  
   - Vérifier l’intégrité temporelle (dates manquantes)  
   - Identifier et comprendre les outliers via méthodes statistiques (IQR) et apprentissage machine (Isolation Forest, Prophet)

2. **Développer et comparer plusieurs modèles de forecasting**  
   - Baselines linéaires (SARIMA, SARIMAX) pour capturer tendance et saisonnalité  
   - Approches non linéaires (RandomForest, Prophet, CatBoost) sur lags et variables métier  
   - Évaluation rigoureuse (MAE, MAPE) sur une période hors-échantillon (nov.–déc. 2023) et prévision pour janvier 2024

3. **Industrialiser la solution**  
   - Automatisation du pipeline (Airflow/Kedro) et conteneurisation (Docker/Kubernetes)  
   - Monitoring continu (MLflow, Grafana/Prometheus) et plan de ré-entraînement mensuel

4. **Répondre à la question métier**  
   - Protocole A/B (Difference-in-Differences, matching ou synthetic control) pour mesurer l’impact d’une innovation (bouteilles verre vs canettes alu)


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
