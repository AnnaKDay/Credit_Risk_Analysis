# Credit_Risk_Analysis
credit risk analysis with supervised machine learning

# Overview
This analysis was conducted to compare 6 different supervised machine learning models to predict credit card risk based on a variety of factors. Furthermore, it strives to identify the most important factors to deciding credit card risk. The goal is to test each model and see which ones handle credit card risk (which is an unbalanced classification) prediction with the least bias and the best accuracy. 

# Results
### Naive Random Oversampling
![Naive](https://user-images.githubusercontent.com/100614266/178161091-a9436d8e-f0a5-476b-a403-a46461ecd31d.png)
![Naive_report](https://user-images.githubusercontent.com/100614266/178161093-6f168277-c29f-4839-b23c-cd0edcfb7d2c.png)
- balanced accuracy score: 64, OK
- High Risk Precision: 0.01, Very Poor
- Low Risk Precision: 1.00 , Very Good
- High Risk Recall: 0.61, Good
- Low Risk Recall: 0.67, Good
- High Risk F1 Score: 0.02, Very Poor
- Low Risk F1 Score: 0.80, Good

### SMOTE Oversampling
![Smote](https://user-images.githubusercontent.com/100614266/178161110-bdd5248c-7b7e-45bd-9a70-7d3666d50235.png)
![Smote_report](https://user-images.githubusercontent.com/100614266/178161111-9e1ea7af-a28a-42dc-8467-26bedfea77dc.png)
- balanced accuracy score: 63, OK
- High Risk Precision: 0.01, Very Poor
- Low Risk Precision: 1.00 , Very Good
- High Risk Recall: 0.62, Good
- Low Risk Recall: 0.63, Good
- High Risk F1 Score: 0.02, Very Poor
- Low Risk F1 Score: 0.77, OK


### Cluster Centroids Undersampling
![Cluster](https://user-images.githubusercontent.com/100614266/178161119-12951250-8d58-444e-aca3-214e87cf90d9.png)
![Cluster_report](https://user-images.githubusercontent.com/100614266/178161122-841241a8-5b53-40b5-a818-4ed4f0ea8d5f.png)
- balanced accuracy score: 51, Poor
- High Risk Precision: 0.01, Very Poor
- Low Risk Precision: 1.00 , Very Good
- High Risk Recall: 0.67, Good
- Low Risk Recall: 0.42, Good
- High Risk F1 Score: 0.01, Extremely Poor
- Low Risk F1 Score: 0.59, Poor


### SMOTEEN Combination Sampling
![SMoteen](https://user-images.githubusercontent.com/100614266/178161129-961e3b71-6761-471f-b80d-64dcfcc691c8.png)
![SMoteen_report](https://user-images.githubusercontent.com/100614266/178161131-bd19f91a-0542-4f0a-9bc7-3b4cb2885b10.png)
- balanced accuracy score: 64, OK
- High Risk Precision: 0.01, Very Poor
- Low Risk Precision: 1.00 , Very Good
- High Risk Recall: 0.7, Good
- Low Risk Recall: 0.58, OK
- High Risk F1 Score: 0.02, Very Poor
- Low Risk F1 Score: 0.73, OK


### Balanced Random Forest Classifier
![brfc](https://user-images.githubusercontent.com/100614266/178161142-ed88fa78-3274-4fb2-86d5-633f5277ae2a.png)
![brfc_report](https://user-images.githubusercontent.com/100614266/178161144-754fe133-d55b-412d-97fb-f9a8c627b46b.png)
- balanced accuracy score: 79, Good
- High Risk Precision: 0.04, Very Poor
- Low Risk Precision: 1.00 , Very Good
- High Risk Recall: 0.67, Good
- Low Risk Recall: 0.91, Very Good
- High Risk F1 Score: 0.07, Very Poor
- Low Risk F1 Score: 0.95, Very Good


### Easy Ensemble AdaBoost Classifier
![ensemble](https://user-images.githubusercontent.com/100614266/178161159-820e9ec1-49b7-47be-be7d-36d9810b9620.png)
![ensemble_report](https://user-images.githubusercontent.com/100614266/178161158-dff96fbe-2ed0-4c10-8a10-4fb4cfd35f4f.png)
- balanced accuracy score: 93, Very Good
- High Risk Precision: 0.07, Very Poor
- Low Risk Precision: 1.00 , Very Good
- High Risk Recall: 0.91, Good
- Low Risk Recall: 0.94, Good
- High Risk F1 Score: 0.14, Very Poor
- Low Risk F1 Score: 0.97, Very Good


# Summary
