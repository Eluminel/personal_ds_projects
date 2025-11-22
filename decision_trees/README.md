Goal: 
To study the application of decision trees in a regression task

Assignment Description:
In this homework, you need to solve a regression problem. As a dataset, use the California housing data from the sklearn.datasets library.
You can also download the dataset via the link provided.
The target variable is MedHouseVal. You can read information about the dataset features by running the following code:
print(fetch_california_housing().DESCR)
Using the obtained data, build a regression model and a decision tree.

Steps to complete the assignment:
1. Obtain the data and load it into your working environment (Jupyter Notebook or another environment).
2. Conduct initial data analysis:
    a. Check the data for missing values and remove them if any are found.
    b. Normalize one of the features.
3. Split the dataset into training and test subsets. Use 80% of the data for training and 20% for testing.
4. Train a regression model on the training set.
5. For the test set, predict the target variable and compare it with the true values by calculating the model’s accuracy. Use the built-in score function for this.
6. Train a decision tree on the training set.
a. Repeat step 5 for the decision tree model.
b. Visualize part of the decision tree. Ensure the plot is readable. See examples of visualization at the provided link.
7. Optimize the depth of the tree (max_depth). Also, optimize one more model parameter of your choice.
a. Repeat step 5 for the optimized model.
8. Draw conclusions based on your work:
a. Compare the accuracy of the two models.
b. Share your opinion on which tasks are better suited for the models trained in this assignment. Discuss their advantages and disadvantages.
