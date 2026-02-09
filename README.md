# Fraud-Detection-System
Financial Fraud Detection Project
This project identifies fraudulent transactions using machine learning.

#Project Goal
The goal was to build a system that catches fraudsters before they can steal money. It analyzes over 6 million rows of transaction data.

#Model Performance
The model used is a Random Forest Classifier.
The model is correct 97% of the time when it flags a transaction as fraud.
The model successfully caught 74% of the actual fraud cases in the test data.
The model is very good at identifying normal transactions without making mistakes.

#Key Findings
The analysis shows two main red flags for fraud:
Account Balance Change: Fraud usually happens when the sender's account balance is emptied to zero.
Recipient Balance Change: There is often a sudden large increase in the receiver's account.

#Recommendations
The company should create automatic alerts for any transaction that leaves an account with 0 naira.
The company should require an extra PIN or OTP for very large transfers to new accounts.
