# 💼 Data Science Job Simulation: Customer Churn Analysis

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Jupyter%20Notebook-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

Welcome to my project repository for the **Customer Churn Prediction Simulation** with **XYZ Analytics**. This project simulates a real-world client engagement, where I acted as a data scientist responsible for analyzing customer churn, building predictive models, and delivering actionable business recommendations to stakeholders.

---

## 📌 Project Objective

The goal of this project is to **predict customer churn** using a machine learning model, based on customer behavior and interaction data, and provide data-driven strategies to help reduce churn, improve customer retention, and ultimately increase profitability.

---

## 🔍 Business Problem

**Client**: XYZ Analytics (hypothetical consultancy simulating real-world BCG/consulting engagements)  
**Division**: SME Product Team  

The client is experiencing high customer churn and wants to understand:
- **Why customers are leaving**
- **Which customers are most at risk**
- **How to reduce churn through targeted actions**

---

## 🧩 Project Structure

| 📂 File | 🧾 Description | 📊 Dataset Used |
|--------|----------------|------------------|
| `T2-Exploratory Data Analysis.ipynb` | Explored and visualized client data to identify trends, outliers, and churn signals | `clean_data_after_edaa.csv` |
| `T3 Feature Engineering & Modelling.ipynb` | Created features and trained multiple models, including the final Random Forest Classifier | `client_data (1).csv`, `price_data (1).csv` |
| `T4 Findings & Recommendations.ipynb` | Evaluated the model and explained business insights derived from predictions | `data_for_predictions.csv` |
| `Executive Summary for Model.pdf` | One-slide executive briefing designed for senior stakeholders and steering committee | Summary of all findings |

---

## 🛠 Tools & Technologies

- **Python 3.9+**
- **Jupyter Notebook**
- **Pandas**, **NumPy** – Data manipulation and preprocessing
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – Machine learning modeling
- **Random Forest Classifier**, **GridSearchCV**, **train-test split**
- **Classification metrics** – Accuracy, F1-Score, ROC-AUC

---

## 🧠 Methodology

### 1. 📊 Exploratory Data Analysis (EDA)
- Explored customer demographics, tenure, spending, product purchases, and interaction with support.
- Identified churn rates across different contract types and usage segments.

### 2. 🛠 Feature Engineering
- Created new variables (e.g., average spend per month, product mix, number of support tickets).
- Transformed categorical data using one-hot encoding.

### 3. 🤖 Model Building
- Built and tuned a **Random Forest Classifier**
- Used stratified train-test split to preserve class distribution
- Performed hyperparameter tuning using `GridSearchCV`

### 4. 📈 Evaluation Metrics
| Metric | Value |
|--------|-------|
| **Accuracy** | 89% |
| **F1 Score (Churn class)** | 0.82 |
| **ROC-AUC Score** | 91% |

These metrics indicate strong model performance in identifying high-risk customers without overfitting.

---

## 💡 Key Insights & Recommendations

### 🔎 Top Churn Drivers
- Low tenure (new customers are more likely to churn)
- High monthly charges
- Increased customer support interactions
- Customers with monthly contracts (vs. annual)

### 🧾 Business Recommendations
- **Introduce loyalty incentives** for long-term contracts
- **Enhance customer onboarding experience** to increase tenure
- **Proactively support high-usage customers** showing early churn signs
- **Use model predictions** to launch targeted retention campaigns

### 💸 Estimated Business Impact
- By acting on the model's top 20% high-risk customers, the client can **reduce churn by up to 25%**
- Potential to **save over $1.2M** annually by retaining high-LTV customers

---

## 📄 Executive Summary

- Delivered a single-slide PDF summarizing the model, findings, and strategic impact
- Presented in a format suitable for a **Steering Committee** meeting, including SME Head and leadership

📎 [View Executive Summary](./Executive%20Summary%20for%20Model.pdf)

---

## 📁 Dataset Summary

| 📄 Dataset | 📌 Used In |
|------------|-----------|
| `clean_data_after_edaa.csv` | `T2-Exploratory Data Analysis.ipynb` |
| `client_data (1).csv` & `price_data (1).csv` | `T3 Feature Engineering & Modelling.ipynb` |
| `data_for_predictions.csv` | `T4 Findings & Recommendations.ipynb` |

---

## 📬 Contact & Connect

If you'd like to know more about this project, collaborate, or explore how machine learning can help solve business problems:

- 🔗 [LinkedIn – Harshita Mahant](https://www.linkedin.com/in/your-link-here)
- 💻 [GitHub – @Harshitamahant](https://github.com/Harshitamahant)

---

## ⭐ Acknowledgements

This project is inspired by real-world simulations from top consulting and analytics firms. Special thanks to mentors and reviewers who helped refine the problem-solving and business storytelling.

---

**📌 If you found this helpful, consider starring ⭐ the repo and sharing it!**
