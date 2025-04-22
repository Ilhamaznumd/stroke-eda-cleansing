## 🧠 Stroke Data Analysis (EDA & Cleaning)

This project performs **Exploratory Data Analysis (EDA)** and **data cleaning** on a healthcare dataset related to stroke prediction. The dataset includes a variety of demographic and health-related attributes to understand patterns and potential risk factors for strokes.

### 📁 Dataset

The dataset contains the following columns:

- `gender`
- `age`
- `hypertension`
- `heart_disease`
- `ever_married`
- `work_type`
- `Residence_type`
- `avg_glucose_level`
- `bmi`
- `smoking_status`
- `stroke` (target)

Source: [Kaggle - Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

---

### 🔍 EDA Summary

- **Univariate Analysis**: Visualizations include bar plots, pie charts, and histograms to understand distributions of categorical and numerical variables.
- **Bivariate Analysis**: Relationships between features and the target (`stroke`) are explored to identify trends and disparities.
- **Correlations**: A heatmap visualizes the correlation between numeric features.

---

### 🧹 Data Cleaning

- Handled **missing values** in the `bmi` column by using median imputation.
- Ensured **data types** are appropriate for analysis.
- Standardized categorical variables if necessary.
- Removed any potential data leakage or anomalies.

---

### 📊 Visualizations

Some visualizations include:

- Age, glucose level, and BMI distributions.
- Stroke distribution across gender, smoking status, work type, etc.
- Correlation heatmap & scatter plots for pattern discovery.

---

### 🛠 Tools Used

- Python
- Pandas
- Matplotlib & Seaborn
- Jupyter Notebook

---
