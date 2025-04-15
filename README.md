# ANALYZING-NYC-FERRY-OPERATIONS
The NYC Ferry system operates a network of routes, transporting passengers between different locations across the city. Our goal is to  understand patterns in ferry usage and recommend operational changes to increase efficiency, optimize resources.

📊 Features
Temporal features: Year, Month, Day, Hour

Route information

Direction of travel

Type of day (e.g., weekday, weekend, holiday)


🧠 Model
Utilizes XGBoost Regressor with the following parameters:

n_estimators=300

learning_rate=0.05

subsample=0.8

colsample_bytree=0.8

max_depth=6

random_state=42

📈 Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)
