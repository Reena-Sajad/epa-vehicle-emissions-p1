# EPA Vehicle Emissions Regression - Part 1

This project explores regression techniques to predict vehicle emissions using data from the **EPA Fuel Economy Dataset**. The goal is to build and evaluate multiple regression models to estimate the **Greenhouse Gas (GHG) score**, a metric indicating the level of emissions a vehicle produces.

---

## 📌 Project Overview

- Focuses on **supervised regression** using EPA vehicle emissions data.
- Predicts the **GHG score** based on features like fuel economy, engine displacement, fuel type, and more.
- Evaluates the performance of several machine learning regression models.
- Includes data preprocessing, visualization, model training, and evaluation.

---

## 🗃️ Dataset

The dataset contains detailed information on vehicles sold in the United States, such as:

- `Fuel Type`, `Transmission`, `Drive`, `Cylinders`
- `Displacement`, `City MPG`, `Highway MPG`, `Air Pollution Score`
- `Greenhouse Gas Score` (Target variable)

> Data Source: [EPA Fuel Economy Dataset](https://www.fueleconomy.gov/)

---

## 🧰 Tools & Libraries Used

- Python 3
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 🧪 Regression Models Implemented

1. **Linear Regression**
2. **Lasso Regression**
3. **Ridge Regression**
4. **Support Vector Regression (SVR)**
5. **Random Forest Regressor**
6. **Gradient Boosting Regressor**
7. **K-Nearest Neighbors Regressor**

---

## 📊 Evaluation Metrics

The models are evaluated using:

- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **R² Score**

These metrics help assess how well each model predicts GHG emissions based on the available features.

---

## 📁 Repository Structure

```bash
epa-vehicle-emissions-p1/
├── epa-vehicle-emissions-p1.ipynb
└── README.md
