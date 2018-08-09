
# Home Credit Defaulter Prediction
# 1. Introduction
## 1.1 About Data 
### (Data Source - <a href="https://www.kaggle.com/c/home-credit-default-risk/data">DATA LINK </a> , Data Size - 3GB)
## 1.1 About Data

* application_train/application_test: It is the main training and testing data with information about each loan application at Home Credit. Every loan is identified by the column SK_ID_CURR. Traing data set has the column Target which specifies if the loan was repaid or not. 0 indicated loan was repaid. 1 - not repaid (Bad debts) 

* bureau: data about the client's previous credits from other financial institutions. Each previous credit has its own row in bureau, but one loan in the application data can have multiple previous credits.

* bureau_balance: monthly data about the previous credits in bureau. Each row is one month of a previous credit, and a single previous credit can have multiple rows, one for each month of the credit length.

* previous_application: previous applications for loans at Home Credit of clients who have loans in the application data. Each current loan in the application data can have multiple previous loans. Each previous application has one row and is identified by the feature SK_ID_PREV.

* POS_CASH_BALANCE: monthly data about previous point of sale or cash loans clients have had with Home Credit. Each row is one month of a previous point of sale or cash loan, and a single previous loan can have many rows.

* credit_card_balance: monthly data about previous credit cards clients have had with Home Credit. Each row is one month of a credit card balance, and a single credit card can have many rows.

* installments_payment: payment history for previous loans at Home Credit. There is one row for every made payment and one row for every missed payment.

##### Worked on 122 columns and 400,000 rows
## 1.2 Import Required Packages
-Matplotlib
-Pandas
-Scipy
      psi
      polygamma
      newton
      gamma
-Sklearn
      LabelEncoder
      cross_val_score
      GaussianNB
      SelectFromModel
      accuracy_score
      RandomForestClassifier
      KNeighborsClassifier
      LogisticRegression
      StandardScaler
-seaborne
-Lightgbm
-XGBoost
      XGBClassifier
      plot_importance
-OS
-pymc3

# 2. Exploratory Data Analysis

# 3. Missing Data Observations
# 4. Handling Missing Data
# 5. Plot posterior - MLE & MCMC
# 6. Feature Importance
## 6.1 XGB Classifier
<img src="https://user-images.githubusercontent.com/25045759/29498307-0ac77adc-85c7-11e7-8801-c49982143a0f.jpg" />
## 6.2 Light gbm
<img src="https://user-images.githubusercontent.com/25045759/29498307-0ac77adc-85c7-11e7-8801-c49982143a0f.jpg" />


# 7. Modelling
## 7.1 Model Accuracy Comparision
## 7.2 Choosing the best model
# 8. Prediction
# 9. Conclusion
