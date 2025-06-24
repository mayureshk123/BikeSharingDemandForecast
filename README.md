# `Bike Sharing Demand Forecast`

The Project contains a python file which forecasts demand based on previous 2 years data. The data is cleaned and transformed to make it usable to train a simple linear regression model. The model is then tested to check if it is a good fit or not.

## Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

- The project is related to prediction of demand for a bike sharing platform which has dip in revenue due to Covid 19 pandemic. The US Bike sharing provider aims to be able to forecast demand and be able to meet it when the lockdowns are lifted and normalcy is restored. To do this easily machine learning is used which relies on past data to learn about the patterns in the data and predict the future demand.
- The dataset used is based on various meterological surveys and peoples ride sharing styles is used. It has independant variables such as date, year, month, day of the week, working day, weekday, holiday, season, temperature, feels like temperature, weather situation, humidity and windspeed. it has dependant variables like number of casual users, number of registered users, total number of users who used the bike sharing platform on that day.

## Conclusions

- Data needs to be cleaned and split into training and testing datasets. Training data set is used to train the linear regression model. Whereas, testing data set is used to test the goodness of fit of the model.
- Data needs to be cleaned as it may have missing data or irrelevant data. We may also end up adding dummy variables during transformation or end up transforming existing variables into a new variables. In this case we need to ensure that such variables are deleted from the dataset and not used for training the models.
- It is necessary to visualize the dataset graphically inorder to check which model makes sense to be used.

## Technologies Used

- numpy
- pandas
- matplotlib
- sklearn

## Acknowledgements

The Project was proposed by Upgrad in association with Woolf University.

## Contact

Created by [@mayureshk123] - feel free to contact me!
