# easyvisa-visa-application-classification
Machine learning classification project to predict visa application certification outcomes and identify key factors influencing certification.
# EasyVisa — Visa Application Classification & Predictive Modeling

## 📌 Project Overview

This project uses machine learning to analyze visa application data and predict whether an application is likely to be **Certified** or **Denied**.

The project focuses on identifying important factors influencing visa certification and evaluating multiple classification algorithms to support a more efficient application-review process.

## 🎯 Business Objective

The objective is to develop a machine learning approach that can help shortlist applicants with a higher probability of visa approval and support more efficient application processing.

The project places particular importance on **recall**, with the goal of minimizing false negatives.

## 📊 Dataset

The dataset contains **25,480 visa application records and 12 variables**.

The target variable is `case_status`, representing:

* Certified
* Denied

The analysis includes applicant, employer, job, wage, education, experience, and employment-related attributes.

## 🛠️ Technologies & Tools

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Machine Learning
* Classification
* Data Visualization

## 🔍 Project Workflow

1. Data Understanding
2. Exploratory Data Analysis
3. Data Cleaning
4. Feature Engineering & Preprocessing
5. Handling Numerical Outliers
6. Class Imbalance Analysis
7. Model Building
8. Model Comparison
9. Model Evaluation
10. Feature Importance Analysis
11. Business Recommendations

## 🧹 Data Preprocessing

The project included:

* Handling anomalous establishment-year values.
* Treating numerical outliers using capping and flooring.
* Encoding the target variable.
* Preparing numerical and categorical features for machine learning.
* Creating processed datasets for model development and evaluation.

## ⚖️ Handling Class Imbalance

Different training approaches were evaluated, including:

* Original dataset
* Oversampled dataset
* Undersampled dataset

This allowed the models to be compared under different class-balance conditions.

## 🤖 Machine Learning Models

Multiple classification algorithms were evaluated, including:

* Decision Tree
* Bagging
* Random Forest
* Gradient Boosting Machine (GBM)
* AdaBoost
* XGBoost

Models were compared using metrics such as accuracy, precision, recall, and cross-validation performance.

## 📈 Model Evaluation

The project evaluated model performance with particular attention to **recall**, because the business objective emphasizes reducing false negatives.

For the oversampled dataset, **XGBoost** achieved the strongest cross-validation recall among the evaluated models at **78.88%**, with a validation recall of approximately **80.53%**.

An AdaBoost model was also evaluated in the project's business-focused model selection, where recall was prioritized for identifying qualified applicants.

## 🔑 Key Business Drivers

The analysis identified important factors associated with visa certification outcomes, including:

* Education level
* Job experience
* Prevailing wage

These factors can help provide a better understanding of characteristics associated with visa certification.

## 💡 Business Recommendations

The project findings can support:

* More efficient screening of visa applications.
* Prioritization of applications based on predicted outcomes.
* Identification of important applicant and employment characteristics.
* Data-driven support for the application-review process.
* Continued monitoring and evaluation of model performance.

## 📁 Repository Structure

```text id="b3e8e0"
easyvisa-visa-application-classification/
│
├── README.md
├── requirements.txt
└── EasyVisa_Classification.ipynb
```

## 👨‍💻 Author

**GNANASEKARAN T**

Data Analyst | Python | SQL | Machine Learning | Statistics | Tableau | Data Science & GenAI

LinkedIn:
https://www.linkedin.com/in/gnanasekaran-t-5a458a39b/
