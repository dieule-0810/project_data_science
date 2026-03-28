# Melbourne House Prices Prediction

## Problem
Predict house prices in Melbourne using regression models.

## Dataset
- Source: Kaggle Melbourne Housing Dataset
- 1350 rows, 21 columns
- Numeric and categorical features

## Workflow
1. Data cleaning: drop missing values
2. Feature engineering: select numeric features + encode categorical
3. Train model: DecisionTreeRegressor, random_state=1
4. Evaluate using MAE
5. Visualize: scatter plot actual vs predicted
6. Output CSV for submission

## Results
- Best model: Decision Tree
- MAE on validation: ~185,000 AUD
- Important features: Rooms, Bedroom2, Bathroom, BuildingArea, Regionname

## Usage
- Open `MelbourneHousePrices.ipynb` in Jupyter Notebook or VSCode
- Run all cells to reproduce results
