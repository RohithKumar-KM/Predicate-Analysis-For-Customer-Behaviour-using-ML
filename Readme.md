# Predictive Analytics for Customer Behavior using Machine Learning

## 📌 Project Overview

This project focuses on analyzing customer behavior and predicting customer churn using Machine Learning techniques. The primary objective is to identify customers who are likely to discontinue the service so that businesses can implement effective retention strategies.

The project follows a structured workflow consisting of data preprocessing, exploratory data analysis (EDA), feature engineering, machine learning model development, model evaluation, and business recommendations.

---

## 🎯 Objectives

- Analyze customer behavior using historical data.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Identify factors influencing customer churn.
- Build multiple machine learning models.
- Compare model performance.
- Recommend business strategies to reduce customer churn.

---

## 📂 Dataset

**Dataset Used:** IBM Telco Customer Churn Dataset

The dataset contains:

- 7,043 customer records
- 33 original features
- Customer demographics
- Service subscription details
- Billing information
- Customer Lifetime Value (CLTV)
- Churn information

Target Variable:

- **Churn Value**
  - 0 → Customer Retained
  - 1 → Customer Churned

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Visual Studio Code
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Git
- GitHub

---

## 📚 Python Libraries

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```


## 📁 Project Structure

```
Predictive-Analysis-For-Customer-Behaviour-using-ML/
│
├── Dataset/
│   └── Customer_churn.csv
│
├── Phase1.ipynb
├── Phase2.ipynb
│
├── Predicate_analysis_report.pdf
├── Predictive-Analytics-for-Customer-Behaviour.pptx
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## ⚙️ Project Workflow

```
Customer Dataset
        │
        ▼
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Model Building
        │
        ▼
Model Evaluation
        │
        ▼
Business Recommendations
```

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Customer Churn Distribution
- Tenure Analysis
- Monthly Charges Analysis
- Contract Type Analysis
- Internet Service Analysis
- Payment Method Analysis
- Customer Lifetime Value Analysis
- Correlation Heatmap
- Customer Segmentation
- Demographic Analysis

---

## 🤖 Machine Learning Models

Three supervised learning algorithms were implemented.

| Model | Accuracy |
|---------|----------|
| Decision Tree | 77.33% |
| Random Forest | 79.03% |
| Logistic Regression | 80.31% |

Random Forest provided the best overall performance for customer churn prediction.

---

## 📈 Model Evaluation

Evaluation metrics used:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 🔍 Important Features

The Random Forest model identified the following important features:

- Tenure Months
- Total Charges
- Monthly Charges
- Contract Type
- Customer Lifetime Value (CLTV)
- Internet Service
- Payment Method

These features significantly influence customer churn prediction.

---

## 💡 Business Recommendations

- Improve retention of new customers.
- Encourage customers to switch to long-term contracts.
- Offer loyalty rewards for high-value customers.
- Improve customer support.
- Promote automatic payment methods.
- Develop personalized marketing campaigns.

---

## 📸 Sample Outputs

The project includes:

- Data visualizations
- Correlation Heatmap
- Feature Importance Graph
- Confusion Matrix
- Classification Report
- Model Comparison

---

## 🚀 Future Improvements

- Hyperparameter Optimization
- XGBoost Implementation
- Deep Learning Models
- Real-time Customer Churn Prediction
- Deployment using Flask or Streamlit

---

## 👨‍💻 Author

**Rohith Kumar K M**

Machine Learning Internship Project

---

## 📄 License

This project is developed for educational and internship purposes.
