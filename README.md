# ChurForge : Customer Churn-Prediction
This project aims to aims to predict the customer churn (likelihood of a customer leaving the company) for a telecom company using a variety of ML classification algorithms.
Customer churn refers to the phenomenon where customers or subscribers stop doing business with a company or stop using its services. High churn rates can indicate dissatisfaction among customers or issues with the product or service offered by the company. Hence identifying high risk customers who are likely to leave is a cruicial step to focus on these segment of customers to try and reatain them by providing certain incentives or improving certain aspects that may lead to retention.

Deployment
Deployed as a streamlit web app - https://telcom-customer-churn-prediction.streamlit.app/
![image](https://github.com/K-NEUTRON/ChurForge/assets/72002384/5677ccbc-6477-4bd3-8e34-cd0b2adc44d0)


Objective
This can be achieved by building a classification model to predict if a customer is likely to leave the company based on certain user features.
Explore different models rangiong from simple logistic regression to decision trees and neural networks to compare and identify best performing and most suitable model.
Dataset
The Dataset is obtain from IBM sample data which is also available on Kaggle. The Dataset has columns consisting of the following information:

Customer Demographics information - gender, age, partner, dependents, city, zip code, latitude and longitude
Customer Account info - features related to contract, payment method, paperless billing, monthly charges, and total charges
Customer Services info - features related to phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Churn Info - If the user stopped using the product in the past month.
EDA
1. Correlation of different feature with the predictor
   ![image](https://github.com/K-NEUTRON/ChurForge/assets/72002384/a6e73253-9985-4b1a-945a-8aa80be60d35)

2. Feature Importance from XGBoost
   ![image](https://github.com/K-NEUTRON/ChurForge/assets/72002384/ec51e983-b67d-491b-9760-320da4b34451)



Models Used
Logistic Regression
Gaussian Naive Bayes
Random Forest
Gradient Boot
XGBoost
Kernel SVM
Note - Hyperparameter tuning was performed for Random Forest and XGBosst to get optimal performance.

Model Evaluation Comparisions
* Initial Comparisions
  ![image](https://github.com/K-NEUTRON/ChurForge/assets/72002384/f4650e99-4764-49d2-898e-4e10a8e44d33)

* After SMOTEEN (over-sampling to deal with class imbalances)
  ![image](https://github.com/K-NEUTRON/ChurForge/assets/72002384/0df4edf1-687d-4046-9457-a470fed57639)

* Best Performing Model (XGBoost)
  ![image](https://github.com/K-NEUTRON/ChurForge/assets/72002384/4e9ada82-c181-4a2c-a76e-1a0a128085e0)

