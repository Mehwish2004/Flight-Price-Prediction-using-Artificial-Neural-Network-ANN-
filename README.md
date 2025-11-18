# Flight Price Prediction using Artificial Neural Network (ANN)

This project predicts flight ticket prices using a deep learning model built with an Artificial Neural Network (ANN). The dataset is pre-processed, encoded, scaled, and then used to train a regression model that learns the relationship between different flight features and their final price.

## Project Overview
The notebook includes the complete workflow:
1. Importing required libraries  
2. Loading and cleaning the dataset  
3. Encoding categorical features  
4. Scaling numerical features  
5. Splitting data into training and testing sets  
6. Building and training an ANN model  
7. Evaluating the model using regression metrics  
8. Visualizing training progress and prediction results  

## Model Details
- **Model Type:** Artificial Neural Network (Regression)  
- **Layers:**  
  - Dense(128, ReLU) + Dropout  
  - Dense(64, ReLU)  
  - Dense(1)  
- **Loss Function:** Mean Squared Error (MSE)  
- **Optimizer:** Adam  
- **Metrics:** Mean Absolute Error (MAE)  

## How to Run
1. Install the required libraries:
pip install -r requirements.txt

2. Open the notebook:
jupyter notebook

3. Run all cells to:
- Preprocess the dataset  
- Train the ANN  
- View loss graphs  
- Evaluate model performance  
- Plot actual vs predicted prices  

## Evaluation Metrics
The model is evaluated using:
- R² Score  
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  

## Files Included
- `flight_price_prediction.ipynb` — Main notebook  
- `Clean_Dataset.csv` — Dataset used for training  
- `requirements.txt` — Required Python libraries  

## Purpose
This project demonstrates how deep learning can be used for regression tasks such as predicting flight ticket prices based on multiple factors like airline, source city, destination city, travel class, time, and stops.


