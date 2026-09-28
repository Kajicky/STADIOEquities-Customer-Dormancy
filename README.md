# STADIOEquities-Customer-Dormancy
Data Science capstone project – customer dormancy and churn prediction
# Publication 1 – Keramati et al. (2016)

## Title

Developing a prediction model for customer churn from electronic banking services using data mining

## Harvard Reference

Keramati, A., Ghaneei, H. and Mirmohammadi, S.M. (2016) ‘Developing a prediction model for customer churn from electronic banking services using data mining’, *Financial Innovation*, 2, 10.

## Link

https://link.springer.com/article/10.1186/s40854-016-0029-6

## Modelling

The study used a Decision Tree (DT) to predict customer churn from electronic banking services. The authors selected the decision-tree approach because it could handle numerical and categorical variables and produce understandable if–then rules describing the characteristics of churned customers.

## Preprocessing Techniques

The researchers detected and removed outliers, handled missing values using mean replacement and k-nearest-neighbour imputation (k=5), addressed class imbalance using bootstrap sampling, divided the data into 70% training and 30% testing sets, and applied forward selection and backward elimination for feature selection.

## Dataset Used

The study used a private dataset obtained from a bank's database. It contained 4,383 electronic-banking customers covering the period from March 2013 to March 2015. Variables included demographic characteristics, electronic-banking transaction activity, customer relationship length and customer complaints. A customer with no electronic-banking transactions for at least two years was classified as a churner.

## Key Takeaways

1. Customer transaction activity and engagement can be useful predictors of future customer disengagement.
2. Data cleaning, missing-value treatment and class-imbalance handling should be considered before modelling.
3. Interpretable models such as decision trees can help identify characteristics associated with customer dormancy and churn.
