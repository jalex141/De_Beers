# De_Beers

![portada](

## Objective

I entered a Kaggle competition about diamond prices. The goal was to make use of the Machine Learning techniques I know to predict the prices of a list of diamond from which we had a set of parameters 

## Project Goals
- Aquire and observe the data set.
- Analyze the different variables and their relations.
- Choose and adapt the variables I am going to use for the predictive model.
- Extract the predicted values for daimond prices

## Data
I am working with a dataset taken from a kaggle competition, consisting of a training csv with a full dataset, a test csv which is missing the price info and a submit example csv

[kaggle link](https://www.kaggle.com/c/diamonds-datamad0921/overview)

## Guidelines

I took the datasets from kaggle, thet are completely clean  
Then I worked on a jupyter notebook to explore the data and prepare some variables  
I used a random forest to obtain the regresion for the prices  
Then predicted with mt model using the test csv and exported the submit csv

****************************


## Repo
I have a diamonds-datamad0921 folder containning my datasets
A testing ipynb where I did the exploration and statistic analyisis
submit.csv with the results for kaggle


## Libraries

- numpy 
- pandas
- seaborn
- matplotlib
- sklearn
- train_test_split
- LinearRegression
- DecisionTreeRegressor
- RandomForestRegressor
- mean_squared_error as mse
- RandomizedSearchCV