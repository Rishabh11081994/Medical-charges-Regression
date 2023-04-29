# Medical-charges-Regression
The project performs regression task to predict medical charges 




Objective: The main objective of the the project to build predictive model to forecast medical expenses based on the feautures
    like age, sex, bmi, smoker, region, number of children etc. The charges is the target column, the regression algorithms 
    like random forest, linear regression, decision tree , k nearest neighbors were implemented and models are evaluated. The 
    significant features are selected using hypothesis test like kruskal wali, spearman correlation, shapiro etc. 
    
    
    
    Details of the dataset

Columns

age: age of primary beneficiary

sex: insurance contractor gender, female, male

bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

children: Number of children covered by health insurance / Number of dependents

smoker: Smoking

region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

charges: Individual medical costs billed by health insurance



The methodology follows in the projects are simple. First step was to do clean the data and pefroms EDA, later feature selection was completed uisng hypothesis test like ANNOVA, kruskal wali, spearman etc. Base model was build with logistic regression model and  different algorithms were applied on the data to build best
predictive model. 

Conclusion
After hypothesis test we find the significant features namely age , smoker, number of children and bmi
assists well to predict medical charges

Random forest model as well KNN works well for the predictive modelling

