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
     
   * Features selected for the model
      - Application Type, Affiliation, use case, Income Amt etc are the features of the model

    ![](https://github.com/SuniAnalytics/Neural_Network_Charity_Analysis/blob/main/Resources/1.%20Target%20and%20Features.png)
   
   * Variables removed from the input data
     - Few variables like EIN and NAME are dropped from the dataset


* Compiling, Training and Evaluating the model

   * No.of neurons, layers, and activation functions used for the nueral network model
      - 100, 80, 30 nuerons
      - 3 layers
      - Activation functions: 
           Relu: For the hidden layers
           Signoid: For binary classification

    ![](https://github.com/SuniAnalytics/Neural_Network_Charity_Analysis/blob/main/Resources/2.%20Model%20Parameters.png)
      
   * Achieved target model performance
      - Yes, acheived 79% accuracy for the model
      
    ![](https://github.com/SuniAnalytics/Neural_Network_Charity_Analysis/blob/main/Resources/3.%20Model%20Performance.png)
    
   * Approach taken to improve the model performance
      - Used a combination of different features to see which features are having a higher impact on model performance. 
      - Increased numbers of nuerons on one of the hidden layers and then created one with three layers instead of 2

## Summary 

![](https://github.com/SuniAnalytics/Neural_Network_Charity_Analysis/blob/main/Resources/3.%20Model%20Performance.png)

       After optimizing the model, accuracy improved to 79% with loss of 43%. Accuracy is higher than the attempted target of 75% and with a decent loss%. 
       However, there is always opportunities to improve the models either by applying correct features or experimenting with models. We can try supervised machine learning models like the Random Forest Classifier to generate a classified output and see if it works.


