Exploring User Behavior with Machine Learning for Service Upgrade
Introduction
This project aims to develop a machine learning model to analyze subscribers' behavior for Megaline, a mobile carrier. The objective is to recommend newer plans (Smart or Ultra) to users currently on legacy plans. The model's accuracy needs to exceed a threshold of 0.75. The data comprises monthly behavior information of subscribers who have already transitioned to the new plans.

Table of Contents
Data Loading and Exploration

Data Preparation

Model Development

Model Testing

Conclusion

Data Loading and Exploration
In this step, the datasets/users_behavior.csv file was loaded and analyzed. It contains the following information:

calls: Number of calls made

minutes: Total call duration in minutes

messages: Number of text messages sent

mb_used: Internet traffic used in MB

is_ultra: Plan for the current month (1 for Ultra, 0 for Smart)

Data Preparation
The dataset was divided into three sets:

Training set (60% of the data)

Validation set (20% of the data)

Test set (20% of the data)

Model Development
To determine the best model, the performance of a decision tree and a random forest model was evaluated by adjusting their hyperparameters. The model with the highest accuracy was chosen for further evaluation.

Model Testing
The selected model was tested using the test dataset to verify its accuracy and performance. The model successfully exceeded Megaline's accuracy requirement of 75%.

Conclusion
Decision Tree Model Accuracy: 78.54%

Random Forest Model Accuracy: 80.56%

Both models exceeded the 75% accuracy threshold, with the random forest model showing slightly higher accuracy. This machine learning model will help Megaline recommend the most suitable plan to customers currently on legacy plans, enhancing customer satisfaction, reducing churn rates, and potentially increasing revenue.
