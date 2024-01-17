# Title: Exploring Gender Differences in School Enrollment

## Introduction:
We will examine how boys and girls are distributed across different grade levels and uncover any variations in enrollment. By analyzing a comprehensive dataset from various schools, we aim to gain insights that promote fairness and equality in education. 


## Dataset Info
The data shows the assessment of over 1,000 primary schools on learning in Uganda across 112 districts covering a period from 2010-2015. (http://catalog.data.ug/dataset/uwezo-school-data-2010-2015)

It groups pupil enrollment across the different classes from P1 to P7 by gender.


## Results and Findings:

### Linear regression: 
- R-squared score: 0.7773644327276159
- Root Mean Squared Error (RMSE): 19.429361445215857


### KNN:
- R-squared score (KNN): 0.736001497840642
- Root Mean Squared Error (RMSE): 21.15738484154725

### Regression Tree:
- R-squared score (Regression Tree): 0.6171373533012638
- Root Mean Squared Error (RMSE) : 25.47902194883242



## Conclusion:
We will implement the linear regression model for our dataset. 

### Justification:

#### R-squared score: 
The R-squared score, measures the proportion of the variance in the dependent variable (y) that can be explained by the independent variable(s) (X) in the model. It ranges from 0 to 1, where 0 indicates that the model does not explain any of the variance in the data, and 1 indicates that the model perfectly explains all the variance.


The linear regression model has the highest R-squared score of 0.8045, indicating that approximately 80.45% of the variance in girls enrollment can be explained by the boys enrollment. This suggests that the linear regression model captures a stronger relationship between the variables compared to the other KNN and Regression Tree models that have 75.62% and 76.82% respectively.

#### RMSE: 
Root Mean Squared Error is a measure of the average deviation between the predicted values and the actual values. 


The linear regression model has the lowest RMSE value of 20.1775. A lower RMSE indicates that the model's predictions are, on average, closer to the actual values. In this case, the linear regression model has the smallest average deviation from the actual girls enrollment numbers compared to the other KNN and Regression Tree models that have 22.5292 and 21.9699 respectively.

Considering both the R-squared score and RMSE, the linear regression model outperforms the KNN regression and regression tree models in terms of capturing the relationship between boys and girls enrollment and providing more accurate predictions.


## Relevant Insights
Relationship between boys and girls enrollment: 
The linear regression model's R-squared score indicates the proportion of variance in girls enrollment that can be explained by boys enrollment. Since the R-squared score is oderately high, it suggests a strong relationship between boys and girls enrollment. This means that as the number of boys enrolled in P1 increases or decreases, there is a corresponding increase or decrease in the number of girls enrolled in the same class.
