# Insight into the nature of road collisions
## SOEN-471 Big Data Analytics

## Abstract
Injuries caused by road collisions are the leading cause of death among children and young adults in Canada [1]. Hence, it is important to get more insight into these events and find patterns to improve road safety.
The purpose of this study is to analyze vehicle collisions data using **supervised machine learning techniques**. Specifically, to identify the features that contribute most to road collisions and to compare the results of a decision tree and a neural network.<br>

Our project addresses the following **research questions**:
1. Which features (location, date, and time of the accident, driver’s conditions, etc.) are most significant in determining the severity and outcome of an accident? Or, which features characterize road collisions?
2. Can one predict the outcome of an accident by analyzing the attributes of an accident?
3. Which machine learning technique predicts best the outcome and severity of a vehicle collision accident?

Our team investigates these questions using the **“Motor Vehicle Collisions” dataset** containing traffic collisions events from 2006 – 2020 in the city of Toronto (https://open.toronto.ca/dataset/motor-vehicle-collisions-involving-killed-or-seriously-injured-persons/). The dataset consists of 16,861 motor vehicle collisions and is composed of 50+ numerical and categorical features (many will be removed and/or pre-processed beforehand).<br><br>
These **data features include**:
1. Information about location, date and time of the accident
2. Information about road and weather conditions (visibility, light, etc.) during the time of the accident
3. Description of the driver involved (age, sex, etc.), driver’s driving conditions (speed, alcohol, disability, etc.) and severity of injury
4. Other information about the event (vehicle type, vehicle manoeuvrer, etc.)

The study analyzes the data using **two machine learning techniques**: a **decision tree** and a **neural network**. 

We have chosen those two techniques because of their ability to deconstruct problems piece-by-piece rather than finding a complex boundary. These two methods also handle data very differently, and it is interesting to compare their performances and interpret the results from them. Tree-based methods split the feature space along the various features in order to optimize the gain of information. On the other hand, with neural networks, each neuron watches over a specific feature space and activates once the input falls into that space. Neural networks have a probabilistic view of the solution, however decision trees are more deterministic.

Before applying the data to the machine learning models, our team will clean and pre-process the data. That is, handle any missing values and encoding as well as remove redundant and irrelevant features.
Using a decision tree or a forest of trees, our team evaluates the importance of features (`feature_importance_ attribute`) in the data and extracts the most discriminating features to address the first question in our research. Our models will be evaluated on testing data and potentially on a similar Montreal dataset to conclude whether one can predict the outcome of an accident based on the accident’s characteristics. The results will be analyzed using various metrics. 

### References
[1] Fridman, L., Fraser-Thomas, J.L., Pike, I. et al. Childhood road traffic injuries in Canada – a provincial comparison of transport injury rates over time. BMC Public Health 18, 1348 (2018). https://doi.org/10.1186/s12889-018-6269-9
