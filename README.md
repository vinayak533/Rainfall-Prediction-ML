## Project Overview
Rainfall-Prediction-ML predicts rainfall occurrence based on meteorological data like pressure, temperature, humidity, wind speed, and cloud cover using a **Random Forest Classifier**. The project includes data preprocessing, visualization, model training, evaluation, and saving/loading the trained model.

## Dataset
The dataset (Rainfall.csv) contains daily weather readings with features such as:
- pressure, temperature (max, min, avg)
- dewpoint, humidity, cloud, sunshine
- winddirection, windspeed
- rainfall (target: 1 = rain, 0 = no rain)

Missing values are handled, and rainfall is converted to binary.

## Exploratory Data Analysis
- Histograms and KDE plots for feature distribution  
- Boxplots to detect outliers  
- Countplot for rainfall distribution  
- Correlation heatmap

## Model
- Algorithm: Random Forest Classifier  
- Hyperparameter tuning: GridSearchCV  
- Evaluation: Accuracy, confusion matrix, classification report, cross-validation



