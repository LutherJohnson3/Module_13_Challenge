This assignment consists of the following subsections:
* Split the data into training and testing sets.
* Scale the features.
* Create a logistic regression model.
* Create a random forest model.
* Evaluate the models.

**Split the Data into Training and Testing Sets**

1. Read the data from https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csvLinks to an external site. into a Pandas DataFrame.
2. In the appropriate markdown cell, make a prediction as to which model you expect to do better.
3. Created the labels set *(y)* from the “spam” column, and then create the features *(X)* DataFrame from the remaining columns.
   * A value of 0 in the “spam” column means that the message is legitimate. A value of 1 means that the message has been classified as spam.
4. Checked the balance of the labels variable *(y)* by using the *value_counts* function.
5. Split the data into training and testing datasets by using *train_test_split*.

**Scale the Features**

1. Created an instance of *StandardScaler*.
2. Fit the Standard Scaler with the training data.
3. Scaled the training and testing features DataFrames using the transform function.

**Create a Logistic Regression Model**

Employws knowledge of logistic regression to complete the following steps:

1. Fit a logistic regression model by using the scaled training data *(X_train_scaled and y_train)*. Set the random_state argument to 1.
2. Saved the predictions on the testing data labels by using the testing feature data *(X_test_scaled)* and the fitted model.
3. Evaluated the model's performance by calculating the accuracy score of the model.

**Create a Random Forest Model**

Employed knowledge of the random forest classifier to complete the following steps:

1. Fit a random forest classifier model by using the scaled training data *(X_train_scaled and y_train)*.
2. Saved the predictions on the testing data labels by using the testing feature data *(X_test_scaled)* and the fitted model.
3. Evaluated the model's performance by calculating the accuracy score of the model.
