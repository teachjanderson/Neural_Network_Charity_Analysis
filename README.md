# Neural Network Charity Analysis

## Overview 

Alphabet Soup's business team is evaluating data from over 34,000 organizations in which it has funded over the years. The goal of this analysis is using machine learning and neural networks through TensorFlow and Python to create a binary classifier capable of prediction the success of applicants funded by Alphabet Soup. Various columns were binned to facilitate a deep learning model with a goal of 75% accuracy. The dataset contained the following columns for analysis: 

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively

## Results

# Data Preprocessing

The processing began with focusing on the metrics and variables to consider in training the model. To start the initial model, the columns EIN  and NAME were removed as these added limited to no value to the model. The APPLICATION_TYPE bin was categorized and the IS_SUCCESSFUL column was used as the target variable. The other varibales were then used as features. 

# Compiling, Training, and Evaluating the Model

The initial model 

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
There is a recommendation on using a different model to solve the classification problem, and justification (3 pt)