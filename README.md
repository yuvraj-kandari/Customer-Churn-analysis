# 📊 Customer Churn Analysis – Exploratory Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a telecom customer dataset to understand customer behavior and identify patterns associated with **customer churn**.

The analysis covers customer demographics, tenure, services, contract types, payment methods, and billing information using Python-based data analysis and visualization libraries.

---

## 🎯 Objectives

* Understand the overall distribution of customer churn.
* Analyze customer characteristics associated with churn.
* Explore relationships between **tenure, contract type, payment method, and churn**.
* Identify important patterns in customer services and billing.
* Present insights through clear and informative visualizations.

---

## 📂 Dataset

The dataset contains:

* **7,043 customer records**
* **21 attributes**
* Customer demographic information
* Service subscription details
* Contract and payment information
* Monthly and total charges
* Churn status

### Key Features

| Feature           | Description                              |
| ----------------- | ---------------------------------------- |
| `customerID`      | Unique customer identifier               |
| `gender`          | Customer gender                          |
| `SeniorCitizen`   | Whether the customer is a senior citizen |
| `Partner`         | Whether the customer has a partner       |
| `Dependents`      | Whether the customer has dependents      |
| `tenure`          | Number of months the customer has stayed |
| `InternetService` | Type of internet service                 |
| `Contract`        | Customer contract type                   |
| `PaymentMethod`   | Customer payment method                  |
| `MonthlyCharges`  | Monthly amount charged                   |
| `TotalCharges`    | Total amount charged                     |
| `Churn`           | Whether the customer left the service    |

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Development environment

---

## 🔍 Analysis Performed

### 1. Data Inspection

* Examined dataset structure and dimensions.
* Analyzed data types and basic statistical information.
* Worked with **7,043 rows and 21 columns**.

### 2. Data Cleaning

* Checked for missing values.
* Verified dataset consistency.
* Checked customer records for duplicates.
* Prepared numerical variables for analysis.

### 3. Exploratory Data Analysis

Analyzed churn based on:

* Gender
* Senior Citizen status
* Partner and Dependents
* Customer tenure
* Internet service
* Online security
* Online backup
* Device protection
* Tech support
* Streaming services
* Contract type
* Paperless billing
* Payment method
* Monthly charges
* Total charges

### 4. Data Visualization

Created multiple visualizations using **Matplotlib and Seaborn**, including:

* Count plots
* Pie charts
* Histograms
* Stacked bar charts
* Percentage-based comparisons

---

## 📈 Key Findings

* The dataset contains **7,043 customers** across **21 features**.
* **1,869 customers (26.53%)** had churned, while **5,174 customers (73.47%)** remained.
* Average customer tenure was approximately **32.37 months**.
* Average monthly charges were approximately **$64.76**.
* Customer behavior was compared across **17 categorical variables** to identify differences between churned and retained customers.
* Payment methods, contract types, tenure, and subscribed services were explored as potential factors related to churn.

---

## 📊 Project Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Inspection
     ↓
Data Cleaning
     ↓
Statistical Analysis
     ↓
Exploratory Data Analysis
     ↓
Data Visualization
     ↓
Churn Insights
```

---

## 📁 Project Structure

```text
Customer-Churn-Analysis/
│
├── practiceEDA.ipynb
├── Book1.csv
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-analysis.git
```

### 2. Navigate to the project directory

```bash
cd customer-churn-analysis
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
practiceEDA.ipynb
```

---

## 💡 Future Improvements

* Build a **machine learning model** to predict customer churn.
* Perform feature engineering.
* Compare different classification algorithms.
* Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC.
* Develop an interactive dashboard using **Power BI, Tableau, or Streamlit**.

---

## 👨‍💻 Author

**Yuvraj**

This project was developed as part of my learning and practical work in **Data Analysis and Exploratory Data Analysis using Python**.
