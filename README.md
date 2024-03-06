# Capstone-Modul-3---E-Commerce
Capstone Modul 3 - E-Commerce

ABSTRAK


INTRODUCTION

Online Shopping Consumer’s Buying Behavior of The Thriving E-Commerce Business
Competitiveness Among E-Commerce Platform  
Customer Churn is Affected by Some Variables
What Variables  Affect The Most

PROBLEM STATEMENT

Customer Churn affected by many variables
How to maintain customer’s Tenure
Predictive Models:
1  Predict Customer Churn
2. Variable with significant affection
Classification Models Created For Specific E-Commerce Business
Perfectly Predicts Customer Churn
Further Boosting:
Customer Satisfaction
Customer Loyalty
Increase Customer Life Time Value
Increase Sales


CONCLUSION

Models used for evaluation are:
1. RF 
2. SVC 
3. Tree
4. LR 
5. k-NN 

Top two models set after benchmarking are: 
RF
SVC

Features used:
1. Tenure
2. WarehouseToHome
3. CashbackAmount
4. DaySinceLastOrder
5. Complain
6. SatisfactionScore

 Metrics

1. Accuracy
2. Precision
3. Recall
4. F1

**One of the metrics that is focused the most is Accuracy to minimize errors.

 Sampling

1. Before Undersampling
2. After Undersampling 

**Under Sampling Benchmarked Models is used for training and testing.

Hyper Parameter Tuning

Before Tuned:
Benchmarked Model Accuracy
0 RF 0.854167

After Tuned:
Tuned Model Accuracy
0 RF 0.9125

**There's a slight improvement between before and after tuning process.

Top 3 Significant Features

1. Tenure
2. Cashback
3. WarehouseToHome
4. 
The classification model with the Accuracy metrics and selected features combined, will allow e-commerce company to determine and do action to keep and prevent customers' churn.


RECOMMENDATION

1. Model Selection and Tuning:
Try different machine learning algorithms like GBM, XGBoost, or neural networks.
Use advanced tuning methods to find the best model settings efficiently.

2. Feature Importance:
Explore the data thoroughly to find new features that predict churn.
Use both existing knowledge and external data to make feature sets richer and capture more customer behaviors.

3. Model Evaluation:
Use advanced evaluation techniques like ROC curves and AUC scores for comprehensive assessment.
Deal with imbalanced data by using advanced sampling methods like oversampling or SMOTE.

4. Sampling:
Test both undersampling and oversampling techniques to handle class imbalances and choose the best one.
Use stratified sampling to make sure training and evaluation subsets represent the whole dataset.

5. Continued Improvement:
Try ensemble methods like stacking and boosting to improve model performance.
Monitor model performance regularly and adapt to changes in business and customer behaviors.

6. Actionable Insights:
Communicate effectively between data scientists, business stakeholders, and marketing teams to use model insights for strategies.
Build automated systems to use predictive models for personalized customer engagement and retention efforts.


