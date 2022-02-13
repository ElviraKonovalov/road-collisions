# soen471-bigData

## Abstract
The purpose of this study is to analyze vehicle collisions data using supervised machine learning techniques. Specifically, to identify the features that contribute most to road collisions and to compare the results of a decision tree and a neural network. Our project addresses the following research questions:

1. Which features (location, date, and time of the accident, driver’s conditions, etc.) are most significant in determining the severity and outcome of an accident? Or, which features characterize road collisions?
2. Can one predict the outcome of an accident by analyzing the attributes of an accident?
3. Which machine learning technique predicts best the outcome and severity of a vehicle collision accident?

Our team investigates these questions using the “Motor Vehicle Collisions involving Killed or Seriously Injured Persons” dataset which includes all traffic collisions events where a person was either Killed or Seriously Injured (KSI) from 2006 – 2020 in the city of Toronto (https://open.toronto.ca/dataset/motor-vehicle-collisions-involving-killed-or-seriously-injured-persons/). The dataset consists of 16,861 motor vehicle collisions and is composed of 50+ numerical and categorical features (many will be removed and/or pre-processed beforehand).<br>
These data features include:
1. information about location, date and time of the accident
2. information about road and weather conditions (visibility, light, etc.) during the time of the accident
3. description of the driver involved (age, sex, etc.) and driver’s driving conditions (speed, alcohol, disability, etc.)
4. other information about the event (vehicle type, vehicle manoeuvrer, etc.)

The study analyzes the data using two machine learning techniques: a decision tree and a neural network. These two methods were chosen as they handle data very differently, and it is interesting to compare their performances and interpret the results from them. Before applying the data to the machine learning models, our team will clean and pre-process the data. That is, handle any missing values and encoding as well as remove redundant and irrelevant features.
