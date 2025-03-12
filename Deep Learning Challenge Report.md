# deep-learning-challenge

Overview of the Analysis

The purpose of this analysis is to develop and evaluate a deep learning model for predicting the success of funding applications submitted to Alphabet Soup. The model aims to classify applications into successful and unsuccessful categories based on various applicant features.

Data Preprocessing

Target Variable:
IS_SUCCESSFUL (indicates whether the funding application was approved or not).

Feature Variables:
APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE
ORGANIZATION
STATUS
INCOME_AMT
SPECIAL_CONSIDERATIONS
ASK_AMT

Removed Variables:
EIN and NAME 

Compiling:
We used 2 layers one the first run through and then 3 layers to create a more accurate result.
We were only able to achieve 73 percent accuracy and the target was 75.  We did not meet our goal.
The Steps we took for improving accuracy included changing features, increasing layers and early stopping.

Summary

The deep learning model provided insights into the factors influencing the success of funding applications but did not meet the target accuracy. Despite optimization efforts, the model's performance plateaued, suggesting that deep learning may not be the best approach for this dataset.
