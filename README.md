Problem Statement:
Detecting parkinson's disease from Image data of D2 Dopamine Receptors of Patients.


Project Overview:
I uploaded the data from a csv file to a pandas dataframe and at first glance I could see that the dataset was a little unbalanced and messy.
First, I removed unnecessary columns and cleaned the data, splitted the data to train and test datasets and used BayesSearchCV to optimize hyperparameters for a LightGBM classifier.
After optimization, I used the best parameters to train the classifier and evaluated the results(described in the notebook and report.txt).
