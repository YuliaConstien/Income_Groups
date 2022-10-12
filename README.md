# Income Groups Classification

This repository is for the final semester project in the Intelligent Data Analysis and Machine Learning 1 course, in the master of Cognitive Systems programme of Potsdam University.

The task is to predict the income group of the remaining 25.000 interviewees and to

## Problem setting, Dataset and Task 

A polling institute wants to be able to estimate an individual’s income from their personal data. To this aim, 30.000 individuals were interviewed concerning such features as: age, employment type, level of education ...etc. For some of the individuals, not all features are
available. Crucially, the income of only 5.000 of the interviewee’s is known. The task is to predict the income group of the remaining 25.000 interviewees and to
prepare the data such that they can be used for further regression and correlation analyses.

The repository includes:


Dataset.train: the annotated data that was made available by the cpurse examinars. But it needed furthur split into training, valdiation and test sets. 

Project_income: a Google Colaboratory file which includes the whole project and needs a notebook enviroment to be run.

###  Project_income file

This file includes the follwing:

Preprocessing: Feature selection and normalitzation

Models: Logistic regsession model, SVM model, Random forest model, Hyperparameter tunning for all 3 models 

Evaluation : Accuracy, F1 score, precision, recall and AUC results for each mdoel 

Predection: predicting income group for the remaining 5000 interviewees.




