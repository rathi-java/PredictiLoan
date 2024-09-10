# Predictive Loan Analysis

## Overview
**Predictive Loan Analysis** is a machine learning project designed to predict personal loan acceptance based on a set of customer attributes such as age, education, income, family size, and more. The project leverages data exploration, feature selection, and machine learning techniques to develop an accurate predictive model.

## Features
- Data Exploration and Visualization
- Feature Selection using Random Forest
- Predictive Modeling (Random Forest Classifier)
- Model Performance Evaluation (Accuracy, Confusion Matrix, Classification Report)
- Scalable for future enhancements

## Technologies Used
- **Python**: Programming language
- **Pandas**: Data manipulation
- **Seaborn/Matplotlib**: Data visualization
- **Scikit-learn**: Machine learning algorithms and utilities
- **Joblib**: Model persistence (saving the trained model)

## Dataset
The dataset used for the analysis includes the following columns:
- **ID**: Unique identifier
- **Pin-code**: Residential area code
- **Age**: Age of the customer
- **Fam members**: Number of family members
- **Education**: Education level (Under Graduate, Graduate)
- **T. Experience**: Total professional experience (in years)
- **Income**: Annual income (in local currency)
- **Mortgage**: Mortgage amount (if any)
- **Fixed Deposit**: Whether the customer has a fixed deposit (yes/no)
- **Demat**: Whether the customer has a Demat account (yes/no)
- **Net Banking**: Whether the customer uses net banking (yes/no)
- **Loan**: Whether the customer applied for a loan (yes/no)

## Project Structure
```bash
|-- datasets/
|   |-- loan_dataset.csv   # The dataset for the analysis
|-- loan_analysis.py       # The main Python script for analysis and model building
|-- loan_prediction_model.pkl  # Saved trained model (Random Forest)
|-- README.md              # Project documentation
