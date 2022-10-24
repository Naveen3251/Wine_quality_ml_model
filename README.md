# Wine_quality_ml_model
Project:Detecting quality of white wine
#Requirements
Jupyter notebook
#Libraries used:
pandas-To handle the DataFrame
seaborn-for Better Visulization.you can also use some other visualization libraries
pickle-for creating file and dumping the file
#Algorithm used:
RandomForestClassifier-its best suited algorithm for large sample data
#Accuracy
I got Accuracy 72
This accuracy got without any tuning and further future engineering
As a beginner i just stopped here if you use further technique the model will get high accuracy
#Steps taken
1.Importing the data 
2.Checking for null values and missing values -this data set doesn't contain any null or missing values 
3.Exploratory data analysis
4.Detecting outliers by boxplot from seaborn
5.Removing the outliers by 2 techniques:
    1.IQR-Method
    2.Percentile method
4.Checking for best fit model 
5.Finally RandomForestClassifier got better result



