# Wine_quality_ml_model
Project:Detecting quality of white wine<br/>
**#Requirements**<br/>
Jupyter notebook<br/>
**#Libraries used:**<br/>
pandas-To handle the DataFrame<br/>
seaborn-for Better Visulization.you can also use some other visualization libraries<br/>
pickle-for creating file and dumping the file<br/>
**#Algorithm used:**<br/>
RandomForestClassifier-its best suited algorithm for large sample data<br/>
**#Accuracy**<br/>
I got Accuracy 72<br/>
This accuracy got without any tuning and further future engineering<br/>
As a beginner i just stopped here if you use further technique the model will get high accuracy<br/>
**#Steps taken**<br/>
1.Importing the data<br/> 
2.Checking for null values and missing values -this data set doesn't contain any null or missing values<br/>
3.Exploratory data analysis<br/>
4.Detecting outliers by boxplot from seaborn<br/>
5.Removing the outliers by 2 techniques:<br/>
    1.IQR-Method<br/>
    2.Percentile method<br/>
4.Checking for best fit model<br/> 
5.Finally RandomForestClassifier got better result<br/>

Data set provided.

