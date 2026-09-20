# Cyber Attack Detector

## Overview

This project analyzes cybersecurity log data to identify characteristics associated with cyber attacks using exploratory data analysis and machine learning.

## Research Question

Which characteristics are most strongly associated with cyber attacks?

## Methods

- SQL data analysis
- Data visualization with Matplotlib
- Data preprocessing using Pandas
- Random Forest Classification

## Results

The Random Forest model achieved:

- Accuracy: 89%
- Precision: 99%
- Recall: 77%

## Key Findings

The Random Forest model identified the following features as the most strongly associated with cyber attacks:

1. Failed Logins
2. IP Reputation Score
3. Login Attempts
4. Session Duration
5. Network Packet Size

## Conclusion

Failed logins, IP reputation score, and login attempts were the strongest predictors of cyber attacks. The model achieved high precision, indicating that attack predictions were highly reliable.

## Technologies Used

- Python
- SQL
- Pandas
- Matplotlib
- Scikit-Learn

## Dataset

This project uses a publicly available cybersecurity dataset.

Source: Cybersecurity Intrusion Detection Dataset by Dinesh Naveen Kumar Samudrala on Kaggle.

Credit to the original dataset creator(s) and publisher.
