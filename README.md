# Wine-Quality

## Project Overview

The objective of this project is to predict wine quality based on various chemical properties like acidity, alcohol content, and residual sugar. The dataset is sourced from the UCI Machine Learning Repository and contains quality ratings for both red and white wines. The project involves data cleaning, exploratory data analysis (EDA), and the development of a machine learning model, specifically a Random Forest model, to make predictions.

## Dataset

The dataset used in this project consists of two CSV files:

`winequality-red.csv`: Contains chemical properties and quality ratings for red wines.
`winequality-white.csv`: Contains chemical properties and quality ratings for white wines.

You can find the link to the dataset files in the file named "Wine Data" in this repository.

## Exploratory Data Analysis (EDA)

Before building the model, I conducted an exploratory data analysis to understand the data better. This included:

- Analyzing the correlation between features and the target variable (quality).
- Visualizing the distribution of quality ratings and key features.
- Identifying and handling outliers.

The EDA results guided the choice of features and the machine learning model.

## Machine Learning Approach

I used a Random Forest model to predict wine quality. The model was trained on the cleaned and normalized data, and the performance was evaluated using R-Squared and Mean Squared Error (MSE).

The Random Forest model was chosen because it can handle non-linear relationships and interactions between features effectively.

## Results

The model was evaluated on both red and white wine datasets. The performance metrics are:

- **Red Wine:**
  - Mean Squared Error (MSE): 0.26
  - R-Squared: 0.50
- **White Wine:**
  - Mean Squared Error (MSE): 0.41
  - R-Squared: 0.46

These results suggest that the model can predict wine quality with reasonable accuracy, but there is room for improvement.

## Conclusion

This project demonstrates that machine learning can be used to predict wine quality based on chemical properties. While the model provides useful insights, wine quality is influenced by many factors, and incorporating additional data could improve the model's performance.
