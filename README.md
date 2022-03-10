# Ad Click Prediction 

* **Objective:** Predict whether or not an internet user will click on an ad based off the features of that user
* Project starts off with exploratory data analysis to get a feel for the dataset
* Some data preprocessing and feature engineering is done to prepare dataset for modeling
* An accuracy of 90% was achieved using a simple logistic regression model (baseline model)
* A random forest model was trained with base parameters to acheive a 93% classification accuracy
* Hyperparameter tuning was performed using gridsearch over 4 hyperparameters. The Out-of-Bag (OOB) error was used as the validation score. Classification accuracy was improved to 94.5% 
* **Conclusion:** A 5% increase in Classifcation accuracy over the baseline model (logistic regression) was achieved.
* Future work: The Ad topic feature can perhaps be encoded into a numerical feature based on sentiment score and used in the model as another feature. 
