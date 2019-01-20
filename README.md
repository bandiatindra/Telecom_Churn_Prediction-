# Telecom_Churn_Prediction-

Churn is a one of the biggest problem in the telecom industry. Research has shown that the average monthly churn rate among the top 4 wireless carriers in the US is 1.9% - 2%. In this analysis I have tried to first develop some hypothesis by cinducing a detailed exploratory data analysis for churn in the Telecom Industry and used predictive analytics to accurately predict the customers wh are likely to churn.

I have explored the following classficiation techniques and compared their accuracy and other metrics such as ROC-AUC score, True Positive Rate and False Positive Rate.

Models Explored -

1. Logistic Regression
2. Random Forests
3. Supprt Vector Machines (SVMs)
4. ADABoost
5. XG Boost

Overall Approach is as follows -

1. Data Preprocessing - To check for any missing values, correlated variables and dummy encoding
2. EDA to develop hypothesis
3. Scaling data to make sure we are using scaled data to improve accuracy
4. Splitting data into train & test datasets
5. Training each of the above models using cross validation
6. Testing the accuracy on test data and plotting ROC curves for each of the models
7. Comparing each model on various metrics and identifying the important parameters which help explain churn.
