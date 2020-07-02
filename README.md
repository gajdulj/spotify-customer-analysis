# sparkify-customer-analysis

The purpouse of this project is to show an example how interaction level data can be used to customer behaviour, such as probability of cancelling a premium service subscription. This project is a part of my Udacity Data Science nanodegree. More detailed analysis can be found in my [Medium Article](https://medium.com/@jakubgajdul/churn-prediction-retain-and-attract-new-customers-d46909635713)

Summary:
Both random forest and xgboost obtained fairly well performance on predicting churn.
This can be improved by feeding the model with more data. Further analysis can focus on analysing the mispredicted users in more depth. 

xgboost:
accuracy: 0.91
macro f-1 score: 0.81

random forest:
accuracy: 0.85
macro f-1 score: 0.68

Requirements:
* python3
* os
* pandas
* numpy
* sklearn
* xgboost
* matplotlib
* seaborn 
* hyperopt
* pandas-profiling

Files in the repository:
**Sparkify.ipynb-** EDA, data cleaning, feature engineering, modelling
**EDA_report.html-** automated EDA report generated with pandas-profiling on the original dataset
**user_aggregated_data.html-** automated EDA report generated with pandas-profiling on the aggregated dateset.
Files not in the repository:
**mini_sparkify_event_data.json**

