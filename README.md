# My First Machine Learning Project

This project is my first experiment in machine learning where I built and evaluated a predictive model for solubility using linear regression and random forest algorithms.

## Overview

In this project, I aimed to predict the solubility of molecules using various molecular descriptors. I used the Delaney Solubility dataset which contains features like MolLogP, MolWt, NumRotatableBonds, and AromaticProportion to predict the LogS (log of the aqueous solubility).

## Data

The dataset used in this project is available as a CSV file. 

## Tools and Libraries Used

- Python
- Pandas
- Scikit-learn
- Matplotlib

## Steps

1. **Loading Data**: I loaded the dataset using Pandas DataFrame.
2. **Data Preparation**: Split the data into features (X) and target (y).
3. **Splitting Data**: Split the data into training and testing sets using train_test_split.
4. **Model Building**:
    - **Linear Regression**: Trained a linear regression model.
    - **Random Forest**: Trained a random forest regressor model.
5. **Model Evaluation**: Evaluated the models using Mean Squared Error (MSE) and R-squared (R2) scores.
6. **Model Comparison**: Compared the performance of the linear regression and random forest models.
7. **Prediction Results**: Visualized the predicted vs. actual solubility values.

## Model Performance

### Linear Regression

- **MSE (Train)**: 1.0075
- **R2 (Train)**: 0.7645
- **MSE (Test)**: 1.0207
- **R2 (Test)**: 0.7892

### Random Forest

- **MSE (Train)**: 1.0282
- **R2 (Train)**: 0.7597
- **MSE (Test)**: 1.4077
- **R2 (Test)**: 0.7092

## Conclusion

In this experiment, both linear regression and random forest models were able to predict the solubility of molecules to some extent. However, the linear regression model performed slightly better in terms of R2 score on the test set.

Feel free to reach out if you have any questions or suggestions! [Contact Me](mailto:uvindukodikara@gmail.com)

