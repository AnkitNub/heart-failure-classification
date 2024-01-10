# Heart-failure-classification

### Overview
This Jupyter notebook tackles the task of heart failure classification using popular machine learning models. We'll walk through data prep, model building, and evaluating key classifiers – RandomForest, KNN, Logistic Regression, LinearSVM and XGBoost. To enhance performance, we'll fine-tune these models with RandomizedSearchCV and GridSearchCV. Plus, we'll uncover crucial features in our dataset.

### Steps:
1) Problem Definition:
Predict the likelihood of heart failure using machine learning models based on essential health indicators

2) Data:
For this personal project, the dataset for predicting heart failure will be sourced from an open dataset available on Kaggle (https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction). The dataset comprises essential health indicators. Additionally, to prepare the data for machine learning models, categorical columns, such as ["ST_Slope", "ExerciseAngina", "RestingECG", "ChestPainType", "Sex"], will be encoded into numerical values using one-hot encoding. This transformation is crucial for ensuring that the machine learning algorithms can effectively utilize the information contained in these categorical features

3) Evaluation:
Achieving an accuracy rate exceeding 85% is a crucial milestone, warranting further refinement and enhancement of the model.

4) Features:
The following features serve as the basis for discerning the presence or absence of heart disease in our patients.
* Age           
* Sex
* Chest pain type (4 values)
* Resting blood pressure
* Cholesterol
* Fasting blood sugar > 120 mg/dl
* Resting electrocardiographic results (values 0,1,2)
* Maximum heart rate achieved
* Exercise induced angina
* Oldpeak = ST depression induced by exercise relative to rest
* The slope of the peak exercise ST segment


5) Feature Importance:
* Identify and analyze important features in the dataset.
* Visualize the importance of features using appropriate plots.
