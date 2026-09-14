# data.org Financial Health Prediction Challenge

This repository contains our solution for the **[data.org Financial Health Prediction Challenge](https://zindi.world/competitions/dataorg-financial-health-prediction-challenge)** hosted on Zindi.

---

##  Project Overview

Micro, small, and medium enterprises (MSMEs) form the backbone of many economies across Africa. However, assessing their financial health is often challenging due to limited formal credit histories and varying economic environments.

The objective of this challenge is to build machine learning classification models to predict the **financial health status** (`Low`, `Medium`, `High`) of business owners across multiple African nations (including Eswatini, Malawi, Zimbabwe, and others) using demographic details, business attributes, attitudes, and financial behaviors.

---

##  Competition Details

* **Platform:** Zindi
* **Organizer:** data.org
* **Task Type:** Multi-Class Classification
* **Target Categories:** `Low`, `Medium`, `High` Financial Health
* **Evaluation Metric:** Multi-class classification performance (e.g., Macro F1-score / Log Loss)
* **Challenge Link:** [data.org Financial Health Prediction Challenge on Zindi](https://zindi.world/competitions/dataorg-financial-health-prediction-challenge)

---

## Dataset Overview

The dataset gathers survey information from small business owners, covering several dimensions:

* **Demographics:** Country of operation, owner age, owner gender.
* **Business Profile:** Business age (years and months), turnover, business expenses, and personal income.
* **Financial Access & Services:** Usage of mobile money, bank accounts, debit/credit cards, informal lenders, and insurance products (medical, funeral, motor vehicle).
* **Perceptions & Attitudes:** Views on insurance affordability, business stability, profit motivation, COVID-19 impact, and outlook for the future.

---

##  Methodology & Workflow

1. **Exploratory Data Analysis (EDA):** Analyzed class distributions, identified missing value patterns, and investigated differences across countries and business maturity levels.
2. **Data Preprocessing & Imputation:** Handled missing survey responses, managed categorical variables, and normalized numerical features like income and expenses.
3. **Feature Engineering:** Extracted financial ratios, indicators of formal vs. informal service adoption, and risk attitude scores.
4. **Model Exploration & Validation:** Evaluated multiple machine learning algorithms including tree-based gradient boosters (LightGBM, XGBoost, Random Forest) and linear models using stratified cross-validation.
5. **Hyperparameter Tuning & Ensembling:** Tuned decision thresholds and blended model predictions to optimize final classification metrics.
6. **Submission Generation:** Produced formatted predictions for the test dataset for evaluation against the competition leaderboard.

---

## Impact

Accurate prediction of MSME financial health empowers microfinance institutions, policy makers, and development organizations to design tailored financial products, provide timely interventions, and support the sustainable growth of small businesses.
