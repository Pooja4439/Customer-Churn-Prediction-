# Customer-Churn-Prediction -in -Subscription -Service
Overview
This project aims to predict customer churn and provide subscription services for users. By leveraging data analytics and machine learning techniques, the project identifies customers at risk of leaving and suggests strategies to retain them. The project also includes a subscription service to engage users and enhance customer loyalty.
Project Structure
customer-churn-prediction/
├── data/
│   ├── raw/
│   ├── processed/
├── notebooks/
├── src/
│   ├── data_preparation.py
│   ├── model_training.py
│   ├── prediction.py
│   ├── subscription_service.py
├── tests/
├── requirements.txt
├── README.md

Usage
Data Preparation
Place your raw data files in the data/raw/ directory.

Run the data preparation script to clean and preprocess the data:
Model Training
Train the machine learning model using the prepared data:
bash

python src/model_training.py
The trained model will be saved in the models/ directory.
Prediction
Use the trained model to predict customer churn:

python src/prediction.py
The predictions will be saved in the output/ directory.
Subscription Service
Run the subscription service to engage users:


python src/subscription_service.py







