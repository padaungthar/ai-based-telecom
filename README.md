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
  
    > Random Forest Regressor

    > Gradient Boosting Regressor

    > Optional: try a small Neural Network using TensorFlow/Keras

  - Evaluate with R² Score, MAE, etc.

### Step 3: Visualize Predictions

Create a heatmap or 2D grid showing signal strength predictions for different locations in a home or neighborhood.

  - Use matplotlib or seaborn for plotting.
  - Simulate different scenarios (e.g., window vs. rooftop placement).

### Step 4: Build a Simple Recommendation System

Let the user input:
  - Their location relative to the tower
  - Obstruction type
  - Device placement height

## Tools You'll Use

- Python (Jupyter Notebook or VS Code)
- scikit-learn
- pandas / numpy
- matplotlib / seaborn
- Optional: TensorFlow or PyTorch (for deeper models)
