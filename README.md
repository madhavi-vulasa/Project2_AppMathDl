# Project2_AppMathDl


Predicting the food classes through Transfer learning.
Steps:
Model Training steps:
Create a ModelCheckPoint callback
Create a data augmentation layer
Create a Fucntional Model without a classification layer
Compile the model
Feature extract for 5 full passes ( 5 epochs on train dataset and validate on 15% of test data to save epoch time)


Evaluating our model prediction results we must compare the model classes prediction results with the original test dataset labels.

Finding out the wrong class predictions


Reference : https://github.com/FidelM345/FoodPredictor
