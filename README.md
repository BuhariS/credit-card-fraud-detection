<h1 align=center>Credit Card Transactions Fraud Detection</h1>
<h4 align=center> By Buhari Shehu</h4>

<img src="https://cdn.pixabay.com/photo/2016/12/19/08/39/mobile-phone-1917737_960_720.jpg" alt="computer_and phone"  >


## Overview
Credit card fraud is a type of cybercrime that involves the illegal use of payment cards to inflict financial loss on unsuspecting victims.  It can happen when a victim is socially engineered to divulge his card's confidential information or carry out a transaction on behalf of the criminal. And in some cases, it may happen without the knowledge of the victim.[ (Wikipedia Contributors, 2019)](https://en.wikipedia.org/wiki/Credit_card_fraud) The consequences of credit card fraud include financial losses to customers, businesses, banks, the economy, and psychological distress.

This project trained and evaluated six(6) machine learning algorithms and got 0.82 `recall` from the gradient boosting classifier. This implies that the model can correctly identify 82% of the test dataset.

### Data Description
The dataset was obtained from Kaggle [(Machine Learning Group - ULB, 2018)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and it contains two-day credit card transactions of Europeans in the month of September 2013. The Class column of the dataset consists of 492 ones (1) for fraudulent transactions and 284,315 zeros (0) for non-fraudulent transactions. Thus the dataset is highly imbalanced.

With the exception of `time, amount, and class`, all other features of the dataset were anonymized and transformed using principal component analysis (PCA).

### Project File
The project in this repository resides in "credit_card_fraud_detection.ipynb" file.

### Dependencies
The dependencies of this project are:
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- sidetable
- imbalanced-learn and
- xgboost.


## Conclusions
Credit card fraud is one of the cybercrimes that has both psychological and financial implications and it is on the increase. In this project, the two-day credit card transactions dataset was analysed and modelled using various machine learning algorithms. Gradient Boosting Classifier was found to be the best classifier with a recall value of 0.82. This means the model can detect 82 % of the total frauds in the dataset. The model can be deployed to monitor real-time transactions and flag suspicious ones.
