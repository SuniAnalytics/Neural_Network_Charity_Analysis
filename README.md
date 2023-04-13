# Neural_Network_Charity_Analysis

## Overview

  Goal of the project is to assist alphabet soup's business team to make an informed decision on which organization predict whether application will succeed if funded by Alphabet Soup. 
  
  Source Data: History of all 34K organization that received funding over the years.
  
  Objective is to analyse the data set and build a machine learning, nueral network model with high accuracy to provide predictions.
  
  We use the following methods for the analysis:

     - preprocessing the data for the neural network model
     - compile, train and evaluate the model
     - optimize the model
  

## Results

* Data Processing

   * Target variable for the model
     - IS_SUCCESSFUL is the target variable for the model
     
   * What variable(s) are considered to be the features for your model?
      - Application Type, Affiliation, use case, Income Amt etc are the features of the model

    ![](https://github.com/SuniAnalytics/Neural_Network_Charity_Analysis/blob/main/Resources/1.%20Target%20and%20Features.png)
   
   * What variable(s) are neither targets nor features, and should be removed from the input data?
     - Few variables like EIN and NAME are dropped from the dataset


* Compiling, Training and Evaluating the model

   * How many neurons, layers, and activation functions did you select for your neural network model, and why?
      - 100, 80, 30 nuerons
      - 3 layers
      - Activation functions: 
           Relu: For the hidden layers
           Signoid: For binary classification

    ![](https://github.com/SuniAnalytics/Neural_Network_Charity_Analysis/blob/main/Resources/2.%20Model%20Parameters.png)
      
   * Were you able to achieve the target model performance?
      - Yes, acheived 79% accuracy for the model
      
    ![](https://github.com/SuniAnalytics/Neural_Network_Charity_Analysis/blob/main/Resources/3.%20Model%20Performance.png)
    
   * What steps did you take to try and increase model performance?
      - Used a combination of different features to see which features are having a higher impact on model performance. 
      - Increased numbers of nuerons on one of the hidden layers and then created one with three layers instead of 2

## Summary 

   

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.


