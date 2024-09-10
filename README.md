# Predictive Loan Analysis

## Overview
**Predictive Loan Analysis** is a machine learning project aimed at predicting whether a customer is likely to accept a personal loan based on various attributes such as age, income, education, family size, etc. The project involves data exploration, feature selection, and the development of a predictive model using the Random Forest Classifier.

The project provides insights into loan acceptance patterns, helps financial institutions make informed decisions, and automates the prediction process.

## Features
- **Data Exploration**: Visualizing data distributions and relationships.
- **Feature Selection**: Identifying the most important features for loan acceptance prediction.
- **Predictive Modeling**: Building and training a Random Forest model.
- **Evaluation**: Measuring model performance using accuracy and classification metrics.

## Technologies Used
- **Python**: Programming language used for data processing and model development.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib/Seaborn**: Data visualization libraries.
- **Scikit-learn**: Machine learning algorithms and utilities.
- **Joblib**: Saving and loading the trained model.

## Dataset
The dataset contains 5000 records with the following attributes:
- **ID**: Unique identifier.
- **Pin-code**: Residential area code.
- **Age**: Age of the customer.
- **Fam members**: Number of family members.
- **Education**: Education level (Under Graduate/Graduate).
- **T. Experience**: Total professional experience in years.
- **Income**: Annual income (in local currency).
- **Mortgage**: Mortgage amount (if any).
- **Fixed Deposit**: Whether the customer has a fixed deposit (yes/no).
- **Demat**: Whether the customer has a Demat account (yes/no).
- **Net Banking**: Whether the customer uses net banking (yes/no).
- **Loan**: Whether the customer applied for a loan (yes/no).

## Project Structure

```bash
|-- datasets/
|   |-- loan_dataset.csv           # The dataset for the analysis
|-- loan_analysis.py               # Main Python script for data analysis and model building
|-- loan_prediction_model.pkl      # Saved trained model
|-- requirements.txt               # List of dependencies for the project
|-- README.md                      # Project documentation
```

## How to Install

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/predictive-loan-analysis.git
cd predictive-loan-analysis
```

### 2. Set Up a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

### 3. Install Dependencies
Install all required Python packages using the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

### 4. Run the Project
After setting up the environment and installing dependencies, run the main analysis script:
```bash
python loan_analysis.py
```

### 5. View Results
- The model will be trained and saved as `loan_prediction_model.pkl`.
- Classification results and model performance will be displayed in the console.

## License
This project is licensed under the MIT License.
```

Feel free to copy and paste this into your `README.md` file! Let me know if you need any further adjustments.
