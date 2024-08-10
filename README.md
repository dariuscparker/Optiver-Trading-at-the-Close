# Optiver - Trading at the Close

## Overview
A competition that challenges participants to develop a predictive model for the closing price movements of Nasdaq-listed stocks using order book and closing auction data, focusing on the final ten minutes of trading

## Key Features
- **Data Exploration**: Utilizes general data exploration techniques to understand the intricacies of the dataset.
- **Advanced Modeling Techniques**: Includes comparisons and ensembling of several machine learning models like LightGBM, XGBoost, CatBoost, and neural networks using TensorFlow/Keras.
- **Feature Engineering**: Demonstrates the creation of new features to improve model performance significantly.
- **Performance Metrics**: Employs Mean Absolute Error (MAE) for model evaluation, focusing on minimizing prediction errors in a highly volatile environment.

## Data
- Due to GitHub storage limits, the dataset used in this project is not stored here. It is recommended to run the notebook in a Kaggle environment. The dataset involves several features critical to predicting stock movements, including price imbalances, weighted average price (WAP), and trading volumes.

## Highlights
- The project utilizes a blend of technical indicators and machine learning models to predict stock price movements effectively.
- Detailed analysis of feature importance and correlations to refine the modeling approach, reducing overfitting and improving predictive accuracy.
- Application of various data preprocessing techniques such as handling missing values and outliers, which were crucial for improving model performance.

## Results
- The models were able to achieve a competitive Mean Absolute Error on the provided test sets, with comprehensive evaluations using both training and validation datasets.
- Insights gained from the competition highlight the importance of preprocessing steps and the challenges associated with time series forecasting in high-frequency trading environments.

## Running the Notebook
The notebook is best run in a Kaggle environment where the necessary compute resources and data are readily available. You can access the notebook via the following link:
[Optiver Model Comparison and Ensemble](https://www.kaggle.com/code/deeparker/optiver-model-comparison-and-ensemble)

## Feedback and Contributions
Feedback and contributions are highly appreciated. If you have any suggestions or insights, please feel free to reach out or contribute to improving the models and techniques used in this analysis.
