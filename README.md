# AIProject
Energy Load Forecasting Project
This project uses machine learning models to forecast energy demand based on various features, including renewable and fossil energy generation, energy prices, and temporal attributes like hour, day, and month.
Objective:
Develop an end-to-end machine learning solution to predict total energy demand (load) using historical energy generation, pricing, and temporal data. The project will incorporate advanced feature engineering, train predictive models, and evaluate their effectiveness to derive actionable business insights for energy sector stakeholders.
Features
Energy Load Forecasting:
Predicts total energy demand using historical data.
Future Simulation:
Simulates energy demand for the years 2024–2033.
Model Evaluation:
Compares Linear Regression and Random Forest models to determine the best-performing model.
Interactive Visualization:
Visualizes trends in predicted energy demand.
Technologies Used
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Streamlit
Joblib
Key Files
final.py: Main script for training models, forecasting, and generating future predictions.
random_forest_model.pkl: Trained Random Forest model for predictions (or hosted externally).
scaler.pkl: Scaler used for feature normalization.
