# SC5002-Lab-2-
For linear regression and ridge regression project, we used a dataset from the UC Irvine Machine Learning Repository: Student Performance - UCI Machine Learning Repository

For the dataset, the file student-mat.csv is selected. It contains around 30 variables including student’s final Mathematics grades, making it ideal for multi-variable regression (refer to the website). The CSV file has a specific structure: all rows are segmented by “;” with the first row containing all variable names and the remaining rows containing corresponding data for each student.

Linear and ridge regression models are trained using all variables to predict students’ G3 (final math grade). K-fold cross validation is used to evaluate the models and reduce variance in performance estimates. Mean Squared Error and R2 of each model are used for comparison between linear and ridge regression model.

For the linear regression model, we found out that student’s past grades (G1, G2) and those having extra educational support in Mathematics is strongly associated with a higher final grade. Meanwhile, students who are in a relationship and have extra-curricular activities tend to result in a lower final grade. 

As the dataset has a lot of predictors, we performed ridge regression to penalise the model for being too complex. Comparing both models, ridge regression performed better in both metrics (Mean Squared Error, R2).
