# Credit_Risk_Analysis

## Overview
With something as difficult to predict as credit risk it is important to look at all factors of our availible data when considering applications for a loan. The methods that we used was to create a train models. Specifically, we use imbalanced-learn and scikit-learn libraries for our model creation. To evaluate our models we used a resampling method. The first few models were oversampeld using Random Over Sample and Smote and then undersampled using Smoteenn. To compare two different models, with the idea of minimizing bias, we used Balanced Random Forest Classifier and Easy Ensemble Classifier.

## Summary of Results

* Oversampling Results: When calculating a balanced accuracy score we generate a result of 65.3%. This is combined with a high risk precision that has a incredibly low positivity of 1% and a recall of 63%.

!(NROversampling)

* Smote Oversampling Results: here our accuracy score is 66% with a precision of high risk at a identical 1%. The recall here is 66%.

!(SmoteOversampling)

* Undersampling Results: here we can see that our undersampling balanced accuracy score is 43.5% while the precision is at 99% and the recall is at 44%

!(Undersampling)

* Combined Over and Under sampling Results: the balanced accuracy score for both combined Over and Under sampling  is 54.2% and the precision is 99% with a recall of 54%.

!(Combination)


 
