Amazon Retail Demand Forecasting

A time-series forecasting project focused on analyzing retail sales patterns and predicting future demand using statistical and machine learning approaches.

Project Overview

This project explores daily sales data for a selected store and product category. The goal is to identify sales patterns, engineer time-based features, and compare forecasting models using a chronological evaluation strategy.

Objectives

* Explore historical retail sales trends and seasonality.
* Build lag-based and rolling statistical features.
* Train and compare forecasting models.
* Evaluate predictions using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
* Generate illustrative future sales forecasts.

Methods & Technologies

* Python
* Pandas and NumPy
* Matplotlib
* Scikit-learn
* Random Forest
* XGBoost (optional)
* Time-series cross-validation

Project Workflow

1. Data loading and preparation
2. Exploratory data analysis
3. Time-based feature engineering
4. Chronological train-test split
5. Model training and evaluation
6. Model comparison
7. Future demand forecasting

Dataset

The notebook is designed for the Store Sales - Time Series Forecasting dataset. The required training CSV must be downloaded separately and its path configured in the notebook.

Evaluation

Model performance is evaluated using MAE and RMSE on a chronological test set. Final scores and conclusions should be added after running the notebook with the dataset.

How to Run

1. Clone or download this repository.
2. Install the required Python packages.
3. Download the dataset and configure the CSV path.
4. Open amazon_retail_demand_forecasting.ipynb in Jupyter Notebook or VS Code.
5. Run the notebook cells in order.

Limitations

Results depend on the selected store, product family, dataset preparation, and evaluation period. Forecasts are exploratory and should not be treated as production-ready predictions without further validation.

Author

Abdelaziz Amr Mettwally
