# ❤️ Heart Disease Data Analysis

## 📌 Overview

This project analyzes a clinical dataset to identify key factors associated with heart disease using exploratory data analysis (EDA) and visualization techniques. The goal is to uncover meaningful patterns that can support data-driven decision-making in healthcare.

---

## 📊 Dataset

The dataset contains patient-level clinical information, including:

* Age
* Sex
* Chest pain type (cp)
* Resting blood pressure (trestbps)
* Cholesterol (chol)
* Maximum heart rate achieved (thalach)
* Exercise-induced angina (exang)
* ST depression (oldpeak)
* Target variable (0 = no disease, 1 = disease)

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Analysis Workflow

1. Data loading and inspection
2. Data cleaning (handling duplicates and structure validation)
3. Exploratory Data Analysis (EDA)
4. Visualization of feature distributions
5. Correlation analysis
6. Feature-wise comparison with heart disease presence

---

## 📈 Key Insights

### 1. Age Distribution

The majority of patients fall within the 50–60 age group, indicating that middle-aged individuals form a significant portion of the dataset.

### 2. Cholesterol Levels

Cholesterol levels show similar distributions across both groups, suggesting it may not be a strong standalone predictor of heart disease.

### 3. Heart Rate (thalach)

Patients with heart disease tend to have higher maximum heart rates, indicating a possible relationship between cardiovascular stress response and disease presence.

### 4. Chest Pain Type (cp)

Chest pain type shows a strong association with heart disease, with certain categories exhibiting a higher prevalence of affected individuals.

### 5. Exercise-Induced Angina (exang)

Absence of exercise-induced angina appears more common in patients diagnosed with heart disease in this dataset.

### 6. Correlation Analysis

Key features such as chest pain type, maximum heart rate, and ST depression (oldpeak) show notable relationships with heart disease, while cholesterol and resting blood pressure demonstrate weak correlations.

---

## 📊 Visualizations

### 🔹 Correlation Heatmap

![Correlation Heatmap](images/heatmap.png)

### 🔹 Age Distribution

![Age Distribution](images/age_distribution.png)

### 🔹 Cholesterol vs Heart Disease

![Cholesterol](images/cholesterol_vs_target.png)

### 🔹 Chest Pain Type vs Heart Disease

![Chest Pain](images/cp_vs_target.png)

### 🔹 Max Heart Rate vs Heart Disease

![Thalach](images/thalach_vs_target.png)

### 🔹 Exercise-Induced Angina vs Heart Disease

![Exang](images/exang_vs_target.png)

---

## ⚠️ Limitations

* Dataset size is relatively small
* Results are based on a specific dataset and may not generalize
* No causal inference—only correlation-based insights

---

## 🚀 Conclusion

This analysis highlights important clinical features associated with heart disease and demonstrates how exploratory data analysis can be used to extract meaningful insights from healthcare datasets.

---

## 📌 Future Work

* Apply machine learning models for prediction
* Feature selection and model optimization
* Validation using larger clinical datasets
