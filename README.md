# AIProject


##Energy Load Forecasting Project


This project uses machine learning models to forecast energy demand based on various features, including renewable and fossil energy generation, energy prices, and temporal attributes like hour, day, and month.
##Objective:


Develop an end-to-end machine learning solution to predict total energy demand (load) using historical energy generation, pricing, and temporal data. The project will incorporate advanced feature engineering, train predictive models, and evaluate their effectiveness to derive actionable business insights for energy sector stakeholders.

#Data Overview and Preprocessing

##Data Source

The dataset contains historical energy price data, along with various features such as:
	•	Renewable Generation: The energy produced from renewable sources like wind and solar.
	•	Fossil Generation: Energy derived from fossil fuels like coal and gas.
	•	Market Features: Energy prices (actual and day-ahead), forecasted demand, and time-related variables such as the hour of the day, day of the week, and month.

#Feature Engineering:
	•	Aggregated Renewable and Fossil Features: Summed the contribution of various renewable and fossil energy sources into two key features (renewable_generation and fossil_generation).
	•	Temporal Features: Extracted hour, day_of_week, and month from timestamps to capture time-based variations.
	•	Renewable-to-Fossil Ratio: Created a derived feature to measure the relative contribution of renewable versus fossil energy.


	#Feature Scaling:
	•	Applied MinMaxScaler to normalize features for the Linear Regression model, ensuring uniform feature distributions.

##Future Simulation:

Simulates energy demand for the years 2024–2033.


##Model Evaluation:

Compares Linear Regression and Random Forest models to determine the best-performing model.
Interactive Visualization:
Visualizes trends in predicted energy demand.

##Key Files

final.py: Main script for training models, forecasting, and generating future predictions.
random_forest_model.pkl: Trained Random Forest model for predictions (or hosted externally).
scaler.pkl: Scaler used for feature normalization.
