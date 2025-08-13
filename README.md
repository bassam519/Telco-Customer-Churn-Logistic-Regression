**# Telco-Customer-Churn-Logistic-Regression
Predicting telecom customer churn using logistic regression with data cleaning, EDA, feature encoding, and model evaluation.
**# Predicting Customer Retention with Logistic Regression

This project uses Logistic Regression to predict whether a telecom customer will churn (leave) based on the **Telco Customer Churn dataset**.

## 📌 Project Steps
1. **Data Loading** – Imported Telco dataset
2. **Data Cleaning** – Converted `TotalCharges` to numeric, encoded categorical features
3. **EDA (Exploratory Data Analysis)** – Bar plots, pie chart, box plots to understand churn patterns
4. **Feature Encoding** – Used `LabelEncoder` for categorical variables
5. **Model Training** – Trained a `LogisticRegression` model
6. **Evaluation** – Calculated model accuracy on the test set

## 📊 Results
- **Accuracy:** Achieved XX% accuracy on the test data  
- Insights:
  - Higher monthly charges are correlated with higher churn
  - Customers with shorter contracts are more likely to churn

## 🛠️ Technologies Used
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📂 Dataset
Dataset: [Telco Customer Churn on Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/telco-customer-churn.git
