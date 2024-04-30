# Car Crash Estimator
Projekt na mimosemestrální předmět 4EK419 - Připadová studie z business analytics

## Contributors
Mário Hoz

Kateřina Remešová

Jakub Drobil

Kryštof Marval

## Dataset 
[Chicago Traffic Crashes - Chicago Police Dept.](https://www.kaggle.com/datasets/anoopjohny/traffic-crashes-crashes/data)

## Description
![obrazek](https://github.com/marvalkrystof/car_crash_estimator/assets/84131825/cb20faeb-8cc9-4486-a8b7-5e27c6a29734)


The work done on the dataset is well-documented in the .ipynb file, but in summary:
1. Columns which were wrongly recoginzed as objects were categorized into their respective datatypes
2. Exploratory data analysis was done (ensuring data quality - outliers, duplicates, missing values, correlation..)
3. Data preprocessing for the models.. Splitting train and test data
5. Feature engineering.. Categorical variables were binned based on frequency, Creation of dummy variables
6. Creation and training of models  (scaling the data using std scaler, rf classifier, LR, CatBoost)
7. Anvil backend code

Anvil frontend code is separately hosted and developed on the anvil website. [Anvil](anvil.works)

*The app isn't currently hosted anywhere live.*

<p align="center">
  <img src=https://github.com/marvalkrystof/car_crash_estimator/assets/84131825/efc65a75-0870-457b-8d90-ba019aef9d75>
</p>
