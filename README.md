# Fintech Churn Prediction
This repository contains the details of a Machine Learning model developed to predict user churn in a fintech company.

Datasets are not uploaded here for 2 reasons: it's size and the fintech company's ownership of them.

You will find two main notebooks:
1) Fintech_churn_prediction: This one contains all the exploration, transformations, tests and development of the model.
2) Fintech_churn_prediction_preprocess_and_predict_pipeline: This one aims to be able to work as a pipeline to gather new information, preprocess it and predict. It uses the fitted models/transformers from the previous notebook. It was used to create DAG in Airflow and get the model in production.
