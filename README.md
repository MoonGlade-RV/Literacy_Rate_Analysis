# 📊 Literacy Rate Analysis in India

This project performs an in-depth Exploratory Data Analysis (EDA) and regression modeling on literacy rate data in India using a dataset from the Ministry of Finance. The goal is to explore patterns, clean missing values, visualize data, and use machine learning models to understand the impact of various features on literacy rates.

---

## 📁 Dataset Source

> **Note**: The dataset used in this notebook does **not** belong to me. It is sourced from the **Ministry of Finance**, Government of India.

---

## 🧰 Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`, `plotly`
- `missingno`
- `scikit-learn`

---

## 📌 Workflow Summary

### 1. Importing Libraries
All necessary data manipulation, visualization, and machine learning libraries are imported.

### 2. Data Collection
The dataset `Literacy_Rate-Ministry_of_Finance_1.csv` is loaded and previewed.

### 3. Data Understanding
- Checked dataset structure using `.info()` and `.describe()`
- Identified missing values using `missingno` and performed imputation with `SimpleImputer`
- Encoded categorical variables using `LabelEncoder`
- Standardized features with `StandardScaler`

### 4. Exploratory Data Analysis
- Performed univariate and bivariate analysis
- Visualized trends using bar plots, line plots, and heatmaps
- Used `plotly` for interactive insights

### 5. Regression Modeling
- Linear Regression and Polynomial Regression
- Used `train_test_split` to train/test models
- Evaluated performance using `r2_score` and `mean_squared_error`
- Optimized models using `GridSearchCV`

---

## 📈 Results
- Polynomial regression provided better fit in certain cases over linear regression.
- Key factors influencing literacy rate were identified based on model coefficients and feature importance.

---

## ✅ How to Run

1. Install required packages (listed above)
2. Open the Jupyter Notebook file: `Literacy_Rate.ipynb`
3. Run all cells step-by-step

---

## 🧠 Future Improvements

- Try more advanced models like Random Forest or XGBoost
- Deploy the model using Streamlit or Flask
- Add regional or gender-based literacy trends

---

## 📝 License and Credits

This notebook is intended for educational purposes. The data belongs to its **rightful owner**, the **Ministry of Finance, Government of India**.
