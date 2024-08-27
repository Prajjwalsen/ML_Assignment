- Explanation of prajjwal ML Assginment 1:

- Step 1. *Import necessary libraries:

- pandas: For data manipulation and creation of DataFrames.
- numpy: For numerical operations (though not strictly necessary here, it's often used).
- train_test_split from sklearn.model_selection: To split the dataset into training and testing sets.
- LinearRegression from sklearn.linear_model: To create the linear regression model.
- mean_squared_error from sklearn.metrics: To evaluate the model's performance.

- Step 2. Create a sample dataset:

- A dictionary data is defined with YearsExperience and Salary.
The dictionary is then converted into a DataFrame using pd.DataFrame().

- Step 3. Define features and target variable:

- X represents the feature (independent variable) which is YearsExperience.
- y represents the target variable (dependent variable) which is Salary.

- Step 4. Split the data into training and testing sets:

- The train_test_split function is used to split the data into training (80%) and testing (20%) sets.
random_state=42 ensures that the split is reproducible.

- Step 5. Create and fit the linear regression model:

- An instance of LinearRegression is created.
The model is fitted using the training data with the fit method.

- Step 6. Make predictions on the test set:

- The predict method is used to make predictions on the test data (X_test).

- Step 7. Calculate Mean Squared Error:
- mean_squared_error computes the MSE between the actual values (y_test) and the predicted values (y_pred).

- Step 8. Print the results:
- Output the MSE to evaluate the model’s performance.
