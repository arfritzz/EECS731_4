# EECS731_4
Major Leagues


The goal of this project was to take data from the NFL and fit a regression model. 

First, I used feature engineering to encode the teams and add a column for the difference in scores. 

Then, I tried both linear regression and random forest regression.  Linear regression overfit the data and random forest regression gave a cross-validation score of around 0.5. 

Ultimately, I used the random forest model to write a predict function to predict the score of the two teams. 
