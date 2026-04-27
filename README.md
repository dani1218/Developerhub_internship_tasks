# 📊 DevelopersHub Corporation – Data Science & Analytics Internship Tasks

> Completed data science tasks as part of the **Data Science & Analytics Internship** at DevelopersHub Corporation.  
> Due Date: **15th May, 2026**

---

## 📋 Table of Contents

- [About](#about)
- [Tasks Overview](#tasks-overview)
- [Task 1 – Exploring and Visualizing a Simple Dataset](#task-1--exploring-and-visualizing-a-simple-dataset)
- [Task 2 – Credit Risk Prediction](#task-2--credit-risk-prediction)
- [Task 3 – Customer Churn Prediction](#task-3--customer-churn-prediction)
- [Task 4 – Predicting Insurance Claim Amounts](#task-4--predicting-insurance-claim-amounts)
- [Task 5 – Personal Loan Acceptance Prediction](#task-5--personal-loan-acceptance-prediction)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Author](#author)

---

## About

This repository contains data science and analytics tasks completed during the **DevelopersHub Corporation Internship**. Each task covers a key area of data science — from exploratory data analysis and visualization to building and evaluating machine learning models using Python.

---

## Tasks Overview

| # | Task | Type | Dataset | Status |
|---|------|------|---------|--------|
| 1 | Exploring and Visualizing a Simple Dataset | EDA & Visualization | Iris Dataset | ✅ Completed |
| 2 | Credit Risk Prediction | Classification | Loan Prediction Dataset (Kaggle) | ✅ Completed |
| 3 | Customer Churn Prediction | Classification | Churn Modelling Dataset | ✅ Completed |
| 4 | Predicting Insurance Claim Amounts | Regression | Medical Cost Personal Dataset | ✅ Completed |
| 5 | Personal Loan Acceptance Prediction | Classification | Bank Marketing Dataset (UCI) | ✅ Completed |

---

## Task 1 – Exploring and Visualizing a Simple Dataset

### 🎯 Objective
Understand how to read, summarize, and visualize a dataset using Python.

### 📂 Dataset
**Iris Dataset** – available via `seaborn` library

### 🔍 Approach
- Loaded the dataset using `pandas` and inspected it using `.shape`, `.columns`, and `.head()`
- Created a **scatter plot** to analyze relationships between variables
- Created a **histogram** to examine data distribution
- Created a **box plot** to detect outliers and spread of values

### 📈 Results & Insights
- The Iris dataset contains 150 samples across 3 species with 4 features each
- Petal length and petal width show strong separation between species
- Seaborn's pairplot clearly visualizes class boundaries

### 🛠️ Skills
`pandas` `matplotlib` `seaborn` `EDA` `Data Visualization`

---

## Task 2 – Credit Risk Prediction

### 🎯 Objective
Predict whether a loan applicant is likely to default on a loan.

### 📂 Dataset
**Loan Prediction Dataset** – available on Kaggle

### 🔍 Approach
- Handled missing values using imputation strategies
- Visualized key features: loan amount, education level, and applicant income
- Trained a **Logistic Regression / Decision Tree** classifier
- Evaluated model using **accuracy score** and **confusion matrix**

### 📈 Results & Insights
- Model achieved a good accuracy on test data
- Education level and applicant income are strong indicators of loan approval
- Confusion matrix revealed the balance between false positives and false negatives

### 🛠️ Skills
`Data Cleaning` `EDA` `Binary Classification` `Logistic Regression` `Decision Tree` `scikit-learn`

---

## Task 3 – Customer Churn Prediction (Bank Customers)

### 🎯 Objective
Identify customers who are likely to leave the bank.

### 📂 Dataset
**Churn Modelling Dataset**

### 🔍 Approach
- Cleaned and prepared the dataset by removing irrelevant columns
- Encoded categorical features (Geography, Gender) using **Label Encoding / One-Hot Encoding**
- Trained a classification model to predict churn
- Analyzed **feature importance** to understand churn drivers

### 📈 Results & Insights
- Age, account balance, and number of products are the top factors influencing churn
- Customers from certain geographies showed higher churn rates
- Model successfully identified high-risk customers

### 🛠️ Skills
`Label Encoding` `One-Hot Encoding` `Supervised Classification` `Feature Importance` `scikit-learn`

---

## Task 4 – Predicting Insurance Claim Amounts

### 🎯 Objective
Estimate the medical insurance claim amount based on personal data.

### 📂 Dataset
**Medical Cost Personal Dataset**

### 🔍 Approach
- Trained a **Linear Regression** model to predict insurance charges
- Visualized the impact of **BMI**, **age**, and **smoking status** on charges
- Evaluated model performance using **MAE** and **RMSE**

### 📈 Results & Insights
- Smoking status has the strongest impact on insurance charges
- BMI and age show a positive correlation with charges
- The regression model performed well with low MAE and RMSE values

### 🛠️ Skills
`Linear Regression` `Feature Correlation` `MAE` `RMSE` `matplotlib` `seaborn`

---

## Task 5 – Personal Loan Acceptance Prediction

### 🎯 Objective
Predict which customers are likely to accept a personal loan offer.

### 📂 Dataset
**Bank Marketing Dataset** – UCI Machine Learning Repository

### 🔍 Approach
- Performed data exploration on features like age, job type, and marital status
- Trained a **Logistic Regression / Decision Tree** classifier
- Analyzed results to identify customer segments most likely to accept the loan offer

### 📈 Results & Insights
- Customers with higher income and certain job types showed greater loan acceptance rates
- Middle-aged customers were more likely to accept personal loan offers
- Model provided actionable business insights for targeted marketing

### 🛠️ Skills
`Data Exploration` `Classification Modeling` `Business Insight Extraction` `scikit-learn`

---

## Technologies Used

| Tool / Library | Purpose |
|----------------|---------|
| Python 3.x | Core programming language |
| Pandas | Data loading, cleaning, and manipulation |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Scikit-learn | Machine learning model building and evaluation |
| Jupyter Notebook | Interactive coding and documentation |

---

## How to Run

1. **Clone this repository:**
   ```bash
   git clone https://github.com/dani1218/Developerhub_internship_tasks.git
   ```

2. **Install required libraries:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Open any task notebook** (e.g., `Task_1_Iris_Visualization.ipynb`) and run all cells.

> 💡 Each task is in its own folder with a dedicated Jupyter Notebook (`.ipynb`) file.

---

## Repository Structure

```
📦 developershub-data-science-tasks
├── 📁 Task_1_Iris_Visualization/
│   └── Task_1.ipynb
├── 📁 Task_2_Credit_Risk_Prediction/
│   └── Task_2.ipynb
├── 📁 Task_3_Customer_Churn/
│   └── Task_3.ipynb
├── 📁 Task_4_Insurance_Prediction/
│   └── Task_4.ipynb
├── 📁 Task_5_Loan_Acceptance/
│   └── Task_5.ipynb
└── README.md
```

---

## Author

**Your Name**
- GitHub: [@your-username](https://github.com/dani1218/Developerhub_internship_tasks)
- LinkedIn: [your-linkedin](www.linkedin.com/in/daniyal-khan-b147012b8)
- Email: dk6662805@gmail.com

---

> ⭐ Star this repository if you found it helpful!  
> 📬 Submitted as part of the DevelopersHub Corporation Data Science & Analytics Internship
