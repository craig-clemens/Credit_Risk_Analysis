# Credit_Risk_Analysis

## Overview
With something as difficult to predict as credit risk it is important to look at all factors of our availible data when considering applications for a loan. The methods that we used was to create a train models. Specifically, we use imbalanced-learn and scikit-learn libraries for our model creation. To evaluate our models we used a resampling method. The first few models were oversampeld using Random Over Sample and Smote and then undersampled using Smoteenn. To compare two different models, with the idea of minimizing bias, we used Balanced Random Forest Classifier and Easy Ensemble Classifier.

## Summary of Results

* Oversampling Results: When calculating a balanced accuracy score we generate a result of 65.3%. This is combined with a high risk precision that has a incredibly low positivity of 1% and a recall of 63%.

!(NROversampling)[https://github.com/craig-clemens/Credit_Risk_Analysis/blob/main/Resources/NROversampling.PNG]

* Smote Oversampling Results: here our accuracy score is 66% with a precision of high risk at a identical 1%. The recall here is 66%.

!(SmoteOversampling)[https://github.com/craig-clemens/Credit_Risk_Analysis/blob/main/Resources/SmoteOversampling.PNG]

* Undersampling Results: here we can see that our undersampling balanced accuracy score is 43.5% while the precision is at 99% and the recall is at 44%

!(Undersampling)[https://github.com/craig-clemens/Credit_Risk_Analysis/blob/main/Resources/Undersampling.PNG]

* Combined Over and Under sampling Results: the balanced accuracy score for both combined Over and Under sampling  is 54.2% and the precision is 99% with a recall of 54%.

!(Combination)[https://github.com/craig-clemens/Credit_Risk_Analysis/blob/main/Resources/Combination.PNG]

* Balanced Random Forest Classifier Results: our accuracy score is 90.7%, our precision is 99% and the recall is 91%

!(RandomForest)[https://github.com/craig-clemens/Credit_Risk_Analysis/blob/main/Resources/RandomForest.PNG]
 
 * Easy Ensemble Classifier Results: the accuracy score is 94%, the precision score is 99% and the recall is 94%.

 !(EasyEnsemble)[https://github.com/craig-clemens/Credit_Risk_Analysis/blob/main/Resources/EasyEnsemble.PNG]


 ## Conclusion

 In an ideal scenario there would be a good balance of recall and precision. With that in mind, it is clear that the ensmble classifier model is by far the supieror model. This offers us a balance of all models with high accuracy scores along with a decent balance of precision and recall scores.
