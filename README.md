# Credit Card Fraud Detection
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. 

## Dataset: 
The dataset has been obtained from kaggle. This dataset contains 284807 rows and 30 numeric columns and one class that specifies whether the transaction is fraudulent or not. The values of columns V1-V28 in the dataset may be result of a PCA(Principal Component Analysis) Dimensionality reduction to protect user identities and sensitive information. There are no missing values in the dataset.

## Outline:
I. Understanding our data
* Gather Sense of our data

II. Preprocessing
* Scaling and Distributing
* Splitting the Data


III. Random UnderSampling and Oversampling
  a) Distributing and Correlating
  b) Anomaly Detection
  c) Dimensionality Reduction and Clustering (t-SNE)
  d) Classifiers
  e) A Deeper Look into Logistic Regression
  f) Oversampling with SMOTE


IV. Testing 
  a) Testing with Logistic Regression
  b) Neural Networks Testing (Undersampling vs Oversampling)


## Visualisation: 
The library used for visualizing the data, confusion matrix etc. is matplotlib, seaborn.


This code is prepared using Jupyter Notebook.
You can find the dataset here: https://www.kaggle.com/mlg-ulb/creditcardfraud/downloads/creditcard.csv/3
