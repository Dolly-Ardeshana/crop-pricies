# Overview

This project aims to predict crop prices based on various features such as Crop, Season, State, Area, Soil type, Pesticide Usage, pH, Temperature, Fertiliser Usage, Price and Rainfall. Three different regression models are implemented and evaluated: Linear Regression, Random Forest Regression, and Support Vector Machine (SVM) Regression. The code preprocesses the data, trains the models, and evaluates their performance using Mean Squared Error (MSE).

## Data Description

The dataset used in this project is stored in a file named ('Crop_Data.csv’). It contains the following columns:

```
Crop :  object 
Season :  object 
State  :  object 
Area  :  numerical
Soil Type :  object 
Pesticide Usage : object 
pH:   object 
Temperature :  object 
Fertilizer Usage: object 
Price :  numerical ( Target )
Rainfall : numerical
```

## Libraries and Modules

The project utilizes the following libraries and modules:

```
pandas
seaborn
matplotlib.pyplot
scikit-learn
```

## Conclusion

This project demonstrates how to preprocess data, train different regression models, and evaluate their performance in predicting crop prices. The visualizations and MSE values help in understanding the model performance and accuracy. After completed the analysis we can conclude that Random Forest Regression model is best for this dataset.
