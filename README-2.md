# 🤖 ML Challenge — Predicting Investment Allocation Performance

**Author:** Nour Salhi  
**Event:** ENS Finance Challenge  
**Notebook:** `ENS_Finance_Challenge_FINAL_(2).ipynb`

---

## 📌 Overview

This project is a submission for the **ENS Finance Challenge**, a competitive machine learning challenge focused on predicting the future performance of investment portfolio allocations. The goal is to leverage financial data and ML techniques to forecast how different asset allocations will perform, a problem at the intersection of quantitative finance and data science.

---

## 🎯 Objective

Given a set of investment allocations across multiple asset classes, the model aims to predict their **future performance** (e.g., return, Sharpe ratio, or a composite score). This type of problem is highly relevant in the asset management industry for portfolio optimization and risk-adjusted decision-making.

---

## 📁 Repository Structure

| File | Description |
|---|---|
| `ENS_Finance_Challenge_FINAL_(2).ipynb` | Main notebook: full pipeline from data loading to model training, evaluation, and predictions |
| `README.md` | Project documentation |

---

## 🔬 Methodology

The notebook covers a complete machine learning pipeline:

### 1. 📥 Data Loading & Exploration
- Loading the challenge dataset
- Exploratory Data Analysis (EDA): distributions, correlations, missing values
- Understanding the structure of investment allocations and target variables

### 2. 🧹 Data Preprocessing
- Feature engineering on financial variables
- Handling missing values and outliers
- Normalization / standardization of inputs
- Train/test split

### 3. 🧠 Model Training
Multiple ML models are trained and compared, potentially including:
- **Linear / Ridge / Lasso Regression** — baseline models
- **Random Forest / Gradient Boosting** — tree-based ensembles
- **XGBoost / LightGBM** — high-performance boosting
- **Neural Networks** — deep learning approaches

### 4. 📊 Evaluation & Model Selection
- Cross-validation and hyperparameter tuning
- Performance metrics (e.g., RMSE, R², ranking metrics)
- Feature importance analysis

### 5. 📈 Predictions & Submission
- Final predictions on the test set
- Output formatted for challenge submission

---

## 🛠️ Technologies Used

- **Python** — core language
- **Jupyter Notebook** — interactive development
- **pandas / numpy** — data manipulation
- **scikit-learn** — ML models and preprocessing
- **XGBoost / LightGBM** — gradient boosting
- **matplotlib / seaborn** — visualization

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/nou874/Machine-Learning-Challenge-on-predicting-the-performance-of-investment-allocations.git
   cd Machine-Learning-Challenge-on-predicting-the-performance-of-investment-allocations
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn xgboost lightgbm matplotlib seaborn jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook "ENS_Finance_Challenge_FINAL_(2).ipynb"
   ```

---

## 🏆 Context

This challenge was organized as part of the **ENS Finance Challenge**, a quantitative finance competition that brings together students and researchers to tackle real-world financial prediction problems using machine learning.

---

## 📬 Contact

GitHub: [@nou874](https://github.com/nou874)
