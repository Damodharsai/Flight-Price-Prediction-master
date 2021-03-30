# Flight Fare Prediction: 
![image](https://user-images.githubusercontent.com/78199382/112974569-3ebefa00-9170-11eb-82cc-a046ccd053aa.png)

This repository consists of files required for end to end implementation and deployment of Machine Learning Flight Fare Prediction web application created with Flask and deployed on the Heroku platform.

## Table of Contents
  * [Demo](#demo)
  * [Overview](#overview)
  * [About the App](#About-the-App)
  * [Installation](#installation)
  * [Deployment on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Future scope of project](#future-scope)


## Demo
Link: https://flightfarepredictionwebapp.herokuapp.com/predict

[![](https://i.imgur.com/R1g2wvC.png)](https://flight-price-prediction-api.herokuapp.com/)

[image](https://user-images.githubusercontent.com/78199382/112928400-31841a00-9134-11eb-8cc8-788d21307373.png)


## Overview
This is a Flask web app which predicts fare of Flight ticket.

## About the App
The Airline Flight Fare Prediction is a Flask web application to predict airline flight fares across the Indian cities. The dataset for the project is taken from Kaggle, and it is a time-stamped dataset so, while building the model, extensive pre-processing was done on the dataset especially on the date-time columns to finally come up with a ML model which could effectively predict airline fares across various Indian Cities. The dataset had many features which had to pre-processed and transformed into new parameters for a cleaner and simple web application layout to predict the fares. The various independent features in the dataset were:

Airline: The name of the airline.

Date_of_Journey: The date of the journey

Source: The source from which the service begins.

Destination: The destination where the service ends.

Route: The route taken by the flight to reach the destination.

Dep_Time: The time when the journey starts from the source.

Arrival_Time: Time of arrival at the destination.

Duration: Total duration of the flight.

Total_Stops: Total stops between the source and destination.

Additional_Info: Additional information about the flight

Price: The price of the ticket

## Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── flight_price.ipynb
├── flight_rf.pkl
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 
