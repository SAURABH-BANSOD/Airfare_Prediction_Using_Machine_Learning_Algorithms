# Airfare_Prediction_Using_Machine_Learning_Algorithms

Objective:
	  The purpose of this project is to study how airline ticket price changes over time, extract the factors that influence this fluctuation and develop a model which could help customers to book ticket at minimum price. Regression & classification are two approaches used for this purpose. The study revealed that mining historical airfare data and modelling using machine learning algorithms, such as Support Vector Machines (SVM), Extra Tree Regressor, etc., can help to predict price trend and save consumers’ money.

DATA COLLECTION:

The data was collected from number of sources. I have collected the data over the span of 69 days from 01/11/19 to 08/01/2020 from Make my trip and IRCTC website. I have selected New Delhi to Bengaluru route for my study. Each day 43 airplanes were departed from New Delhi to Bengaluru. So, data collected has (43 * 69= 2967) tuples and each tuple consisting of various parameters.
Our study is restricted to economy class ticket prices and airplanes having zero stops. Crude oil price data was collected daily from macrotrend.com website for 69 days. Our data set consist of following columns:
	Number of days left till flight departure
	Date of departure
	Crude oil price on a particular day
	Duration of flight
	Departure time 
	Arrival time 
	Taken date 
	Airline name
	Airplane ID 
	Source 
	Destination
We have collected historical crude oil price data from Macrotrends website.
 
 RESULTS:
 1. Extra Trees Regressor algorithm has a highest accuracy of 96.04% for prediction-based modelling in our data set.
 2. Logistic Regression algorithm has good f1-score of 77% for classification-based modelling.
    



