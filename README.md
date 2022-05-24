# Credit_Risk_Analysis

## Overview of the analysis
For the project, supervised machine learning models will be useed to analyze credit risk prediciton. Once the data is split into two sets, testing and training, multipule modles, such as SMOTE and SMOTEENN, are used to to determine the risk of an applicant. After evaluating the performances of the models, it is then looked at which would be best to predict credit risk. 

## Results
1. Naive Random Oversampling
- Balanced Accuracy Score: 62.49%
- Precision Score Low Risk: 100%
- Precision Score High Risk: 1%
- Recall Score Low Risk: 65%
- Recall Score High Risk: 60%

![image](https://user-images.githubusercontent.com/96198468/170135946-34356779-dcce-4c22-9c78-3b2e63cefc41.png)

2. SMOTE Oversampling
- Balanced Accuracy Score: 65.12%
- Precision Score Low Risk: 100%
- Precision Score High Risk: 1%
- Recall Score Low Risk: 66%
- Recall Score High Risk: 64%

![image](https://user-images.githubusercontent.com/96198468/170136131-2611c0e6-bbe0-404f-bec7-ff39e19be948.png)

3. Cluster Centroids Undersampling
- Balanced Accuracy Score: 51.03%
- Precision Score Low Risk: 100%
- Precision Score High Risk: 1%
- Recall Score Low Risk: 43%
- Recall Score High Risk: 59%

![image](https://user-images.githubusercontent.com/96198468/170136280-4cd10610-9331-4b06-8b29-9e5da1f586d8.png)

4. SMOTEENN
- Balanced Accuracy Score: 51.03%
- Precision Score Low Risk: 100%
- Precision Score High Risk: 1%
- Recall Score Low Risk: 43%
- Recall Score High Risk: 59%

![image](https://user-images.githubusercontent.com/96198468/170136445-76548b1a-9db7-41ec-9c9b-6b56a535e15f.png)

5. Balanced Random Forest Classifier
- Balanced Accuracy Score: 
- Precision Score Low Risk: 
- Precision Score High Risk: 
- Recall Score Low Risk: 
- Recall Score High Risk: 

6. Easy Ensemble AdaBoost Classifer
- Balanced Accuracy Score: 
- Precision Score Low Risk: 
- Precision Score High Risk: 
- Recall Score Low Risk: 
- Recall Score High Risk: 

## Summary
After looking at 4 of the modles, we can see that while all of the modles are under 90% balanced accuracy, it is clear that the SMOTEENN and Cluster Centroids modles should not be used. I would reccommend the Naive Random Oversampling in this situation. This is due to the higher balanced accuracy at 62.49%.
