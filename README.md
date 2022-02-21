# Predicting-Combined-Cycle_Power-Plant

This project was created for a learning purpose. 

The following dataset can be accessed on [Kaggle](https://www.kaggle.com/gova26/airpressure)

## Introduction

The dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (EP) of the plant.

Attribute Information:
Features consist of hourly average ambient variables

Temperature (T) in the range 1.81°C and 37.11°C,
Ambient Pressure (AP) in the range 992.89-1033.30 milibar,
Relative Humidity (RH) in the range 25.56% to 100.16%
Exhaust Vacuum (V) in teh range 25.36-81.56 cm Hg
Net hourly electrical energy output (EP) 420.26-495.76 MW
The averages are taken from various sensors located around the plant that record the ambient variables every second. The variables are given without normalization.

The aim is to fit different algorithms to predict Energy Output, evaluate the models and find the one with the best performance.

## Technologies

- Python 3.9 (IDE: Spyder)
- libraries: scikit learn, numpy and matplotlib

### Machine Learning Algorithms
- Multiple Linear Regression
- Polinomial Regression
- Support Vector Regression (with feature scaling)
- Decision Tree
- Random Forest

## Results
The metric applied to evaluate performance was R2-adjusted for all the ML Algorithms. **Random Forest performed better (96.1)** than other ML algorithms as following: Support Vector Regression (94.8), Polinomial Regression (94.5), Multiple Linear Regression (93.2), and Decision Tree Regression (92.2) in order to predict Energy Output (EP) based on the features.   

## References
The codes were based on the course Machine Learning from A-Z: Hands-on Python & R in Data Science from Udemy with some adaptations.
