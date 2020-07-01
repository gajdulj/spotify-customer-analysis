# spotify-customer-analysis

The purpouse of this project is to show an example how interaction level data can be used to customer behaviour, such as probability of cancelling a premium service subscription. It is my final Udacity Data Science nanodegree project and more detailed analysis can be foun on medium: HYPERLINK

Summary:
Both random forest and xgboost obtained fairly well performance on predicting churn.
This can be improved by feeding the model with more data. Further analysis can focus on analysing in more depth what features contribute to 

xgboost:
              precision    recall  f1-score   support

           0       0.93      0.93      0.93        28
           1       0.60      0.60      0.60         5

    accuracy                           0.88        33
   macro avg       0.76      0.76      0.76        33
weighted avg       0.88      0.88      0.88        33

random forest:
              precision    recall  f1-score   support

           0       0.90      0.93      0.91        28
           1       0.50      0.40      0.44         5

    accuracy                           0.85        33
   macro avg       0.70      0.66      0.68        33
weighted avg       0.84      0.85      0.84        33

Requirements:
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
* Sparkify.ipynb- EDA, data cleaning, feature engineering, modelling
* EDA_report.html- automated EDA report generated with pandas-profiling on the original dataset
* user_aggregated_data.html- automated EDA report generated with pandas-profiling on the aggregated dateset.
Files not in the repository:
* mini_sparkify_event_data.json

