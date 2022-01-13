# Capstone_2
This project is about the prediction of default loans. A dataset from Lending Club uploaded to Kaggle was used.
The original data has 151 columns, and we believe not all of them have noticeable impact to our target variable.
So we studied the correlation between those columns and the target column, and features with poor correlations are removed.

The original data has about 80% points for fully paid loans and only about 20% on default loans. So the data point is not balanced.
about 60% of points for fully paid loans are removed to make the data balanced.

A few models have been tried, such as KNN, decision tree, logistic regression, and random forest. It is found that 
the random forest gives the best performance. An overall 97% prediction accuracy could be reached.

It is also interesting to find that if you want the model to be more successful in predicting default loans,
you can train the model with a dataset which contains more data points for default loans. This could be very useful for 
the loan company as they have the choice to get more accurate prediction on a specific class. 
