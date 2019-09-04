# Capstone: Starbucks

## Contents
1. [Motivation](#motivation)
2. [Project Structure](#projectstructure)
3. [Used Libraries](#usedlibraries)
4. [Summary](#summary)

<a name="motivation"></a>
### Motivation
In this project we utilize simulated data from Starbucks App to get insights on custome's behaivor with offers.
The data consists of three parts 
1. portfolio - which includes information about each offer.
2. profile - which includes informtion about each customer.
3. transcript - which includes data about the offer's and customer transactions.


<a name="projectstructure"></a>
### Project Structure
- `Starbucks_Capstone_Challenge.ipynb` - Main notebook for analysis
- `Starbucks_Capstone_Challenge.html` - An HTML version of the notebook.
- `data` - A folder that contains the datasets
  * `portfolio.json` - containing offer ids and meta data about each offer (duration, type, etc.)
  * `profile.json` - demographic data for each customer
  * `transcript.json` - records for transactions, offers received, offers viewed, and offers completed
- `visuals.py` - A visualization library

<a name="usedlibraries"></a>
### Used Libraries:
In this project we used the following libraries:
- 'pandas'
- 'matplotlib'
- 'numpy'
- 'sikitlearn'

<a name="summary"></a>
### Summary

In this project I have built a model that predicts if an offer will be succesful given the targeted customer information and the offer details. This project followed four steps. In the begging, we have cleaned the data. After that we have constructed a new dataframe which includes all the features that will be used in training the different models. Next, we have trained three different models and evaluated thier performance. Finally, we improved the performance of the one of the selected models.

Although our model was able to predict the success of an offer with accuracy of more than 90%, I believe Starbuck should gather more information about thier customers like martial status, and accomadation location.