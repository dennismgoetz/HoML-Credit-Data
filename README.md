# HoML---Credit-Data
The objective of this project was to ```determine bad vs. good credit rating``` with different ML models.

## Project Description
This project was part of the "Hands on Machine Learning" course at Catholic University Eichstätt-Ingolstadt. The objective was to ```determine bad vs. good credit rating```. As the data set stated:
> It is worse to class a customer as good (0) when they are bad (1), than it is to class a customer as bad when they are good (1). (FP worse than FN!!)
It was important for us to classify the bad credit ratings accuratly.
> 
Our ```objectives``` with this project were:
- Create a model that predicts the target value if a new sample has a 'good' or 'bad' credit rating.
- Most important features for credit rating? Reliability.
- Can forward/backward selection improve the performance of the model?
- How well are regression models performing with the categorical data (1hotEncoding)?

We implemented the ML models with ```ColumnTransformers``` and ```Pipelines```.

## Data Set Description
Contains data about people who applied for a loan (e.g.: credit history, purpose of the loan, employment status), and whether the bank deemed them to be a “good” or “bad” credit risk
- instances: 1,000
- features: 20

[Data Source from UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))

## Install and Run this Project
Please install the environment.yml file as follows:
```
conda env create -n ENVIRONMENTNAME -f environment.yml
```
It is important to run all notebooks in following order (to access the variables saved in the Jupyter Notebook kernel):
- Data_Understanding
- Data_Preparation
- Modelling

## Team Members
- [Dennis Götz](https://github.com/dennismgoetz)
- [Vincent Bläske](https://github.com/vini1166)
- [Florian Korn](https://github.com/flo1166)
