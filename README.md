### Fifa
Group Project Week 2 Bootcamp

##1: Understanding the data

In this first step we have been checking and understanding what information we had in each column, which variable would be the best to create the model with machine learning. 

##2: cleaning the data

Once we had this clear, we started to clean our data frame. For this we have dropping unnecesary columns, treated unnecesary errors, transformed some columns, changed data types or treated nans.

##3: Features selection

Once we have our new data frame ready, we have moved on to check the correlation between our target and the rest of the selected data.

##4: Training the model

With this checked, and making some further adjustments to our selected data, we move on to training the model. We have done the separation of X and Y, then separated the numerical part from the categorical part, standardised both parts, and concatenated it all together again. 

Finally in this section we have entered the model with our test data.

##5: Validating the model

In this section we have validated the accuracy of the model with R2, MSE and RMSE. 

##6: Save my Model with pickle and Loaded from disk

Once we were satisfied with the results of the validation, we went on to save the model and test load it, to see that it worked correctly. 

##7: Test the model with other data set¶

We have loaded the new data set, and proceeded to read it, clean it up with our previously created function, split x/y, split the numerical data from the categorical data, standardised both, concatenated them back into a single data frame, and finally, tested this new data frame on our previously saved model to see what results it gives us. 

##8: Validating the model again with the second data test

Finally, we have rechecked the results with R2, MSE and RMSE, in our new data frame, and we have found that it works and returns the expected results, so we can start using our model to predict.  
