## Overview of the Analysis
The purpose of this analysis was to create a logistical regression model to help in predicting healthy or high-risk loans. After creating the model, training it on a sample of the data, and making a confusion matrix and a classification report, I created this report for assessing the models suitability for data-driven business decision-making. Here are my findings: 

#### Results
- __Accuracy: 99%__ -- The model correctly classified most loans with a 99% overall accuracy. 
- __False Classifications__ -- It only __misclassified 146 out of 19,384 cases__.
    - __False Positives__ -- There were 110 healthy loans that were incorrectly classified as high-risk.
    - __False Negatives__ -- There were 36 high-risk loans were incorrectly classified as healthy.
- __Precision for High-Risk Loans: 84%__ -- Of all loans predicted as high-risk, __16% were actually healthy__, which could lead to unnecessary loan denials. 
- __Recall for High-Risk Loans: 94%__ -- The model successfully identified 94% of actual high-risk loans meaning __only 6% of high-risk loans were missed.__ 
- __High Class Imbalance__ -- The dataset contains __18,765 healthy loans and only 619 high-risk loans.__ This could be a factor in the less accurate high-risk classifications. 

### Summary
The logistical regression model demonstrated __high accuracy (99%)__, with particular good predictions for healthy loans. However, there is a concern regarding the precision of high-risk loan predictions. The misclassification of healthy loans as high-risk could lead to a loss in business opportunities. So, while the model is effective at capturing high risk loans, its precision needs improvement before full implementation. Addressing this issue might require techniques such as adjusting the decision thresholds, training the model with more 1 (high-risk loan) cases, or even using other methods of classification to discover more about the data. 
