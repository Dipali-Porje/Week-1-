# 🌬️ Wind Power Generation Forecasting

This project focuses on forecasting wind power generation using historical weather and energy production data from multiple locations. It involves data preprocessing, exploratory data analysis (EDA), and predictive modeling using machine learning techniques.

---

## 📁 Project Structure

📦 wind-power-forecasting/ ├── Location1.csv ├── Location2.csv ├── Location3.csv ├── Location4.csv ├── merge_locations.csv ├── wind power generation forecasting.ipynb └── README.md

---

## 📌 Objectives

- Merge wind power datasets from multiple locations.
- Perform exploratory data analysis (EDA) to understand patterns.
- Preprocess and prepare data for machine learning.
- Train and evaluate models to forecast power generation.

---

## 🧪 Technologies & Libraries Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📊 Dataset Description

- **Location1.csv** to **Location4.csv**: Datasets containing weather features and power generation values from different locations.
- Merged into one unified dataset: `merge_locations.csv`.
- link - https://www.kaggle.com/datasets/mubashirrahim/wind-power-generation-data-forecasting?select=Location2.csv
  

---

## 🧹 Steps Performed

### 1. Data Loading
- Loaded 4 CSV files with data from different geographical locations.

### 2. Merging
- Added a `Location` column to each dataset.
- Merged all into a single DataFrame for consolidated analysis.

### 3. Exploratory Data Analysis (EDA)
- Initial EDA to understand trends and distributions.
- Focus on variables affecting power generation.

### 4. Preprocessing
- Handled missing values (if any).
- Scaled data using `StandardScaler`.
- Prepared features and target for modeling.

### 5. Modeling (Planned in Week 3)
- Train-Test split using `train_test_split`.
- Model training and evaluation (to be completed).

---

## 🚀 Future Work

- Implement and compare ML models (e.g., Linear Regression, Random Forest, etc.)
- Evaluate performance using metrics like RMSE, MAE, R².
- Deploy the model using a web app (e.g., Flask/Streamlit).



---


