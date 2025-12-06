# BinanceCoinAnomalyPredictionWithPython

Project Title: Crypto Market Anomaly Detection & Regime Clustering

1. Project Overview

This project builds a complete unsupervised machine learning pipeline for detecting anomalies and identifying market regimes in cryptocurrency OHLCV data (Open, High, Low, Close, Volume).

Using engineered financial features and clustering algorithms, the model identifies:
	•	🔍 Abnormal market behavior (manipulation, liquidity spikes, flash crashes)
	•	📊 Three distinct market regimes (calm, high-volatility, bullish momentum)

The project is directly applicable to real-world crypto exchanges such as Local Token Exchange, improving market monitoring, risk detection, and strategic decision-making.

⸻

2. Main Objectives
	•	Build a data cleaning + ETL pipeline
	•	Perform exploratory data analysis (histograms, boxplots, scatter plots, heatmap)
	•	Engineer financial features:
	•	daily returns
	•	volatility (20-day)
	•	intraday range
	•	volume change
	•	Detect anomalies using Isolation Forest
	•	Identify regimes using K-Means Clustering
	•	Interpret clusters for business value
	•	Visualize regimes on price charts & PCA projection

⸻

3. Technologies Used

Category	Tools
Programming	Python 3.10+
Data	Pandas, NumPy
ML Models	scikit-learn
Visualization	Matplotlib, Seaborn
Finance	OHLCV data (Crypto)
Deployment	Jupyter Notebook / Python Script
Version Control	Git / GitHub


⸻

4. Skills Developed

During this project, I developed strong practical skills in:

📌 Data Engineering (ETL)
	•	Detecting and removing missing values
	•	Handling duplicates
	•	Treating infinities
	•	Scaling data
	•	Cleaning and aligning time series

📌 Exploratory Data Analysis
	•	Understanding distributions
	•	Identifying volatility clusters
	•	Detecting outliers visually
	•	Correlation analysis with heatmaps

📌 Feature Engineering
	•	Financial returns
	•	Volatility estimation
	•	Price dynamics (High–Low range)
	•	Volume analysis

📌 Machine Learning (Unsupervised)
	•	Isolation Forest for anomaly detection
	•	K-Means for clustering and regime detection
	•	PCA for dimensionality reduction

📌 Business Interpretation
	•	Linking ML results to actionable insights
	•	Understanding market manipulation signals
	•	Identifying bullish, bearish, and high-risk regimes

📌 Professional Presentation
	•	Clear documentation
	•	Clean code for GitHub
	•	Graphical interpretation
	•	Market analytics storytelling

⸻

5. What I Learned

This project taught me:
	•	How financial time-series differ from normal datasets
	•	How to engineer domain-specific features in crypto/finance
	•	The importance of volatility, returns, and price ranges
	•	How to detect risk signals using ML instead of rules
	•	How market regimes help exchanges understand liquidity & volatility
	•	How to build a full end-to-end ML pipeline used in real exchanges

⸻

6. Project Structure

crypto-market-analysis/
│
├── data/
│   └── btc.csv
│
├── notebooks/
│   └── Crypto_Analysis.ipynb
│
├── src/
│   ├── etl.py
│   ├── eda.py
│   ├── feature_engineering.py
│   ├── anomaly_detection.py
│   ├── clustering.py
│   └── visualization.py
│
├── results/
│   ├── anomalies_clusters.csv
│   └── charts/
│
└── README.md


⸻

7. Business Value (for Local Token Exchange)

a) Anomaly Detection

The model flags unusual market movements such as:
	•	manipulations
	•	liquidity shocks
	•	flash crashes
	•	extraordinary volatility

👉 Helps the exchange protect users, monitor market integrity, and support regulatory compliance.

b) Regime Clustering

Identifies:
	•	stable markets
	•	high-volatility stress periods
	•	bullish momentum phases

👉 Useful for:
	•	dynamic fee adjustment
	•	liquidity management
	•	internal risk dashboards
	•	institutional investor reporting
  

🇫🇷 📌 Titre du Projet : Détection d’Anomalies & Régimes de Marché Crypto

1. Aperçu du Projet

Ce projet construit un pipeline complet de machine learning non supervisé pour :
	•	détecter les anomalies de marché
	•	identifier les régimes de marché

à partir de données OHLCV (Open, High, Low, Close, Volume).

Il permet de distinguer :
	•	🔍 les comportements anormaux du marché
	•	📊 trois régimes : calme, très volatil, momentum haussier

Ce type d’analyse est utilisé par des exchanges crypto comme Local Token Exchange.

⸻

2. Objectifs
	•	Pipeline ETL complet
	•	Analyse exploratoire détaillée
	•	Feature engineering financier
	•	Détection d’anomalies (Isolation Forest)
	•	Clustering de régimes (K-Means)
	•	Visualisation et interprétation métier

⸻

3. Technologies Utilisées
	•	Python
	•	Pandas, NumPy
	•	Scikit-learn
	•	Matplotlib, Seaborn
	•	Jupyter Notebook
	•	Git / GitHub

⸻

4. Compétences Développées
	•	Nettoyage et préparation de données
	•	Analyse statistique et visuelle
	•	Feature engineering financier
	•	Machine learning non supervisé
	•	Détection d’anomalies
	•	Clustering
	•	Réduction de dimension PCA
	•	Interprétation business
	•	Documentation professionnelle

⸻

5. Ce Que J’ai Appris
	•	Manipuler des séries temporelles financières
	•	Construire des features utilisés en finance
	•	Détecter automatiquement les risques de marché
	•	Identifier les cycles et régimes de volatilité
	•	Transformer un modèle ML en outil utile pour un exchange

⸻

6. Structure du Projet

(identique à la section anglaise)

⸻

7. Valeur Métier pour Local Token Exchange

a) Détection d’Anomalies

Permet de repérer :
	•	manipulations
	•	pics de volatilité
	•	chutes soudaines
	•	irrégularités de volume

👉 Améliore la sécurité et la surveillance du marché.

b) Détection des Régimes

Permet de comprendre :
	•	les périodes calmes
	•	les phases de stress
	•	les phases haussières

👉 Utile pour :
	•	ajustement des frais
	•	gestion de liquidité
	•	suivi des risques internes
