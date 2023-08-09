# Module 12 Report Template

## Overview of the Analysis



* The purpose of this analyais was to determine the credit risk for 'healthy' loans and for 'high risk loans.'
* The models predict the credit worthiness of individuals based on their credit risk.
* The overall accurracy and precision were attempted to be predicted from the trained models.
* The data was read into a dataframe from the given csv file. Then the data was split into train and test pools. A logistic regression model was trained and then the data was tested from the resulting model. Predictions were then able to be made on the resulting data.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
    Accuracy 99%
    Precision 100 for the healthy loans and 87% for the 'high risk' loans
    Recall scores 100 for the healthy loans and only 89% for the high risk loans



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
    Accuracy of 100 was seen
    Precision was 100 for the healthy loans and 87% for the high risk loans
    Recall was 100 for both loans

## Summary


* The second model seems to predict slightly better than the first with 100% accuracy. However, there is only 87% precision with high risk loans. Both models predict healthy loans well, however neither model predicts high risk loans with enough precision to warrant giving the loan. This is especially true given the loans are considered high risk in the first place.


