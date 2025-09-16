Goal: apply methods for assessing data quality in practice.
Task description:
Perform data cleaning using the Titanic passengers dataset. 
The dataset can be downloaded from the provided link or found in the lesson materials. 
Train a classification model on the given data, with the target feature Survived 
(1 – passenger survived, 0 – passenger died). 
Train the model on raw data and calculate the quality metric. 
Perform data cleaning. Train the model again on the processed data and calculate the quality metric. 
Compare the results. The metric value should improve.

Workflow steps:

1. Load the dataset.
2. Remove all missing values and categorical variables. Train the model. 
Select and calculate a quality metric.
3. Load the complete dataset again.
4. Remove features that are logically unnecessary for building the model. Justify your choice.
5. Check the dataset for missing values.
a) Calculate what percentage of data will be lost if missing values are simply removed.
b) Fill missing values: with mean value; with a constant; with a special category indicating missing value; with a random number. 
Use the appropriate method for different features. Not all methods are required.
6. Convert categorical variables into numerical ones. Try to avoid using loops for this task.
7. Check the dataset for outliers.
a) Remove outliers if you consider it reasonable. Justify your choice.
8. *Plot 1–2 graphs of your choice. 
The visualization should be based on the dataset and provide useful insights (the graph should allow conclusions about the dataset/class/feature).
9. *Try mathematically transforming the Age feature.
10. Train the same model as in step 2 on the transformed data. Calculate the same metric as in step 2.