# 🌍 ESG & Profitability: Panel + ML Analysis

> 💡 Can responsible investing and profitability coexist?
> This project explores whether **High-ESG firms** sacrifice profitability using a blend of **econometrics** and **machine learning**.

---

## 📖 About the Project

This repo contains the full data science workflow from my MSc dissertation (2025).
We bring together:

⚖️ **Panel Econometrics** → causal insights on ESG vs. profit
🤖 **Machine Learning** → predictive models for firm ESG classification
📊 **Visualization & EDA** → uncover patterns in 400 firm-year observations

---

## 🛠️ Tech Stack

* Python 3.9+
* Jupyter Notebook
* Libraries:

  * `pandas` • `numpy` • `matplotlib` • `seaborn`
  * `scikit-learn` • `statsmodels`

---

## 📂 Repository Structure

```
├── Dissertation Code Final.ipynb   # 📓 Report
├── data/                           # 📁 Raw data (excluded for confidentiality)
├── README.md                       # 📜 You are here!
```

---

## 🔍 Methodology

### 📌 Panel Econometrics

* **Objective:** Estimate the impact of ESG on profitability.
* **Dependent Variable:** Profit Margin.
* **Key Predictor:** ESG Score (1–7 scale, also High/Low binary).
* **Controls:** Log revenue, lagged profit margin.
* **Approach:** Both **Fixed Effects** and **Random Effects** models are estimated. The **Hausman test** is used to guide model selection and robustness.

### 🤖 Machine Learning

* **Objective:** Predict whether a firm is High-ESG or Low-ESG based on financial and industry features.
* **Models Used:**

  * Logistic Regression
  * Random Forest 🌲
  * Gradient Boosting ⚡
  * Support Vector Machine (SVM) 🔺
  * K-Nearest Neighbors (KNN) 👥
* **Features:** Market cap, industry dummies, lagged profitability, financial indicators.

### 📊 Model Evaluation

* Accuracy
* Precision / Recall
* F1-Score
* Cross-Validation (to ensure generalizability)
* Feature importance analysis (for ML models)

---

## ⚡ Getting Started

### 🔧 Installation

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
pip install -r requirements.txt
```

### ▶️ Run the Notebook

```bash
jupyter notebook "Dissertation Code Final.ipynb"
```

---

## 🎯 Key Insights

* **Econometrics** → ESG doesn’t always imply profit trade-offs
* **ML Models** → highlight predictive signals in firm characteristics
* **Combined Approach** → inference + prediction = richer insights

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Fork the repo, open a PR, or drop an issue 🚀.

