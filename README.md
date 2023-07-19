# flight-price
![Screenshot (452)](https://user-images.githubusercontent.com/96257624/197807693-1dec2f30-3536-4dff-8746-7256665b6553.png)

# Problem Statement:
Travelling through flights has become an integral part of today’s lifestyle as more and more people are opting for faster travelling options. The flight ticket prices increase or decrease every now and then depending on various factors like timing of the flights, destination, and duration of flights various occasions such as vacations or festive season. Therefore, having some basic idea of the flight fares before planning the trip will surely help many people save money and time.

# Goal:
The main goal is to predict the fares of the flights based on different factors available in the provided dataset.

# Approach:
The classical machine learning tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and Model Testing. Try out different machine learning algorithms that’s best fit for the above case.

# Dataset:[here](https://github.com/Bharathkumar-ms/Flight-fare-prediction1/tree/main/Data)


# Project Various Step

# Data Exploration
I started exploring datasets using pandas, NumPy,matplotlib and seaborn.


# Data visualization
Ploted correlation matrix to get insights about dependend and independed variables. Made chats like( Bocxplot,countplot,distplot,pairplot).

![](https://github.com/coderpro2000/flight-price/blob/main/Docs/vis.png)

# Model Selection
Made many Models But selected RandomForest Regressor.

# Hyperparameter Optimization
Using Randomizedsearch CV and GridSearch CV to select the best parameter for training the model

# Model Dump
As per selected trained model is dumped to pickled format for app development

# Ide used Pycharm
![](https://github.com/coderpro2000/flight-price/blob/main/Docs/soft.png)

# Model Accuracy 
81.2%



# Deployed:
Deployed on heroku -- [here](https://flight-fare-prediction-msb.herokuapp.com/predict)




