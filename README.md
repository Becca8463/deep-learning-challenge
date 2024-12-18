# deep-learning-challenge
﻿Neural Network Model Report
Overview of the analysis
The purpose of this assignment is to create and optimize a machine learning model to predict if an organization's loan application will be successful.


Results
Data Preprocessing
-First we dropped the ID columns, 'EIN' and 'NAME'. To improve the model, we check which ones have a low frequency count to put in a bucket named 'other'.
-The target variable is the 'IS_SUCCESSFUL' column.
- We removed 'EIN' and 'NAME' because they were not features or targets.


Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model
-Random state was 45.
-Hidden Layer 1: 6 neurons with ReLU activation
-Hidden Layer 2: 6neurons with ReLU activation
-Output Layer: A single neuron with sigmoid activation for binary classification output
-The initial model only achieved a 72% accuracy.
-All models stayed around the same accuracy even with taking out a hidden layer.
-Increasing the bin sizes did not increase the accuracy.


Were you able to achieve the target model performance?
-No. All attempted models stayed between 72 and 73 percent accuracy. 


What steps did you take in your attempts to increase model performance?
- I took out a hidden layer which did not have the desired effect. I then tried smaller and larger binning however no major effect happened.


Summary
The neural network model was close to 73% accuracy. I personally wouldn't trust this model if giving a loan;however, it isn’t terrible. My goal with adjustments was to achieve 80% or higher however the change of layers did not make a difference. This model will be able to capture some patterns however, it will be limited.
