# Energy Load Forecasting Project

## Objective:
The goal of this project is to develop an end-to-end machine learning solution to predict total energy demand (load) based on historical energy generation, pricing, and temporal data. The solution will incorporate advanced feature engineering, model training, and evaluation, providing actionable business insights for stakeholders in the energy sector.

---

## Data Overview and Preprocessing

### Data Source:
The dataset includes historical data related to energy demand and supply, covering the following features:

- **Renewable Generation:** Energy produced from renewable sources (e.g., wind and solar).
- **Fossil Generation:** Energy derived from fossil fuels (e.g., coal, gas).
- **Market Features:** Includes actual and day-ahead energy prices, forecasted demand, and temporal variables like hour, day of the week, and month.

### Feature Engineering:
Several advanced feature engineering techniques have been applied:

- **Aggregated Renewable and Fossil Features:** Summed contributions from various renewable and fossil energy sources into two primary features: `renewable_generation` and `fossil_generation`.
- **Temporal Features:** Extracted key time-based features such as `hour`, `day_of_week`, and `month` from timestamps to capture time-dependent variations in energy demand.
- **Renewable-to-Fossil Ratio:** Created a derived feature to evaluate the relative contribution of renewable versus fossil energy.

### Feature Scaling:
- **MinMaxScaler:** Normalized features to ensure uniform distribution across the dataset, making them suitable for models like Linear Regression.

---

## Future Simulation
This project includes a simulation of energy demand for the years 2024–2033, using trained models to predict future energy demand based on historical trends.

---

## Model Evaluation:
The models compared in this project include:

- **Linear Regression:** A baseline model for predicting energy demand.
- **Random Forest:** A more complex model to assess non-linear relationships and interactions in the data.

The performance of both models is evaluated based on predictive accuracy, and the best-performing model will be selected for forecasting.

---

## Interactive Visualization
An interactive visualization is used to display trends in predicted energy demand, providing insights into how the demand is expected to evolve over time.

---

## Key Files

- **`final.py`:** The main script for training machine learning models, performing forecasting, and generating future energy demand predictions.
- **`random_forest_model.pkl`:** A serialized Random Forest model used for predictions.
- **`scaler.pkl`:** A serialized scaler object for normalizing features before making predictions.

---


