
# Project Title

A brief description of what this project does and who it's for

# Fraudulent Credit Card Transactions Prediction

## 🎯 Problem Statement

This project aims to predict fraudulent credit card transactions using advanced machine learning models. We analyze customer-level data obtained through a research collaboration between Worldline and the Machine Learning Group. The dataset, sourced from Kaggle, comprises 284,807 transactions, of which 492 are fraudulent. Given the high imbalance in the dataset, special techniques are required to handle this before model building.

## 💼 Business Problem Overview

For many banks, retaining highly profitable customers is paramount. However, banking fraud poses a significant threat to this goal by causing substantial financial losses and eroding trust and credibility among customers. According to the Nilson Report, banking fraud is projected to amount to $30 billion globally by 2020. As digital payment channels proliferate, the number of fraudulent transactions continues to rise, presenting new and sophisticated challenges.

In the banking industry, leveraging machine learning for credit card fraud detection is crucial. It enables:
- Proactive monitoring and fraud prevention
- Reduced need for time-consuming manual reviews
- Minimized costly chargebacks and fees
- Fewer denials of legitimate transactions

## 🔍 Understanding and Defining Fraud

Credit card fraud encompasses any dishonest act aimed at obtaining account information without proper authorization for financial gain. Common methods of fraud include:

- **Skimming**: Duplicating information from the magnetic strip of the card
- **Manipulation/alteration**: Modifying genuine cards
- **Counterfeiting**: Creating fake cards
- **Theft/loss**: Using stolen or lost credit cards
- **Fraudulent telemarketing**: Conducting fraudulent activities over the phone

## 📊 Data Dictionary

The dataset includes credit card transactions made by European cardholders over two days in September 2013. Out of 284,807 transactions, 492 were fraudulent, resulting in a highly imbalanced dataset where fraudulent transactions represent 0.172% of the total. To maintain confidentiality, the data has been modified using Principal Component Analysis (PCA).

| Feature | Description |
|---------|-------------|
| Time    | Seconds elapsed between the first transaction and subsequent transactions |
| Amount  | Transaction amount |
| Class   | Class label (1 for fraud, 0 for non-fraud) |
| V1-V28  | Principal components obtained via PCA |

## 🚀 Project Pipeline

1. **Data Understanding and Exploration**
   - Load and inspect the dataset
   - Identify and handle missing or anomalous data points

2. **Data Cleaning**
   - Handle missing values
   - Treat outliers

3. **Exploratory Data Analysis (EDA)**
   - Conduct univariate analysis
   - Perform bivariate analysis
   - Identify and mitigate data skewness

4. **Data Preparation for Modeling**
   - Address data imbalance
   - Scale the data using normalization techniques

5. **Train/Test Split**
   - Split dataset into training and testing sets
   - Use k-fold cross-validation

6. **Model Building**
   - Train models (Logistic Regression, SVM, Decision Tree, Random Forest, XGBoost, etc.)
   - Tune hyperparameters using Grid Search Cross Validation

7. **Model Evaluation**
   - Evaluate using Precision, Recall, F1-Score, and AUC-ROC
   - Focus on metrics emphasizing fraudulent transaction detection
   - Aim for balance between Precision and Recall
   - Strive for high True Positive Rate (TPR) and low False Positive Rate (FPR)


## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## 🙏 Acknowledgements

We would like to thank Kaggle for providing the dataset and the Machine Learning Group for their research collaboration.
