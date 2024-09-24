# Lead-Score-Case-Study
Lead-Scoring-Case-Study
Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

Read Data

Import important libraries
Read Leads data into dataframe
Quick review of dataframe
Shape of Leads dataframe¶
Check for conversion rate in dataframe
Analyze data and prepare data

Check for missing values
Check level of categorical columns
Identify columns that have default "Select" value
Check for missing values
Identify categorical columns with missing values
Identify quantitative columns with missing values
Calculate percentage missing values (Re-check)
Checking distribution of these quantitative variables
Impute quantitative columns
Drop columns which has more than 4000 missing values
Impute missing values for categorical values with less missing values
Boxplot for quantitative varibles
Bivariate Analysis
Create dummy variables
Label encoding for other categorical columns
Drop columns with no variance
Checking correlation
Data Preparation for Modeling

Train Test split
Feature Scaling
Model Building

Create a function for model building
Feature Scaling
Use RFE for feature selection
Using statsmodel for rfe columns
Predicting based on latest model
Create confusion metrics
Plot ROC Curve
Find Optimal cutoff value
Plot accuracy sensitivity and specificity
Precision - Recall plot
Making prediction on test set

Find Principal Components using PCA

Logictic Regression on PCA

Model Conclusion

Merging train and test prediction
Merging predictions to original dataframe
Creating Lead Score column
Creating a dataframe with cutoff and conversion%
