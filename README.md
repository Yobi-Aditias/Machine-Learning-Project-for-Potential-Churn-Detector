# Machine-Learning-Project-for-Potential-Churn-Detector

In the dynamic landscape of E-Commerce, customer churn, or the rate at which customers cease doing business with a company, holds significant importance. Understanding and predicting churn can be pivotal for businesses to maintain customer satisfaction, improve retention strategies, and ultimately drive profitability.

This project aims to develop a churn detection model using customer data from the E-Commerce dataset ("Dataset - E Comm.csv" obtained from Kaggle). The main file, Analyzing_and_Building_model.ipynb, contains the entire pipeline for loading the data, data exploration, data cleaning, exploratory data analysis (EDA), model building using pipelines, model tuning by comparing several models, hyperparameter tuning to find the best hyperparameters, and more.

## File Structure

**Analyzing_and_Building_model.ipynb**: This is the main file consisting of the entire workflow of the project, including data loading, exploration, cleaning, EDA, model creation using pipelines, model tuning, hyperparameter tuning, and prediction. The pipeline includes encoding, scaling, model creation, hyperparameter tuning, and prediction. The best model from the pipeline is saved in the file modelML.pkl in pkl format.

**testing_to_inference_data.ipynb**: This file contains the process of creating inference data and applying the model stored in modelML.pkl for prediction.

Dataset
The dataset used in this project is "Dataset - E Comm.csv" obtained from Kaggle. It contains customer data from an E-Commerce platform.