# 🔥 Fire Weather Index (FWI) Prediction using Algerian Forest Fire Dataset

This repository presents a machine learning solution for predicting the Fire Weather Index (FWI), a crucial indicator used to assess wildfire risk. Leveraging the Algerian Forest Fire Dataset, this project applies various regression techniques — including Linear Regression, Ridge, and Lasso — to model the relationship between meteorological variables and fire risk. Cross-validation is used to ensure robust model evaluation and comparison.

---

## 📌 Project Overview

- **Objective**: Build and evaluate regression models to accurately predict the Fire Weather Index (FWI) using environmental and weather-based features.
- **Use Case**: Aids wildfire risk assessment and supports the development of early warning systems for forest fire prevention and management.

---

## 📊 Dataset Summary

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset+)
- **Description**: The dataset contains meteorological data collected from two Algerian regions — Bejaia and Sidi-Bel Abbes — along with computed fire danger indices.
- **Features**:
  - `Temperature`, `RH` (Relative Humidity), `Wind`, `Rain`
  - Derived FWI components: `FFMC`, `DMC`, `DC`, `ISI`, and `FWI`
- **Target Variable**: `FWI` (Fire Weather Index)

---

## ⚙️ Models Used

The following regression models were implemented and evaluated:

- **Linear Regression**
- **Ridge Regression** (L2 Regularization)
- **Lasso Regression** (L1 Regularization)

Each model was trained and validated using **k-fold cross-validation** to assess its generalization performance.

---

## 🚀 Running the Project

### 🔧 Prerequisites

Ensure Python 3.7 or higher is installed. Then install dependencies using:

```bash
pip install -r requirements.txt
