# Online Payment Fraud Detection

## Introduction
Online payment is the most popular transaction method in the world today. However, with an increase in online payments also comes a rise in payment fraud. The objective of this notebook is **to train machine learning models for identifying fraudulent and non-fraudulent payments**. The dataset is collected from Kaggle, which contains historical information about fraudulent transactions which can be used to detect fraud in online payments. 

The dataset consists of 10 variables:
* step: represents a unit of time where 1 step equals 1 hour
* type: type of online transaction
* amount: the amount of the transaction
* nameOrig: customer starting the transaction
* oldbalanceOrg: balance before the transaction
* newbalanceOrig: balance after the transaction
* nameDest: recipient of the transaction
* oldbalanceDest: initial balance of recipient before the transaction
* newbalanceDest: the new balance of recipient after the transaction
* isFraud: fraud transaction


### Python Libraries
pandas, numpy, seaborn, matplotlib, tabulate, sklearn

Random Forest and Naive Bayes were used to identify online payment fraud due to the large dataset.

![image](https://user-images.githubusercontent.com/118715799/210950017-e4d317e0-6bf4-4ecd-8313-9b8121e04e9f.png)

Read the complete Online Payment Fraud Detection project [here](https://github.com/seuwenfei/Online-payment-fraud-detection/blob/main/online-payment-fraud-detection.ipynb).

## Conclusion
The best performing model is **Random Forest** for identifying fraudulent and non-fraudulent payments.
