# Credit Card Fraud Detection 

The dataset :  [Kaggle Website](https://www.kaggle.com/mlg-ulb/creditcardfraud)  


## Problem Statement
Predict fraudulent credit card transactions using machine learning models.

## Business Overview
Banking fraud threatens customer retention and leads to financial losses and credibility issues. With the rise of digital payments, fraudulent transactions are increasing. Machine learning helps banks reduce manual reviews, chargebacks, fees, and denials of legitimate transactions.

## Understanding Fraud
Credit card fraud involves unauthorized acts to gain financial information. Common methods include:
- Skimming
- Alteration of genuine cards
- Creation of counterfeit cards
- Stolen/lost credit cards
- Fraudulent telemarketing

## Data Overview
The dataset includes credit card transactions by European cardholders over two days in September 2013. Out of 284,807 transactions, 492 were fraudulent (0.172%). Features include:
- `time` Seconds elapsed between the first transaction and subsequent transactions
- `amount` Transaction amount
- `class` Class label (1 for fraud, 0 for non-fraud)
- `V1` to `V28` Principal components from PCA

## Project Pipeline
1. **Data Understanding** Load and understand the features
2. **Exploratory Data Analysis (EDA)** Perform univariate and bivariate analyses, check for skewness, and mitigate if necessary
3. **Train/Test Split** Perform train/test split and use k-fold cross-validation
4. **Model Building/Hyperparameter Tuning** Try different models and fine-tune hyperparameters
5. **Model Evaluation** Evaluate models using appropriate metrics, focusing on precision and recall over accuracy

## Solution Approach
1. **Data Understanding and Exploration**
   - Load and understand the features
   - Identify necessary features for the final model
2. **Data Cleaning**
   - Handle missing values
   - Treat outliers
3. **Exploratory Data Analysis**
   - Perform univariate analysis
   - Perform bivariate analysis
4. **Prepare Data for Modelling**
   - Check and mitigate skewness
   - Handle data imbalance
5. **Split Data into Train and Test Sets**
   - Perform train/test split
   - Scale the data (normalization)
6. **Model Building**
   - Train models with algorithms such as Logistic Regression, SVM, Decision Tree, Random Forest, XGBoost
   - Tune hyperparameters with Grid Search Cross Validation
7. **Model Evaluation**
   - Focus on precision and recall over accuracy
   - Aim for a good ROC score with high TPR and low FPR

## Conclusion
This project aims to predict fraudulent credit card transactions using machine learning models, focusing on handling imbalanced data and evaluating models with appropriate metrics.


