# Starbucks-Capstone-Project


## Overview
Starbucks, one of the world’s most popular coffee shops, frequently provides offers to its customers through its rewards app to drive more sales. These offers can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). This project is focused on tailoring the promotional offers for customers based on their responses to the previous offers and predict the response of a customer to an offer. Firstly, to best analyze the data thoroughly, Exploratory Data Analysis(EDA) is performed to find the data representations & characteristics. Secondly, machine learning models are built predict the customer’s response to an offer so that Starbucks can properly target who they send their offers to.

## Libraries used:
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- xgboost
- pickle

## Datasets
For this project, the data sets are provided by Starbucks and Udacity in the form of three JSON files. These contains simulated data that mimics customer behavior on the Starbucks rewards mobile app.

- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
- profile.json - demographic data for each customer
- transcript.json - records for transactions, offers received, offers viewed, and offers completed

## Explanation of each variable in the files:

### portfolio.json

id (string) - offer id
offer_type (string) - type of offer ie BOGO, discount, informational
difficulty (int) - minimum required spend to complete an offer
reward (int) - reward given for completing an offer
duration (int) - time for offer to be open, in days
channels (list of strings)

### profile.json

age (int) - age of the customer
became_member_on (int) - date when customer created an app account
gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
id (str) - customer id
income (float) - customer's income

### transcript.json

event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer id
time (int) - time in hours since start of test. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record
Files


## The following files attached to this GitHub's repository include the following:

Starbucks_Capstone_notebook.ipynb: This is the Jupyter Notebook in which I performed all my work.
data: This contains the three JSON files provided by Starbucks / Udacity as noted above.

# Acknowledgements
Thanks to Starbucks and Udacity







