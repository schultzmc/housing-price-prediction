# Housing Price Prediction
A regression and machine learning analysis predicting housing prices from property characteristics.

## Abstract
This project builds and compares multiple predictive models including linear regression, penalized regression, decision trees, gradient boosting, and random forest to predict housing prices using the Housing.csv dataset. The data is split into training and test sets, with model performance evaluated to determine which approach best captures the relationship between property features and price.

## Files
- Project.Rmd : R Markdown file containing data setup, model training, and evaluation
- Housing.csv : housing dataset used for training and testing the models

## How to Run
Open Project.Rmd in RStudio and knit to PDF or HTML. Requires the following R packages: readr, glmnet, tree, gbm, randomForest.

## Methods
- Train/test split (100 observations helf out for testing, seed = 123)
- Linear regression as a baseline model
- Penalized regression
- Decision trees
- Gradient boosting
- Random forest

## Results
See Project.Rmd for full model comparisons and evaluation metrics across all five approaches.

## Author
Madison Schultz
