

# Cardiovascular-Risk-Prediction
The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

**Problem Statement:** 

 The dataset is from an ongoing cardiovascular study on residents of the town
of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-
year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It
includes over 4,000 records and 15 attributes.


![AdobeStock_241906878_optimised](https://user-images.githubusercontent.com/96189065/222941167-3e547087-c21d-4959-89b0-5ab68fca79a7.jpg)



**Approaches:**

1. Data Inspection
2. Data processing
    a. NaN values detection and conversion depending upon their size
    b. Outliers detection
    c. Data Duplication detection
    d. Data Encoding
    e. Drop some not useful column
3. EDA
4. Outliers removal using interquartile and z score
5. Data balancing
6. Train test model
7. Apply model
8. Comparison between various models
9. Use Predictive model for testing data
10. Find out important feature on which our target variable depend


**Conclusion:** 

The main aim of this project is to compare the accuracy and other parameters like
precision, recall ,f1 score, auc roc of all the classification algorithms to evaluate the risk of 10-year
CHD using 14 features. After implementing four classification models and comparing their
accuracy and other scores, we can conclude that for this dataset Random forest Classifier is the
appropriate model to be used. Also out of all features CigsPerDay, age and BP are the most
important feature which decided the person having chance of 10 year heart diseases or not.
