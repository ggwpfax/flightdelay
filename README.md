# Flight Delay Prediction
This repository contains a comprehensive project on predicting flight delays using various machine learning models. The project includes data cleaning, preprocessing, exploratory data analysis (EDA), and model training with multiple algorithms. The goal is to build a predictive model that can accurately forecast flight delays based on historical data.

# Introduction
Flight delays cause significant inconvenience and financial losses in the aviation industry. By leveraging machine learning, this project aims to predict potential delays and help mitigate their impact. The dataset used includes various features such as flight schedules, weather conditions, and airline information.

# Models Utilized
This project explores and compares the performance of several machine learning models:
* AdaBoost: AdaBoost_V1.ipynb
* Random Forest:
* Using all features: Flight - Random Forests All features.ipynb
* Balanced dataset: Flight - Random Forests Balanced.ipynb
* Imbalanced dataset: Flight - Random Forests Imbalanced.ipynb
* Multi-Layer Perceptron (MLP) Neural Network:
* Part I: Flight - MLP_NN_Part_I.ipynb
* Part II: Flight - MLP_NN_Part_II.ipynb
* Part III: Flight - MLP_NN_Part_III.ipynb
* Part IV: Flight - MLP_NN_Part_IV.ipynb
* XGBoost: XGBoost_V1.ipynb
  
# Data Preprocessing
Data cleaning and preprocessing are critical steps in preparing the dataset for model training. This involves handling missing values, encoding categorical variables, and scaling numerical features. The following notebooks cover these steps:
* Data_Cleaning_Preprocessing_I.ipynb
* Data_Cleaning_Preprocessing_II.ipynb
* Flight - Data Preprocessing 1.ipynb
* Flight - Data Preprocessing 2.ipynb
  
# Exploratory Data Analysis
EDA is performed to gain insights into the data and understand the underlying patterns and relationships between features. The EDA notebooks include visualizations and statistical analyses:
* EDA_1.ipynb
* EDA_2.ipynb
* Flight - EDA.ipynb
  
# Model Training and Evaluation
Model training is performed using the preprocessed data, and various evaluation metrics such as accuracy, precision, recall, and F1-score are used to assess model performance. The respective notebooks for each model provide detailed steps and results.

# Installation
Clone the repository and install the required dependencies:

`git clone https://github.com/ggwpfax/flight-delay-prediction.git`
`cd flight-delay-prediction`
`pip install -r requirements.txt`

# Usage
* Data Preprocessing: Run the data cleaning and preprocessing notebooks.
* EDA: Explore the data using the EDA notebooks.
* Model Training: Train the models using the respective notebooks.
* Evaluation: Evaluate model performance and compare results.
  
# Results
The performance of each model is documented in the respective notebooks. Comparative analysis and insights are provided to identify the best-performing model for flight delay prediction.
