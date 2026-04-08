# 📊 Healthcare Clinical Trials Analysis

## 📌 Objective
The goal of this project is to clean and analyze clinical trial data to extract meaningful insights and demonstrate real-world data handling skills.

---

## 🧠 Problem Statement
Real-world datasets are often messy and inconsistent. This dataset contains issues such as:
- Inconsistent country names (e.g., "india", "India ", "USA")
- Missing values
- Mixed date formats
- Duplicate records with different IDs

---

## 🛠️ Data Cleaning Steps
- Standardized country names using `country_converter`
- Handled missing values:
  - Country → "Unknown"
  - Enrollment → 0
- Converted mixed date formats into proper datetime
- Extracted Year from date for analysis
- Removed duplicate records based on relevant columns
- Reset index for clean dataset

---

## 📊 Analysis Performed
- Top countries conducting clinical trials
- Most studied diseases
- Trend of trials over time

---

## 📈 Key Insights
- A few countries contribute to the majority of clinical trials
- Certain diseases (like Cancer) dominate the dataset
- Clinical trial activity increases over recent years

---

## 🧰 Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Country Converter

---

## 📁 Output
- Cleaned dataset exported as:
  - `cleaned_clinical_trials.csv`
  - `cleaned_clinical_trials.xlsx`

---

## 🚀 Key Learning
This project highlights the importance of:
- Handling messy real-world data
- Making thoughtful data cleaning decisions
- Understanding data before analysis

---

## ⚠️ Note:
- Missing dates are included as a separate category (<NA>) to ensure transparency in analysis

---

## 👩‍💻 Author

**Sukriti Singh** 
🔗 GitHub: https://github.com/Sukriti-2609
