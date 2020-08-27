

Using Machine learning models to predict cases and fatalties.

Link to the competition: https://www.kaggle.com/c/breast-cancer .

Breast Cancer is a serious problem across the globe. In that situation Kaggle came up with the dataset of predicting the cases.

About the dataset:

It contains 2 file - train.csv and test.csv These files holds data for 173 countries and daywise confirmed cases and fatalties of total 70 days. Also, these details are specified province region wise.

Now, firstly I looked at the dataset.

    There were no null values for Province_Region. So, there was no need to replaced by mean/median/mod values.

    The Date feature is of type Int64. So, there was no need converted columns that are ob type object to have the dataframes be only numerical type features.

After splitting the data into train and test, I have used the following models:

1.Linear Regression
2.Decision Tree Regressor
3.Gradient Boosting Classifier

Out of all I got the best score with Gradient Boosting Classifier.

Thanks for reading :-)
