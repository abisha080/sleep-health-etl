# 💤 Automated ETL Pipeline for Sleep Health & Lifestyle Data

## 🎯 Objective
Build an automated ETL (Extract, Transform, Load) pipeline to preprocess, transform,
and load sleep health and lifestyle data for analyzing sleep disorders.

---

## 📊 Dataset Description
The dataset contains demographic, lifestyle, and health-related features including:
- Sleep Duration
- Quality of Sleep
- Stress Level
- Physical Activity Level
- Blood Pressure
- Age
- Sleep Disorder (Target Variable)

---

## ⚙️ ETL Pipeline Workflow

### 🔹 Extract
- Loaded raw sleep health data from CSV using Pandas
- Removed non-informative identifier columns

### 🔹 Transform
- Handled missing values
- Performed feature engineering (Blood Pressure split)
- Outlier detection and treatment using IQR and Z-score
- Multicollinearity check using Variance Inflation Factor (VIF)
- Scaled numerical features
- Encoded categorical features
- Built automated preprocessing pipelines using Scikit-learn

### 🔹 Load
- Saved processed train and test datasets
- Stored reusable preprocessing pipeline using Joblib

---

## 📈 Exploratory Data Analysis (EDA)
- Target class distribution visualization
- Numerical feature distributions
- Categorical feature frequency plots
- Boxplots for outlier analysis
- Correlation heatmap
- Pairplots for multivariate relationships

---

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- SciPy
- Statsmodels
- Joblib

## ✅ Final Output
- ML-ready processed datasets
- Reusable ETL preprocessing pipeline
- Scalable and production-ready data workflow

---

## 👤 Author
**Abisha.C**


