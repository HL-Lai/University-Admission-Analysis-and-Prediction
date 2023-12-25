# University Admission Analysis and Prediction

This project aims to analyze and predict university admissions using various statistical models. The analysis is performed using R.

## Dataset

The dataset used is obtained from [Kaggle](https://www.kaggle.com/datasets/mohansacharya/graduate-admissions/data). It contains 7 variables which are considered important for being admitted into a University Master's programme.

## Preprocessing

The data is first loaded and any missing values are omitted. Outliers are identified and removed using the Interquartile Range (IQR) method.

## Model Building

Three models are built for the prediction:

1. Multiple Linear Regression
2. Ridge Regression
3. LASSO Regression

For each model, the performance is evaluated using Root Mean Squared Error (RMSE) and R-squared value.

## Results and Comparison

After analyzing the performance of the three models, it was found that Ridge Regression has the least Root Mean Squared Error (RMSE) and the highest R-squared value. Therefore, it can be concluded that Ridge Regression is the preferred model for University Admission Prediction.

Please refer to the R markdown file for the detailed code and analysis.

## Dependencies

- R
- dplyr
- ggplot2
- caret
- glmnet

## Usage

To run the R markdown file, you need to have R installed on your machine. You can then open the R markdown file in RStudio and run it.

## Acknowledgments

- Thanks to Kaggle for providing the dataset.
- Thanks to the R community for providing excellent resources and libraries.

## References
Acharya, M. S., Armaan, A., & S Antony, A. (2019). A Comparison of Regression Models for Prediction of Graduate Admissions, *IEEE International Conference on Computational Intelligence in Data Science 2019*. 1-5. 10.1109/ICCIDS.2019.8862140.