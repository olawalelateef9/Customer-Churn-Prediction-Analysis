# Customer-Churn-Prediction-Analysis
This repository contains a machine learning pipeline to predict customer churn based on historical data. The project demonstrates data preprocessing, feature engineering, model training, and evaluation. This project uses a combination of exploratory data analysis and machine learning to predict which customers are likely to churn.
The goal of this analysis was to predict customer churn using various machine learning models, including Logistic Regression, Random Forest, and Support Vector Machine (SVM). Customer churn refers to the likelihood of customers discontinuing their services, and predicting churn helps businesses implement proactive strategies to retain customers.

I used historical customer data, applied preprocessing and feature engineering, and trained the models to assess their performance based on key metrics: accuracy, precision, recall, and F1-score. Here's a summary of the results from each model:

1. Logistic Regression:
Accuracy: 0.7939
Precision: 0.6469
Recall: 0.4947
F1-Score: 0.5606
Logistic Regression performed best in terms of accuracy, with a value of 79.39%. It also had the highest precision, which suggests that the model effectively identifies customers who are likely to churn. However, its recall was moderate, indicating it missed a considerable portion of actual churn cases.

2. Random Forest:
Accuracy: 0.7875
Precision: 0.6354
Recall: 0.4706
F1-Score: 0.5407
The Random Forest classifier had slightly lower accuracy (78.75%) and precision compared to Logistic Regression but exhibited a comparable recall. This model's performance was balanced, though it did not outperform Logistic Regression in any of the metrics.

3. Support Vector Machine (SVM):
Accuracy: 0.7854
Precision: 0.6277
Recall: 0.4733
F1-Score: 0.5396
SVM produced results similar to the Random Forest model, with a slightly lower accuracy of 78.54% and a comparable balance between precision and recall. Like the other models, it struggled to achieve high recall, indicating that identifying all churn cases remains challenging.

Conclusion
While all three models delivered comparable performance, Logistic Regression slightly outperformed the others, particularly in terms of accuracy and precision. However, none of the models excelled at recall, which means there is room for improvement in identifying all potential churn cases. Further optimization through hyperparameter tuning or the use of more advanced models may improve the overall performance, particularly in recall.
