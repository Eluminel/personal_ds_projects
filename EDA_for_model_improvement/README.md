Goal:
To study the application of Exploratory Data Analysis (EDA) methods for improving the performance of machine learning models.
Task Description:
In this assignment, you need to improve the RMSE and R² metrics of a linear regression model by performing data preprocessing and exploratory data analysis.
The dataset to be used is California Housing from the sklearn.datasets library.
The target variable is MedHouseVal.
Workflow Steps:
Load the data and import it into your working environment (Jupyter Notebook or another IDE).
Check for missing values in the dataset. Remove them if any are found.
Split the dataset into training and test subsets:
80% for training
20% for testing
Build a linear regression model and calculate the RMSE and R² metrics on both the training and test sets.
Plot the distribution of the target variable. Make conclusions — are there any outliers?
Compute and display the correlation matrix.
Ensure that the matrix cells are color-coded and display the numerical correlation values.
a. Make conclusions based on the results.
b. Remove features based on correlation values and your conclusions.
c. Repeat steps 3 and 4 using the updated data.
Investigate the remaining features for outliers.
a. Remove outliers if any are detected.
b. Repeat steps 3 and 4 on the modified data.
Apply mathematical transformations to several selected features — for example:
take the logarithm,
square the values,
or take the square root.
a. Repeat steps 3 and 4 on the transformed data.
Formulate conclusions based on your work:
a. Briefly describe what transformations were applied to the data.
b. Compare the metrics of all models (preferably in a table of the form:
| Model | RMSE | R² | Features used and transformations applied |).
c. Write your opinion on how well the models performed the task.