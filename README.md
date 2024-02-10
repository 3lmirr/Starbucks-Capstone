# Starbucks Capstone Project | Udacity - Data Scientist Nanodegree

## Overview

Starbucks, a globally renowned coffee chain, frequently utilizes its rewards app to extend offers to its clientele with the aim of boosting sales. These offers range from simple advertisements for drinks to tangible benefits like discounts or BOGO (buy one get one free) deals. This initiative is centered on tailoring promotional offers for customers based on their past responses, aiming to predict how a customer might respond to a particular offer. The project begins with Exploratory Data Analysis (EDA) to thoroughly examine data representations and characteristics. Following this, machine learning models are constructed to forecast customer responses to offers, aiding Starbucks in effectively targeting their offer distribution. This repository contains the Jupyter Notebook for the Starbucks Capstone Challenge, which is part of the Data Science Nanodegree Program by Udacity. The challenge involves analyzing simulated data mimicking customer behavior on the Starbucks rewards mobile app to determine which demographic groups respond best to which offer type.

A detailed report of analysis for this project is available [here](https://medium.com/@elmir3101/mastering-personalization-a-comprehensive-analysis-of-starbucks-reward-program-d77a811017f0).

## Datasets and Inputs

For this project, the data sets are provided by Starbucks and Udacity in the form of three JSON files. These contains simulated data that mimics customer behavior on the Starbucks rewards mobile app.
-   portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
-   profile.json - demographic data for each customer
-   transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:

**portfolio.json**

-   id (string) - offer id
-   offer_type (string) - type of offer ie BOGO, discount, informational
-   difficulty (int) - minimum required spend to complete an offer
-   reward (int) - reward given for completing an offer
-   duration (int) - time for offer to be open, in days
-   channels (list of strings)

**profile.json**

-   age (int) - age of the customer
-   became_member_on (int) - date when customer created an app account
-   gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
-   id (str) - customer id
-   income (float) - customer's income

**transcript.json**

-   event (str) - record description (ie transaction, offer received, offer viewed, etc.)
-   person (str) - customer id
-   time (int) - time in hours since start of test. The data begins at time t=0
-   value - (dict of strings) - either an offer id or transaction amount depending on the record

(As the size of transcript.json is more than GitHub accepts, I upload it in .xlsx format)

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<a name="acknowledgement"></a>
## Acknowledgements

* [Udacity](https://www.udacity.com/) 
* [Starbucks](https://www.starbucks.com/) 

