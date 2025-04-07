# DAV-ASSIGNMENT 166
Heart Disease

Heart Disease Data for Health Research

About Dataset:
This dataset contains various health indicators and risk factors related to heart disease. Parameters such as age, gender, blood pressure, cholesterol levels, smoking habits, and exercise patterns have been collected to analyze heart disease risk and contribute to health research. The dataset can be used by healthcare professionals, researchers, and data analysts to examine trends related to heart disease, identify risk factors, and perform various health-related analyses.

Columns ;

Age: The individual's age.

Gender: The individual's gender (Male or Female).

Blood Pressure: The individual's blood pressure (systolic).

Cholesterol Level: The individual's total cholesterol level.

Exercise Habits: The individual's exercise habits (Low, Medium, High).

Smoking: Whether the individual smokes or not (Yes or No).

Family Heart Disease: Whether there is a family history of heart disease (Yes or No).

Diabetes: Whether the individual has diabetes (Yes or No).

BMI: The individual's body mass index.

High Blood Pressure: Whether the individual has high blood pressure (Yes or No).

Low HDL Cholesterol: Whether the individual has low HDL cholesterol (Yes or No).

High LDL Cholesterol: Whether the individual has high LDL cholesterol (Yes or No).

Alcohol Consumption: The individual's alcohol consumption level (None, Low, Medium, High).

Stress Level: The individual's stress level (Low, Medium, High).

Sleep Hours: The number of hours the individual sleeps.

Sugar Consumption: The individual's sugar consumption level (Low, Medium, High).

Triglyceride Level: The individual's triglyceride level.

Fasting Blood Sugar: The individual's fasting blood sugar level.

CRP Level: The C-reactive protein level (a marker of inflammation).

Homocysteine Level: The individual's homocysteine level (an amino acid that affects blood vessel health).

Heart Disease Status: The individual's heart disease status (Yes or No).
# Heart Disease Prediction – Data Analysis Project

This project analyzes the **Heart Disease dataset** to uncover patterns, relationships, and potential indicators related to heart health using Python libraries such as **Pandas, NumPy, Seaborn, and Matplotlib**.

---

## 📊 Dataset Overview

The dataset contains patient records with the following key attributes:

- `age`: Age of the patient
- `sex`: 1 = male, 0 = female
- `cp`: Chest pain type (0–3)
- `trestbps`: Resting blood pressure (in mm Hg)
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- `restecg`: Resting electrocardiographic results (0–2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes; 0 = no)
- `oldpeak`: ST depression induced by exercise
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels (0–3) colored by fluoroscopy
- `thal`: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)
- `target`: 0 = no heart disease, 1 = heart disease

---

## ⚙️ Operations Performed

### ✅ Data Cleaning & Preprocessing
- Loaded using `pandas.read_csv()`
- Checked for nulls, dtypes, basic stats
- Renamed columns for clarity (optional)

### 📈 Exploratory Data Analysis (EDA)
- Count plots and distributions:
  - Age distribution
  - Cholesterol levels
  - Heart disease by gender
- Correlation heatmap
- Grouped statistics based on `target`

### 🧠 Feature Engineering
- Created BMI-like derived features (if height/weight present)
- Binned continuous features into categories
- Normalized values for model readiness

### 🔍 Groupby & Aggregations
- Mean cholesterol by age groups
- Heart disease prevalence by chest pain type
- Gender vs heart disease frequency

### 📊 Visualizations
- Histogram of Age and Cholesterol
- Boxplot: Chol vs Target
- Count plot of Chest Pain Types
- Pie chart of Heart Disease distribution
- Heatmap of correlation between variables

---

## 🧪 How to Run

1. **Clone the repo** or upload notebook + dataset to Colab/Jupyter.
2. Place `heart_disease.csv` in the same directory.
3. Run the notebook (`.ipynb`) file.
4. Install required libraries:
```bash
pip install pandas numpy seaborn matplotlib
📌 Summary
This project provides:

Real-world practice of NumPy & Pandas

Practical EDA and visualization skills

Insightful look into heart health risk factors

You can extend this analysis by adding:

Machine Learning models

Interactive dashboards (e.g., Streamlit or Dash)

Feature selection and model interpretability

