# 📊 HR Analytics Job Change EDA

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on an HR Analytics dataset to understand the factors that influence a candidate's decision to look for a new job.

The analysis focuses on candidate demographics, education, experience, company characteristics, training hours, and job-switching behavior. Through visualization and statistical exploration, the project uncovers meaningful patterns and insights that can help organizations improve employee retention strategies.

---

## 🎯 Objectives

* Understand the distribution of candidates across various demographic and professional attributes.
* Analyze the relationship between candidate characteristics and job change behavior.
* Identify factors that may influence employee turnover.
* Generate actionable business insights through data visualization and analysis.

---

## 📂 Dataset Features

The dataset contains information about:

* Candidate demographics
* Gender
* Education level
* Major discipline
* Relevant experience
* University enrollment status
* Work experience
* Company size
* Company type
* Training hours
* City development index
* Job change target variable

### Target Variable

* **0** → Candidate is not looking for a job change.
* **1** → Candidate is looking for a job change.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Analysis Performed

### Data Understanding

* Dataset overview
* Data types inspection
* Summary statistics

### Data Cleaning

* Missing value analysis
* Duplicate record detection
* Data quality checks

### Univariate Analysis

* Gender distribution
* Education level distribution
* Experience distribution
* Training hours distribution
* Company size analysis

### Bivariate Analysis

* Experience vs Job Change
* Education Level vs Job Change
* Gender vs Job Change
* Company Size vs Job Change
* Training Hours vs Job Change

### Target Variable Analysis

* Job change distribution
* Class balance analysis

### Correlation Analysis

* Relationship among numerical variables
* Heatmap visualization

---

## 📈 Key Questions Answered

* What percentage of candidates are looking for a job change?
* Is the dataset balanced or imbalanced?
* Does work experience influence job-switching behavior?
* Are freshers more likely to change jobs?
* Does education level affect job change decisions?
* Does company size influence employee turnover?
* Do training hours impact job-switching behavior?
* Does city development index affect job mobility?

---

## 💡 Key Insights

* Candidates with lower experience levels tend to switch jobs more frequently.
* STEM graduates represent a significant portion of the dataset.
* Job-switching behavior varies across company sizes.
* Training hours show varying influence on employee mobility.
* City development index may play a role in career movement decisions.

---

## 📁 Project Structure

```text
HR_Analytics_Job_Change_EDA/
│
├── HR_Analytics_Job_Change_EDA.ipynb
├── README.md
└── dataset.csv
```

---

## 🚀 How to Run

1. Clone the repository.
2. Install required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook using Jupyter Notebook or VS Code.
4. Run all cells sequentially.

---

## 📚 Conclusion

This project demonstrates the use of Exploratory Data Analysis techniques to uncover patterns and trends in employee job-switching behavior. The findings can help HR teams and organizations better understand workforce dynamics and make data-driven retention decisions.
