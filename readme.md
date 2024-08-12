# Wine Quality Prediction Using Machine Learning

## Overview
This project uses machine learning to predict wine quality from physicochemical properties, focusing on datasets of red and white wines. The analysis employs XGBoost and Random Forest models to classify and predict wine quality, providing actionable insights for improving wine production and marketing strategies.

## Datasets
The datasets include detailed measurements of wine properties:
- `winequality-red.csv`: Physicochemical and quality data for red wine.
- `winequality-white.csv`: Similar data for white wine.

Attributes in each dataset include fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, and a quality rating.

## Files
- `winequality-red.csv` and `winequality-white.csv`: Dataset files.
- `winequality.names`: Attribute descriptions.
- `XGBoost.ipynb`: XGBoost model analysis.
- `(4)XGBoost.ipynb`: Enhanced XGBoost analysis with parameter tuning.
- `(w)randomforest.ipynb`: Random Forest analysis for white wine.
- `randomforest.ipynb`: Random Forest analysis for red wine.
- `regression.ipynb`: Regression models for predicting wine quality.

## Insights from Machine Learning Models
- **XGBoost Model:** Revealed the significance of alcohol level, sulphates, and acidity in predicting wine quality. 
- **Random Forest Red Wine:** Showed strong predictive capabilities especially for medium and high-quality wines, with alcohol and sulphates as the most influential features.
- **Random Forest White Wine:** Highlighted the importance of volatile acidity and sulfur dioxide levels, providing insights into quality factors specific to white wine.
- ****Regression Analysis**:** Explored the relationship between the continuous variables of the datasets and wine quality, providing a different perspective on prediction beyond categorical quality levels.