# loan_project
### Summary

Prior to data analysis, numerical data of the object type was converted. Although the ordinal data type was not specified in the dataset information, string values were converted to integer values based on an analysis of the dataset. 

For missing value handling, rows with very few missing values were removed, and separate methods were used to fill in the missing data for columns with missing values.


Outliers were examined, and columns where incorrect data entry was suspected were corrected using the IQR method.



The following models were tested on the dataset using GridSearch CV:

* KNeighborsClassifier
* RandomForestClassifier
* GradientBoostingClassifier
* LogisticRegression
* XGBClassifier


Subsequent to evaluating these models, the best model was selected. Using this model, a cost-benefit analysis was performed based on the average values in the dataset to analyze the current situation and the bank's customer policies.