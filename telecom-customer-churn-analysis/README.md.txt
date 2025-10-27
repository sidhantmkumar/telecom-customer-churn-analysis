# 📊 Telecom Customer Churn Analysis

![GitHub last commit](https://img.shields.io/github/last-commit/sidhantmkumar/telecom-customer-churn-analysis?color=blue)
![Python](https://img.shields.io/badge/Python-3.10+-yellow)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

### _A data-driven project to uncover why customers leave a telecom service and how to retain them._

---

## 🌟 Project Overview

Customer churn is one of the biggest challenges in the telecom industry.  
This project uses **Python-based exploratory data analysis (EDA)** to identify the main factors behind churn and generate actionable business insights.

By analyzing customer demographics, service usage, and billing details, the goal is to help telecom companies **predict and reduce churn rates**, thereby improving customer retention and revenue.

---

## 🎯 Objectives

- Explore customer behavior and churn patterns  
- Identify which features most strongly influence churn  
- Visualize key relationships between billing, contracts, and churn  
- Translate analytical results into business recommendations  

---

## 🧰 Tools & Technologies

| Category | Tools / Libraries |
|-----------|------------------|
| **Programming** | Python |
| **Data Handling** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Modeling (Future)** | Scikit-learn |
| **Environment** | Jupyter Notebook |
| **Version Control** | Git & GitHub |

---

## 📂 Project Structure

telecom-customer-churn-analysis/
│
├── data/
│ └── telecom_churn.csv # Sample dataset (cleaned)
│
├── notebooks/
│ └── Teleco_churn_analysis.ipynb # Main analysis notebook
│
├── visuals/
│ └── churn_distribution.png # Optional exported plots
│
├── requirements.txt # Project dependencies
└── README.md # Project documentation

yaml
Copy code

---

## 📊 Dataset Overview

Each row represents one customer and their details:

| Feature Category | Examples |
|------------------|-----------|
| **Demographics** | Gender, SeniorCitizen, Partner, Dependents |
| **Services** | InternetService, PhoneService, MultipleLines |
| **Contracts & Billing** | Contract, PaymentMethod, MonthlyCharges, TotalCharges |
| **Target Variable** | `Churn` (Yes / No) |

> _Source: Publicly available telecom churn dataset (cleaned version used here)._

---

## 🔍 Key Insights & Findings

1. Customers on **month-to-month contracts** are most likely to churn.  
2. **Higher monthly charges** are directly linked to higher churn rates.  
3. **Electronic check payments** show the highest churn ratio among payment methods.  
4. **Long-tenure customers** are more loyal and rarely churn.  
5. Customers **without partners or dependents** are more prone to leave early.

These findings highlight that churn is often driven by **pricing sensitivity and lack of long-term commitment.**

---

## 📈 Visual Highlights

The notebook includes:
- 📊 Churn distribution visualizations  
- 📉 Tenure vs. churn scatterplots  
- 💳 Payment method comparisons  
- 🔥 Correlation heatmap between features  

---

## 🚀 How to Run Locally

1. **Download the project**
   - Click the green **Code → Download ZIP** button on GitHub  
   - Extract it to your computer

2. **Install dependencies**
   - Open the folder in Jupyter or VS Code  
   - Run:
     ```bash
     pip install -r requirements.txt
     ```

3. **Launch the notebook**
   ```bash
   jupyter notebook notebooks/Teleco_churn_analysis.ipynb
🔮 Future Enhancements
Add a machine learning model (e.g., Logistic Regression, Decision Tree) for churn prediction

Develop an interactive dashboard using Streamlit or Power BI

Automate data cleaning and visualization pipelines

##Author:
Sidhant Kumar
📍 Vellore Institute of Technology (VIT)
🎓 Data Analytics & AI Enthusiast
📧 sidhantmkumar@gmail.com
🔗www.linkedin.com/in/sidhant-k-1315ba289/

I enjoy using data to understand people and systems — and turning analysis into actionable stories. This project reflects my approach: clear insights, clean visuals, and real-world impact.

🧩 License
This project is licensed under the MIT License.

⭐ Acknowledgements
Thanks to open-source communities and public datasets that make data analytics learning accessible to everyone.

🌟 If you found this useful
Give this repository a ⭐ on GitHub — it motivates me to share more analytics projects!