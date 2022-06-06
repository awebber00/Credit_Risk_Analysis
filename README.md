# Credit_Risk_Analysis

## Project Overview

Predicting credit risk is extremely difficult. The goal of this analysis is to determine whether an individual is low risk or high risk based on their score output. For this assessment we can create a model and then train and evaluate that model to give us our desired results. Here we are using imbalanced-learn and scikit-learn libraries to build models and evalute them using a resampling method. Data oversampling using randomoversampler and smote algorithms was utilized for the first deliverable, and to undersample the data clustercentroid algorithm was used. In the following deliverable a combination of over and undersampling was explored with the data using smoteenn. Lastly, two machine learning models that minimize bias were compared; balancedrandomforestclassifier and easyensembleclassifier.

 ## Results
 
 - Naive Random Oversampling results: The balanced accuracy test is 63%, the precision for the high_risk has a very low positivity at 1% and the recall is 74%

![screenshot](https://github.com/awebber00/Credit_Risk_Analysis/blob/main/Resources/creditriskresampling1.png)

- SMOTE oversampling results: The balanced accuracy score is 66%, the precision for the high_risk loans has a low positvity again at 1% and recall is 63% overall

![screenshot](https://github.com/awebber00/Credit_Risk_Analysis/blob/main/Resources/creditriskresampling2.png)

- Undersampling results: The balanced accuracy score is 66%, the precision is at 99% and the recall is 40%

![screenshot](https://github.com/awebber00/Credit_Risk_Analysis/blob/main/Resources/creditriskresampling3.png)

- For the combined analysis of the over and undersampling: The calculated balance accuracy score is 54%, the precision is at 99% and the recall is 57%

![screenshot](https://github.com/awebber00/Credit_Risk_Analysis/blob/main/Resources/creditriskresampling4.png)

- Balanced Random Forest Classifier results: The calculated balance accuracy score is 78%, the precision is 99%, the recall is overall at 89%

![screenshot](https://github.com/awebber00/Credit_Risk_Analysis/blob/main/Resources/creditriskensemble1.png)

- Easy Ensemble AdaBoost Classifier results: The calculated balance accuracy score is 92%, the precision is 99%, the recall is overall at 94%

![screenshot](https://github.com/awebber00/Credit_Risk_Analysis/blob/main/Resources/creditriskensemble2.png)


## Summary

We utilized a combination of oversampling and undersampling as well as independent cases of both for our analysis to help determine which loans are high risk or low risk. We then resampled the data using ensemble classifiers to perform the analysis. The recall in the samples were in the lower range. The ensemble classifiers are more accurate for this analysis due to us wanting a more balanced output for deteremining the risk of these loans. The Easy Ensemble had the best balance of all the models because of it's high accuracy score and good balance of precision and recall scores.


* Note: All images that are screen shots are mine. All other photos are sourced from Google Images.
