# Heart Disease Dataset Analysis
# Project Overview
This project provides an analytical exploration of a heart disease dataset using Power BI and SQL. It aims to uncover patterns and predictors associated with heart disease through data visualizations and statistical queries.

---

# Dataset

The dataset (`heart_disease_prediction_data.csv`) is a cleaned version of a publicly available heart disease dataset. It includes clinical features related to cardiovascular health.

# *Features*

- `age`: Age of the patient  
- `sex`: Sex (1 = male, 0 = female)  
- `cp`: Chest pain type (0–3)  
- `trestbps`: Resting blood pressure (mm Hg)  
- `chol`: Serum cholesterol (mg/dl)  
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)  
- `restecg`: Resting electrocardiographic results  
- `thalachh`: Maximum heart rate achieved  
- `exang`: Exercise-induced angina (1 = yes; 0 = no)  
- `oldpeak`: ST depression induced by exercise  
- `slope`: Slope of the peak exercise ST segment  
- `ca`: Number of major vessels (0–3)  
- `thal`: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)  
- `target`: Heart disease presence (1 = yes, 0 = no)  

---

# Data Source

The original data was sourced from:  
- [Kaggle – Heart Disease Prediction Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-prediction)

---

# Data Cleaning Process

1. **Removed Missing Values**: Dropped rows with undefined or null values
2. **Converted Data Types**: Ensured all categorical fields were correctly encoded (e.g., `sex`, `target`, `cp`).  
3. **Renamed Columns**: Made column names consistent and readable.

---

# Tools Used

- **Power BI** – Data visualization and dashboard creation  
- **SQL** – Exploratory queries for pattern discovery  


---

# Key Insights

- **Age** and **chest pain type** are strong indicators of heart disease.  
- **Males** have a slightly higher risk than females in this dataset.  
- **Exercise-induced angina** and high `oldpeak` scores correlate with heart disease.  
- Patients with **higher cholesterol** and **lower max heart rate** are more at risk.  

---

# Recommendations

- Encourage routine cardiovascular screening for individuals over age 40, especially those with frequent chest pain.
- Promote physical activity and monitoring of max heart rate as part of preventive care.
- Health professionals should give attention to patients with exercise-induced angina or high ST depression (oldpeak).
- Gender-specific risk profiling may improve the effectiveness of early diagnosis.

---

# Limitations

- The dataset is relatively small (~300 rows), which limits generalizability.
- Data is historical and may not reflect recent advances in diagnosis or treatment.
- Some variables (e.g., thal, ca) had missing values that were dropped, potentially removing valuable cases.
- The dataset does not include lifestyle factors (diet, smoking, stress), which are significant in heart health analysis.

---
