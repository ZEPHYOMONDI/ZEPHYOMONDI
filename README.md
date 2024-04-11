- 👋1. **Import libraries:** Pandas for data manipulation, scikit-learn for train-test split, linear regression, and performance metrics.
2. **Load data:** Replace "house_pricing_data.csv" with your actual data file path.
3. **Exploratory Data Analysis (EDA):**
   - Check for missing values using `isnull().sum()`.
   - Check data types using `dtypes`.
   - Analyze the distribution of house prices using `data["price"].hist()`.
   - Analyze the relationship between features and house prices using scatter plots or heatmaps (not included in the code).
4. **Split data:** Split features (X) and target variable (y) using `train_test_split`. Here, 80% of the data is used for training and 20% for testing.
5. **Create a linear regression model:** Create a linear regression model using `LinearRegression`.
6. **Train the model:** Train the model using `model.fit(X_train, y_train)`.
7. **Make predictions:** Predict house prices on the testing set using `model.predict(X_test)`.
8. **Evaluate the model performance:** Calculate MSE, MAE, and RMSE using the `mean_squared_error`, `mean_absolute_error`, and `np.sqrt(mse)` functions, respectively. Print the results.
