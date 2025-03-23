# Molecular Solubility Prediction using Linear Regression

## Overview
This project builds a machine learning model using Scikit-learn to predict the solubility of molecules. It employs a Linear Regression algorithm and utilizes Pandas for data manipulation and Matplotlib for visualization.

## Dataset
The dataset consists of molecular descriptors that influence solubility. It includes features such as molecular weight, logP, and other physicochemical properties that are used to predict solubility.


## Implementation
1. **Data Preprocessing**
   - Load the dataset using Pandas.
   - Handle missing values and normalize data if necessary.

2. **Exploratory Data Analysis (EDA)**
   - Use Matplotlib to visualize correlations between features and solubility.

3. **Model Training**
   - Apply Linear Regression from Scikit-learn.
   - Split the dataset into training and testing sets.
   - Train the model and evaluate its performance using metrics such as R² score and Mean Squared Error (MSE).

4. **Predictions**
   - Use the trained model to predict the solubility of new molecular structures.

## Results
The model achieves a reasonable prediction accuracy with the given dataset. Further improvements can be made using feature engineering or advanced regression models.

## Future Work
- Experiment with more complex models like Random Forest or Neural Networks.
- Feature selection to improve model performance.
- Deploy the model using a web-based interface.

## Acknowledgments
- Scikit-learn for providing easy-to-use ML tools.
- Pandas and Matplotlib for data handling and visualization.


