**House Price Prediction**

This repository contains a project that predicts house prices based on area size using a machine learning model. The project works with two Excel datasets: 

1. homeprices.csv: This dataset contains historical data of house prices and corresponding areas.
2. areas.csv: This dataset contains the areas for which we want to predict house prices.

**Workflow**

- **Data Loading**: We first load the `houseprices.csv` dataset, which contains house prices and corresponding area sizes. This dataset is used to train the prediction model.
- **Model Training**: A machine learning model is trained using this dataset to learn the relationship between area size and house price.
- **Prediction**: Once the model is trained, we load the `areas.csv` dataset, which contains area sizes for which we want to predict house prices.
- **Saving Results**: The predicted prices are then saved in a CSV file named `areas_prices.csv`, which includes the predicted house prices for each area size.

**Features**

- Predict house prices based on area size.
- Uses linear regression (or any suitable machine learning model) to make predictions.
- Outputs the results in a CSV format for easy interpretation.

**How to Use**

1. **Run the project**: Load the datasets and execute the model to predict house prices for the given areas.
2. **Results**: The predictions will be saved in the `areas_prices.csv` file.


### Requirements

- Python
- Pandas
- Scikit-learn (for model training)

