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
- Data from 2020 onwards was excluded as the COVID-19 pandemic caused major changes in housing prices that the machine could not learn from.
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
## Model Selection & Training
- Linear Regression
- RandomForestRegressor
- XGboost Regressor
## Hyperparameter Tuning
- GridSearchCV
## Model Evaluation
Training/Validation/Testing split of 70/15/15 to be used.
(Data from 1990-2009 to be trained on, 2010-2014 for hyperparameter tuning, 2015-2019 to be tested on)
Tools of analysis:
- MAPE (mean absolute percentage error)
## Ensembling method
- Average of the 3 models to be taken for predictions

# Work Distribution

Data Preprocessing: Asha, Saamiya

Team 1
Saamiya, Aashka, Andrel : To work on Linear Regression and XGboost models.

Team 2
Asha, Jinal : To work on the RandomForest Regression model.