# energy-comsumption-prediction
Group members: Geoffrey Hung, Jiaqi Chen, Wendeng Hu

## Table of Contents
* Introduction
* Data Prepocessing
* Feature Engineering
* Modeling
* Model Evaluation

## Introduction
Modern building consume energy every day. Recently much investments aimed to improve building efficiencies to reduce costs and emissions have been implemented. The question is, How does these energy consumptions related to the environment, and is the improvement working? Our team focus on building models to depict the general patterns of different buildings' energy consumptions and assess the value of energy efficiency improvements by forcasting the future energy consumptions. With better estimates of these energy-saving investments, large scale investors and financial institutions will be more inclined to invest in this area to enable progress in building efficiencies.

The data is downloaded from kaggle [Great Energy Predictor III](https://www.kaggle.com/c/ashrae-energy-prediction/overview), which contains detailed energy usage information of over 1000 buildings over 3 years time. There are overall 20+ features including building geo locations, weather informations, meter consumptions... The train dataset has 20216100 observations (in year 2016) and test dataset has 41697600 observations (in year 2017 and 2018). Those information come in 5 seperate csv files.


## Data Prepocessing
   - [First look](https://github.com/JiaqiCChen123/energy-comsumption-prediction/blob/master/First_look.ipynb)

Firstly we take a general look into the raw data, and we find that there are **missing values** upon several feature about weather information. 
As for the meter_reading, we find nearly **1/10 of the whole observation has zero values**, which is suspectable.

 - [Data_visualization](https://github.com/JiaqiCChen123/energy-comsumption-prediction/blob/master/First_look.ipynb)
 
 Then we do some basic visualization upon the raw data, from which we find that:
    - There are 
    - ...
    - ...
 
## Feature Engineering
## Modeling
## Model Evaluation

