Goal: to apply basic ensemble methods in practice

Assignment Description:
In this homework, you need to solve a classification task predicting the presence of heart disease in patients. You must download the dataset manually from the website.
The target variable is HeartDisease, which takes the value 0 or 1 depending on the absence or presence of heart disease. (You can read more about the features in the dataset description on the website. For this assignment, it is not necessary to understand the medical details.)

Steps to complete the assignment:
1. Obtain the data and load it into your working environment (Jupyter Notebook or another tool).
2. Prepare the dataset for model training.
a) Convert categorical variables into numerical values. You may use pd.get_dummies or preprocessing.LabelEncoder. Try not to use loops for this task.
b) Create 1–2 plots of your choice. The visualization should be based on the dataset and be meaningful (the plot should allow you to draw a conclusion about some property of the dataset/class/feature).
3. Split the dataset into training and test subsets. Use 80% of the data for training and 20% for testing.
4. Train a decision tree on the training set using the following models:
a) tree.DecisionTreeClassifier
b) ensemble.RandomForestClassifier
5. For the test set, predict the target variable. Output the metrics for each model using metrics.classification_report.
6. Output the feature importances obtained from the model in step 4b as a bar chart. Sort the importances in descending order.
7. Train a bagging model based on the model from step 4a using ensemble.BaggingClassifier.
a) Repeat step 5.
8. Train a stacking model using the three models from steps 4a, 4b, and svm.LinearSVC, using ensemble.StackingClassifier.
a) Repeat step 5.
9. Formulate conclusions based on your work.
a) Compare the metrics of all built models.
b) Explain which model you consider the best and why.