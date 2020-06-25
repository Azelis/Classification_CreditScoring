## Classification for Credit Scoring

This project is a part of coursework of Data Mining for Credit Scoring from University of Southampton. **It is not completed** since this version is a fast one, the completed will be **updated**, where model can be improved by:
- Grid Search to find the most optimal parameters (proper hyperparameters)
- Resampling data to have same samples size of dependent variable in OTHER WAY
- Remove variables based on feature selection either by Information Value
- Scale data to have similar ranges of values
- Create more variables

A project to create data mining model which helps to determine if a customer will be delinquent in upcoming 2 years after 90 days past.
<br>
List of models used in analysis (classification):
- Logistic Regression
- Decision Tree
- Random Forest
- Stochastic Gradient Descent
- Extreme Gradient Boosting (Best Performance)
- k-nearest neighbors

### Content
1. Data Exploration
2. Data Clearance
3. Building and Selecting the Model
4. Performance of Model
<br>
Project mainly used scikit-learn libraries including given suggestion how to improve credit scoring model. 
Additionally, using cross validation to determine more accurate score which is roc_auc as a final accuracy measure.
Given graph represents that model has potentiality to be good:
<img width="386" alt="Screen Shot 2020-06-25 at 02 40 54" src="https://user-images.githubusercontent.com/37827791/85644064-d6e1fd00-b68d-11ea-8891-44f1ed6965be.png">


**Cheatsheet** for ML:
![ml_map](https://user-images.githubusercontent.com/37827791/85572230-b6358b00-b62c-11ea-81dd-a179d216b258.png)
