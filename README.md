
![Image](https://github.com/JulianTrufero/Diamond-Price-Prediction/blob/main/Images/PORTADA.jpg)

## DIAMOND PRICE PREDICTION
- The goal of this project is the prediction of the price of diamonds based on some of their characteristics (weight, color, quality of cut, etc.), putting into practice different machine learning algorithms and feature extraction techniques
- Firstly, we performed an EDA over the data set and analized the correlation structure of the data. Then we treated the categorical features and used manual label encoding in order to keep the ordinal relevance fo those variables.
- Then, with the training set, we did a test split strategy using 80% of the data for train the models and the 20% left to test them.
- To measure the performance of our models we used the Root Mean Squared Error of prediction (RMSE). We started from a simple model and continue adding some complexity in order to get a better performance, this were the resultant metrics for each of the models used:  
  - Linear Regression: RMSE = 0.1913
  - Decision Tree Regression: RMSE = 0.1187
  - Decision Tree Regression with Cross Validated Grid Search: RMSE = 0.1078
  - Random Forest Regression: RMSE = 0.0934
  - Random Forest Regression with Cross Validated Randomized Search: RMSE = 0.0906
  - XGBoost (Extreme Gradient Boosting) Random Forest Regression: RMSE = 0.08525
- All the analysis was performed with the help of this libraries: [Numpy](https://numpy.org/doc/), [Pandas](https://pandas.pydata.org/docs), [Sklearn](https://scikit-learn.org/stable/), [Seaborn](https://seaborn.pydata.org/), [XGBoost](https://xgboost.readthedocs.io/en/latest/) 

# 
