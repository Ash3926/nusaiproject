<<<<<<< HEAD
# AI Model to predict HDB Resale Price
=======
**Please ensure you have the necessary libraries installed prior to running the code**
# Predicting Housing Resale Prices
## By Home Bros: Quoid Jing-Xuan Andrel, Jinal Surana, Shah Aashka Anand, Asha Meredith Solomon, Saamiya Khan
## Overview 
We will be utilising datasets from data.gov.sg containing true values of housing resale prices, as well as other continuous attributes to conduct supervised learning to predict housing resale prices.
## Data Collection
These are the datasets we utilised: </br>
[Resale Flat Prices | HDB | data.gov.sg](https://data.gov.sg/collections/189/view) </br>
[Real GDP](https://tablebuilder.singstat.gov.sg/table/TS/M015651) </br>
[Unemployment Rate (End Of Period), Quarterly, Seasonally Adjusted | SINGSTAT | data.gov.sg](https://data.gov.sg/datasets/d_b816a930bca0eb19fdf20fcbfcdd4c39/view) </br>
[Population Size](https://tablebuilder.singstat.gov.sg/table/TS/M810811)
## Data Preprocessing
The attributes we will be referencing from the datasets are: 
- Area Square Meters
- Flat Type
- Month of Sale
- Remaining Lease
- Real GDP (annual)
- Flat Model
- Population
- Unemployment rate
- Distance to CBD
## Feature Engineering
We will use the scikit-learn Standard Scaler
## Model Selection & Training
- Linear Regression
- RandomForestRegressor
- XGboost Regressor
## Hyperparameter Tuning
- Ray Tune
## Model Evaluation
Test/Validation/Training split of 70/15/15 to be used 
(Data from 1990-2009 to be trained on, 2010-2014 for hyperparameter tuning and 2015-2019 to be tested on)
Tools of analysis:
- Lowest possible MAE (mean absolute error)
- Feature Importance Ranking (determine which feature affects the prediction most) - SHAP Analysis
>>>>>>> 24a05d2e83050167b2250b122f6058ec39dfd1b6

Ensure necessary libraries are installed:
- numpy
- sklearn
- math
- time
- geopy
- pandas
- xgboost

Processed files have been uploaded to save time, but to recreate them Run All on the file `Data Preprocessing.ipynb` Takes approximately 40minutes.

To see the model's performance, Run All on the `AI_model.ipynb` file. 