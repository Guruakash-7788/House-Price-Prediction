# California House Price Prediction and Model Deployment

This repository contains files related to California House Price Prediction and the deployment of the trained model using FastAPI.

## Project Overview

In this project, I obtained the California House Price Prediction dataset by CAM NUGENT from Kaggle. The dataset can be found [here](https://www.kaggle.com/datasets/camnugent/california-housing-prices). I used Jupyter Notebook for training the House Price Prediction Model.

## Steps Used To Train and Deploy the Model

### Step 1: Data Collection

- Obtained the California House Price Prediction dataset by CAM NUGENT from Kaggle.
- Used Jupyter Notebook to train the House Price Prediction Model.

### Step 2: Training the Model

- Installed all required libraries and modules mentioned in the `requirements.txt` file.
- Imported necessary libraries and modules for data preprocessing and model training.
- Analyzed the data and looked for outliers.
- Checked for null values.
- Performed data preprocessing, including handling skewed distributions and converting categorical data to numerical data.
- Conducted feature engineering.
- Split the preprocessed dataset into train and test sets.
- Scaled/standardized/normalized the features of X_train and X_test.
- Fit the Model using Linear Regression.
- Calculated the evaluation metrics.
- Stored the trained model as a `.pkl` file using Joblib.

### Step 3: Reusing the Model

- To Reuse the trained model we can use our stored `.pkl` file for predicion.

These are all the steps required to train and use the California House Price Prediction model. Feel free to explore the repository for more details and files related to this project.
