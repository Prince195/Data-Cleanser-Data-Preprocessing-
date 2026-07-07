# 🏥 Patient Health Records Data Cleanser

A complete data preprocessing project built with Python and Pandas that demonstrates how to clean and prepare healthcare data for analysis and machine learning. The project covers missing value treatment, outlier detection, visualization, and creation of a final cleaned dataset.

---
## 📌 Project Overview

Real-world datasets often contain missing values, inconsistent records, and extreme outliers. This project demonstrates multiple preprocessing techniques on a patient health records dataset to improve data quality before analysis or predictive modeling.

The notebook includes:

- Missing value analysis
- Multiple imputation techniques
- Outlier detection
- Outlier treatment
- Data visualization
- Final cleaned dataset generation

---
## 📂 Dataset

The project uses a synthetic **Patient Health Records** dataset containing **550 patient records** with attributes such as:

- Patient ID
- Age
- Gender
- BMI
- Blood Pressure
- Cholesterol
- Glucose
- Region
- Smoking Status
- Other healthcare-related attributes

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📚 Data Preprocessing Techniques

### Missing Value Handling

Implemented multiple methods including:

- Mean Imputation
- Median Imputation
- Most Frequent Imputation
- Random Sample Imputation
- Missing Indicator
- KNN Imputer
- MICE (Iterative Imputer)

---

### Outlier Detection & Treatment

Different approaches were implemented:

- Z-Score Method
- IQR Method
- Percentile Capping
- Winsorization
-
## 📊 Visualizations

The notebook includes visual analysis such as:

- Missing value distribution
- Box plots
- Histograms
- Before vs After comparison
- Statistical summaries

---

## 📁 Project Structure

```
Patient-Health-Records-Data-Cleanser/
│
├── Data_Cleanser.ipynb
├── patient_health_records_clean.xls
├── README.md
```

---

## 🚀 Features

- Clean and well-structured preprocessing workflow
- Multiple missing value handling techniques
- Multiple outlier treatment methods
- Easy to understand code
- Suitable for beginners in Data Analytics and Data Science
- Ready for Machine Learning preprocessing

---

## 🎯 Learning Outcomes

This project demonstrates practical implementation of:

- Data Cleaning
- Data Preprocessing
- Feature Preparation
- Exploratory Data Analysis (EDA)
- Healthcare Dataset Processing
- Machine Learning Data Preparation

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook

```bash
jupyter notebook Data_Cleanser.ipynb
```

4. Run all cells.

---

## 📈 Output

The project generates:

- Missing value reports
- Outlier analysis
- Cleaned healthcare dataset
- Statistical summaries
- Data visualizations
- Final processed dataset
