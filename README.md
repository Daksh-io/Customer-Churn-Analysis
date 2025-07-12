# Customer Churn Analysis 🔍

Leverage data-driven insights to understand—and proactively reduce—customer churn using Python and Power BI.

## 📂 Project Overview

This repository contains:
- `TCA.ipynb`: A Jupyter notebook performing end-to-end churn analysis using the **Telco Customer Churn** dataset
- `Teco Customer Churn Analysis.pdf`: A report summarizing findings and visuals
- `Telco-Customer-Churn.csv.csv`: The raw dataset (7043 records, 21 features)
- *(Optional)* A Power BI dashboard export (if included)

## 🎯 Objectives

This project aims to:
1. **Explore** the Telco dataset to uncover churn patterns and feature insights  
2. **Preprocess** data (handle missing values, encode categorical variables)  
3. **Feature-engineer** relevant variables (e.g., tenure bins)  
4. **Train predictive models** (Random Forest, Logistic Regression) to classify churners  
5. **Evaluate model performance** using metrics like accuracy, precision, recall, and confusion matrix  
6. *(Optional)* **Visualize insights** through Power BI dashboards and exported PDF  

## 📁 Project Structure

| File                              | Description |
|-----------------------------------|-------------|
| `Telco-Customer-Churn.csv.csv`   | Original customer churn dataset |
| `TCA.ipynb`                       | Jupyter notebook for analysis, model training & evaluation |
| `Teco Customer Churn Analysis.pdf` | Report summarizing key findings |
| *(Optional)* `Customer Churn Dashboard.pbix` | Power BI dashboard file |

## 📊 Dataset Overview

- **Rows**: 7043 customers  
- **Features**: 21 variables including demographics, account info, services, and `Churn` label   

## 🚀 Getting Started

### Requirements

Install required packages via `pip`:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn plotly
