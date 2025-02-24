# ECGR_5105_001_Assignment_1
This repository is the solutions of assignment 1 of ECGR 5105

# Problems Description

## Problem 1 (50 points)

Develop a code that runs linear regression with a gradient decent algorithm for each explanatory variable in isolation. In this case, you assume that in each iteration, only one explanatory variable (either x1, x2, or x3) is explaining the output. You need to do three different training, one per each explanatory variable. For the learning rate, explore different values between 0.1 and 0.01 (your choice). Initialize your parameters to zero (theta to zero).

Report the linear model you found for each explanatory variable.
Plot the final regression model and loss over the iteration per each explanatory variable.
Which explanatory variable has the lower loss (cost) for explaining the output (Y)?
Based on your training observations, describe the impact of the different learning rates on the final loss and number of training iterations.

## Problem 2 (50 points)

This time, run linear regression with gradient descent algorithm using all three explanatory variables. For the learning rate, explore different values between 0.1 and 0.01 (your choice). Initialize your parameters (theta to zero).

Report the final linear model you found the best. 
Plot loss over the iteration.
Based on your training observations, describe the impact of the different learning rates on the final loss and number of training iterations.
Predict the value of y for new (x1, x2, x3) values: (1, 1, 1), (2, 0, 4), and (3, 2, 1)


## Project Structure
- `ECGR_5105_Assignment_1_Liyuan.ipynb` – Jupyter Notebook containing the full implementation and analysis.
- `README.md` – Project documentation (this file).


## Implementation Details
- **Dataset:** CSV file with three explanatory variables (`x1`, `x2`, `x3`) and one target variable (`y`).
- **Algorithm:** Gradient Descent for optimizing the linear regression model.
- **Training:** Each feature is trained in isolation, resulting in three separate models.
- **Evaluation:** Loss is analyzed across different learning rates, and the best feature for predicting `y` is identified.



## Author
- **Liyuan**
- Course: ECGR 5105 – Machine Learning
