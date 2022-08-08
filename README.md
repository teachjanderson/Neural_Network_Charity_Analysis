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

# The initial model 

<p align="center"><img src="https://github.com/teachjanderson/Neural_Network_Charity_Analysis/blob/main/Images/Model.png" width="600" />

The initial model included 5,981 parameters with 43 inputs, 2 hidden layers, and 1 output layer. The first hidden layer had 43 inputs and 80 neurons. The second layer had 80 inputs and 30 neurons. The activation for both hidden layers was RULE and the output layer used Sigmoid. The target accuraacy for this model was 75%. The model achieved an accuracy 72.63%

# Optimizations

<p align="center"><img src="https://github.com/teachjanderson/Neural_Network_Charity_Analysis/blob/main/Images/Results.png" width="600" />

Four attemps were made to increase the accuracy of this model with limited success. The first attempt focused on using ASK_AMT as the target variable. The parameters of the model were left the same as the initial model. As seen above, this resulted in a loss of accuracy of 1/3 of a percent. The second optimization focused on INCOME_AMT similar to the first optimization. A third hidden layers was added and the neurons were adjusted on the other hidden layers. This was an improvement but still not as efficient as the initial model. Finally, a third and fourth optimization were attempted. Each of these focused on changing the layers, with the fourth optimization adding a dropout layer, and the neurons. Similarly, neither of these were able to achieve the effectiness level of the first attempt. 

## Summary

The initial model achieved the greatest accuracy for Alphabet Soup but is still short of the 75% accuracy level. The different optimizations with changes in variables, layers, epochs, and dropout layers were unable to reach the 75% target. One recommendation is using the Random Forest Classifier as it may resolve problems with overfitting. 
