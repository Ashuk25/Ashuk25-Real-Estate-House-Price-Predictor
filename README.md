# Real Estate House Price Prediction
## Problem Term Down

1) We have give dataset of house prices with some features like no. of bathrooms, no. of bedroom, etc.

2) Our task is to create a model which will predict the price for any house by looking at features.

3) While learning about Machine Learning it is best to actually work with real-world data. not just artificial datasets.

4) There are hundreds of open datasets to choose from.
## Getting Started

1) The first question i should ask Mr. X is what is the bussinees objective and end goal? How will real estates behefit from the model?

2) Mr. X tells me that real estates ill use this model to predict house prices in a given area and will invest in the area if its undervalued.

3) Next question i should ask to Mr. X is how does the current solution look like? The answer is - Manual experts who analyze the features.

4) The predictions made by so called " experts" are not very good (error rate is 25%) that is why real estates PVT LTD is coming to me.

## Finding The Type Of Model To Build

1) Supervised, unsupervised or Reinforcement learning?

2) Classification task or Regression task?

3) Batch learning or online learning techniques?

# Selecting a Performance Measure

1) A typical performance measure for regression problems is the Root Mean Square Error(RMSE). 
RMSE(X,h) = root(1/mi*sum(h(x(i)-y(i))2))
2) RMSE is generally the preferred performance measure for regression taska, so we choose it for this particular problem we are solving for real estates Pvt. Ltd.
3) Other performance measures include Mean Absolute Error, Manhattan norm, etc but we will use RMSE for this problem.
# Checking The Assumptions
1) It is very important for me to check for any assumptions I might have made and correct them before launching the ml system.
2) For example, I should make sure that the team needs the price and not the categories like expensive, cheap, etc.
3) If latter is the cases. formulating the problem as a regression task will be counted as a big mistake.
4) I talked to the real estate team members and ensured that they are aware of all the assumptions.

# Setup :

## Run the commands

- pip3 install --upgrade pip
- pip3 install --upgrade jupyter matplotlib numpy pandas scipy scikit-learn
- jupyter notebook

## Visit to below link for data

- https://archive.ics.uci.edu/ml/machine-learning-databases/housing/

## Download below files from above link

- housing.data
- houding.names

## Models 

### Decision tree:

    Mean:  4.618150080285071
    Standard deviation :  1.5286947108202538

### Linear Regression

    Mean:  5.026691729826505
    Standard deviation :  1.0559260837947781

### Random Forest Regressio
    
    Mean:  3.317294704549673
    Standard deviation :  0.7190966217403666


