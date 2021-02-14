# Credit Risk Analysis
## Overview
The purpose of this project was to leverage the tools of machine learning to analyze creditworthness based on vast datasets.

## Results
Below are the balanced accuracy results for the six different machine learning models:
* This method oversamples the data to predict the results:

![oversampling](https://user-images.githubusercontent.com/71234992/107864144-e5e10f80-6e16-11eb-8c55-59ca4c26a49a.PNG)

* This method oversamples the data using smote to predict the results:

![smote_oversampling](https://user-images.githubusercontent.com/71234992/107864145-e679a600-6e16-11eb-84b3-6def224c7d31.PNG)

* This method undersamples the data to predict the results:

![undersampling](https://user-images.githubusercontent.com/71234992/107864146-e679a600-6e16-11eb-8a3b-8e30d968bb08.PNG)

* This method combines the undersampleing and oversampling data to predict the results:

![combination](https://user-images.githubusercontent.com/71234992/107864142-e5e10f80-6e16-11eb-853a-dfa25a69ee07.PNG)

* This method utilizes the balanced random forest method to predict the results:

![brf](https://user-images.githubusercontent.com/71234992/107864141-e5487900-6e16-11eb-9792-8b50d2178fc3.PNG)

* This method utilizes the easy ensemble adaboost classifier sampling method to predict the results:

![eec](https://user-images.githubusercontent.com/71234992/107864143-e5e10f80-6e16-11eb-9140-a77721e510aa.PNG)

## Summary
It is clear from the results above that the Easy Ensemble AdaBoost Classifier sampling machine learning method is the most accurate with an accuracy over 90%. As such, this is the best method to use.
