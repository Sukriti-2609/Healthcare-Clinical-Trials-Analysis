# 💊 Healthcare Clinical Trials Analysis

## 📖 Overview
This project analyzes global clinical trial data to identify trends in diseases, countries, and study activity over time.  
It demonstrates end-to-end data analysis, including data cleaning, transformation, and exploratory data analysis (EDA) using Python.

---

## 🎯 Objectives
- Clean messy real-world dataset
- Standardize inconsistent country names
- Handle missing values
- Analyze trends in clinical trials
- Visualize key insights

---

## 🚨 Problem Statement
Real-world datasets are often messy and inconsistent. This dataset contains issues such as:
- Inconsistent country names (e.g., "india", "India ", "USA")
- Missing values
- Mixed date formats
- Duplicate records with different IDs

---

## 🧹 Data Cleaning Steps
- Standardized country names using `country_converter`
- Handled missing values:
  - Country → "Unknown"
  - Enrollment → 0
- Converted mixed date formats into proper datetime
- Extracted Year from date for analysis
- Removed duplicate records based on relevant columns
- Reset index for clean dataset

---

## 💹 Analysis Performed
- Top countries conducting clinical trials
- Most studied diseases
- Trend of trials over time

---

## 📌 Key Insights
- Clinical trials are highly concentrated in a small number of countries, indicating uneven global research distribution
- Cancer and Diabetes are the most frequently studied diseases, reflecting global healthcare priorities
- Trial activity shows an increasing trend over time, suggesting growing investment in clinical research

---

## 🧰 Tech Stack 🛠️
- Python (Pandas, NumPy)
- Data Visualization (Matplotlib, Seaborn)
- Country Standardization (`country_converter`)

---

## 🗂️ Project Structure

```
healthcare-clinical-trials-analysis/
│
├── data/
│   │
│   ├── raw/
│   │   └── clinical_trials.csv
│   │
│   └── cleaned/
│       └── cleaned_clinical_trials.csv
│
├── notebooks/
│   └── healthcare_analysis.ipynb
│
├── outputs/
│   │
│   ├── general/
│   │   ├── 1.png
│   │   ├── 2.png
│   │   └── 3.png
│   │
│   ├── plots/
│   │   │
│   │   ├── bar/
│   │   │   ├── enrollment.png
│   │   │   ├── top_countries.png
│   │   │   ├── top_diseases.png
│   │   │   ├── yearwise_distribution_excluding.png
│   │   │   └── yearwise_distribution_including.png
│   │   │
│   │   └── line/   
│   │       ├── trend_over_time_excluding.png
│   │       └── trend_over_time_including.png
│   │
│   └── reports/
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## 🔍 Key Analysis

### 🌍 Top Countries Conducting Trials
- Identified countries with highest clinical trial activity

### 🦠 Most Studied Diseases
-	Cancer and Diabetes dominate research focus

### 📈 Trend Over Time
-	Clinical trials show increasing trend over years

---

## 📂 Output

### 🖥️ General Overview
![1](outputs/general/1.png)
![2](outputs/general/2.png)
![3](outputs/general/3.png)

### 📈 Trend Analysis
![Trend_Over_Time](outputs/plots/line/trend_over_time_excluding.png)
![Trend_Over_Time_MY](outputs/plots/line/trend_over_time_including.png)

### 📊 Distribution Analysis
![Top Countries](outputs/plots/bar/top_countries.png)
![Top Diseases](outputs/plots/bar/top_diseases.png)
![Yearwise](outputs/plots/bar/yearwise_distribution_including.png)
![Yearwise_MY](outputs/plots/bar/yearwise_distribution_excluding.png)
![Enrollment](outputs/plots/bar/enrollment.png)

- Cleaned dataset exported as:
  - `cleaned_clinical_trials.csv`

---

## 🧠 Key Learnings
This project highlights the importance of:
- Handling inconsistent real-world data
- Understanding data before analysis
- Working with missing values and formatting issues 
- Converting and extracting datetime features 
- Performing EDA and generating insights
- Built a reproducible and well-structured data analysis pipeline suitable for real-world datasets

---

## ⚠️ Note:
- Missing dates are included as a separate category (`<NA>`) to ensure transparency in analysis

---

## 👩‍💻 Author

**Sukriti Singh** 
🔗 GitHub: https://github.com/Sukriti-2609

---

## 📎 How to Run

1. Clone the repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Run the notebook in Jupyter or Kaggle
