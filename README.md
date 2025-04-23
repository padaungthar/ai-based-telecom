# Mini-Project: AI-Based Signal Strength Prediction for FWA CPE Placement
## Goal:
Build a simple machine learning model that predicts signal strength (RSSI or SINR) based on environmental features to suggest optimal placement for a CPE device.

## Step-by-Step Plan
### Step 1: Collect or Simulate Data
  You’ll need a dataset with features like:

  > Distance from tower (in meters)

  > Line-of-sight (boolean)

  > Obstruction types (e.g., wall, glass, tree)

  > Elevation

  > Device height (e.g., rooftop or window level)

  > Signal strength (RSSI or SINR) — target variable

### Step 2: Build the ML Model

Use Python with libraries like pandas, scikit-learn, and matplotlib.

  - Preprocess data (normalize, encode categories).

  - Train a regression model:

    . Random Forest Regressor

    . Gradient Boosting Regressor

    . Optional: try a small Neural Network using TensorFlow/Keras

  - Evaluate with R² Score, MAE, etc.
