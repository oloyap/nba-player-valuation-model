# nba-player-valuation-model

**NBA Player Valuation Model** – An end-to-end machine learning project that predicts NBA player salaries, identifies undervalued and overvalued contracts, and delivers front-office style insights using XGBoost, clustering, and surplus value analysis.

---

## 📌 Overview

This project builds a data-driven valuation framework to replicate how NBA front offices assess player value relative to contract cost. Using historical player performance and salary data (2010–2025), the model predicts expected salary, measures surplus value, and highlights market inefficiencies.

The goal is to support smarter decisions in **free agency, contract negotiations, and roster construction** through advanced analytics.

---

## 🎯 Objectives

- Predict NBA player salaries using machine learning  
- Identify **undervalued and overvalued contracts**  
- Segment players into role-based archetypes using clustering  
- Quantify **surplus value** to support salary cap optimization  

---

## 🧠 Methodology

### 1. Data Cleaning & Feature Engineering
- Standardized multi-season player statistics  
- Created lag features and rolling averages  
- Adjusted salaries relative to league salary cap growth  
- Engineered efficiency, usage, and impact metrics  

### 2. Salary Prediction (Supervised Learning)
- Trained **XGBoost regression models**  
- Evaluated using **MAE, RMSE, and R²**  
- Applied **Optuna hyperparameter optimization** for tuning  

### 3. Player Archetype Clustering
- Used unsupervised learning (e.g., K-Means) to group players by role  
- Identified clusters such as:
  - High-usage scorers  
  - Defensive specialists  
  - High-efficiency role players  
  - Bench contributors  

### 4. Surplus Value Analysis
- Calculated difference between **predicted salary and actual contract value**  
- Flagged:
  - **Undervalued players** → trade / free agency targets  
  - **Overvalued players** → contract risk indicators  

---

## 📊 Key Outputs

- Optimized salary prediction model  
- Player archetype clusters with interpretation  
- Surplus value rankings  
- Front-office style recommendations for:
  - Free agency targeting  
  - Contract negotiations  
  - Roster optimization  

---

## 💼 Business Impact

This project demonstrates how analytics can be used to:

- Improve **salary cap efficiency**  
- Avoid overpaying high-variance or declining players  
- Identify **high-impact, low-cost contributors**  
- Support data-driven decision making in professional sports  

---

## 🛠 Tech Stack

- Python  
- pandas, NumPy  
- scikit-learn  
- XGBoost  
- Optuna  
- matplotlib / seaborn  
- Jupyter Notebook  

---

## 👤 Author

**Peter Oloya**  
Master of Management Analytics (MMA) – University of Alberta  
Analytics Consultant | Data Scientist | Data Technician, ACO Services  

---

## 📜 Disclaimer

This project is for educational and portfolio purposes. All data used is publicly available.

