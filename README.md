# Credit_Risk
## Overview
###
The purpose of this project is to apply machine learning to analyze/determine credit card risk. To normalize the dataset, we will be using algorithms, such as Naive Random Oversampling, SMOTE Oversampling, Undersampling, Combination Under-Over Sampling, Balanced Random Forest Classifier and Easy Ensemble Adaboost Classifier.
## Result
### Naive Random Oversampling

![Naive Random Oversampling](https://user-images.githubusercontent.com/67567087/166122870-5922f46b-0e5e-44e3-a323-528f693c7c9f.png)
- Balanced Accuracy: 0.6249984891886339
- Precision: high(0.01) & low(1.00)
- Recall: high(0.60) & low(0.65)

### SMOTE Oversampling

![SMOTE Oversampling](https://user-images.githubusercontent.com/67567087/166123023-42d3e9a9-ae0e-4368-ac7c-95efaf735719.png)
- Balanced Accuracy: 0.6512584051472337
- Precision: high(0.01) & low(1.00)
- Recall: high(0.64) & low(0.66)

### Undersampling

![Undersampling](https://user-images.githubusercontent.com/67567087/166123215-2a821448-fa5e-4565-a3ce-f93ef339221e.png)
- Balanced Accuracy: 0.6512584051472337
- Precision: high(0.01) & low(1.00)
- Recall: high(0.59) & low(0.43)

### Combination (Over and Under) Sampling

![Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/67567087/166123258-2d0140ee-9aa3-4152-add9-655ce16c8282.png)
- Balanced Accuracy: 0.5102725100821478
- Precision: high(0.01) & low(1.00)
- Recall: high(0.70) & low(0.57)

### Balanced Random Forest Classifier

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/67567087/166123289-346e7847-05a3-4415-8763-35f243dae653.png)
- Balanced Accuracy: 0.7877672625306695
- Precision: high(0.04) & low(1.00)
- Recall: high(0.67) & low(0.91)

### Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/67567087/166123475-1195b265-e733-42ac-a6a1-7005ea616685.png)
- Balanced Accuracy: 0.925427358175101
- Precision: high(0.07) & low(1.00)
- Recall: high(0.91) & low(0.94)

## Summary
Although accuracy close to 1 is important to determine the best machine learning model, it is also important that we look into high precision for Low Risk Loans and High Recall for High Risk Loans. The reasoning for this is that if a loan is high risk but falsely predicted as low risk, then it would be harmful. Looking into this, the highest accuracy was the Easy Esemble AdaBoost Classifier at 0.93. The precision for low risk in this case was 1.00 and recall for high risk was 0.91. All models had a good precision when it came to predicting low risk, which agrees with the credit loans being an unbalanced classification problem, as good loans heavily outnumbers bad loans. Looking into recall, AdaBoost had the highest recall value, making it a good predictor for high risk loans. 
