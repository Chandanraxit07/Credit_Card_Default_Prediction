you can access the python notebook using this link
https://github.com/Chandanraxit07/Credict_Card_Default_Prediction/blob/main/Copy_of_Credit_Card_Default_Prediction_Capstone_Project.ipynb


# Credict Card Default Prediction
We'll be analyzing credit card data. Trying to predict patterns that lead to defaulting on credit. Various Machine Learning methods will be applied to the dataset. We will also try to derive some features to help our predictions. The 'real world' applications of these methods will be considered throughout our report. Balancing accuracy and the rate of true positive predictions will be the main consideration throughout the report.
# Data Summary
● X1 - Amount of credit(includes individual as well as family 
credit)

● X2 - Gender

● X3 - Education

● X4 -Marital Status

● X5 - Age

● X6 to X11 - History of past payments from April toSeptember

● X12 to X17 - Amount of bill statement from April toSeptember

● X18 to X23 - Amount of previous payment from April to 

September

● Y - Default payment

# Challenges

● Understanding the columns.

● Feature engineering.

● Getting a higher accuracy on themodels

# Conclusion

● XGBoost provided us the best results giving us a recall of 85 
percent(meaning out of 100 defaulters 85 will be correctlycaught 
by XGBoost)

● Random Forest also had good score as well but leads to overfit 
the data.

● Logistic regression being the least accurate with a recall of 79
