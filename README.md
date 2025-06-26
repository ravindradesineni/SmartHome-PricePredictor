# SmartHome-PricePredictor
A machine learning project that leverages linear regression to estimate house prices based on key property features. This project emphasizes simplicity, clarity, and real-world interpretability using foundational regression modeling.

## Overview

The purpose of this project is to apply a basic regression technique to estimate the price of a house based on various factors. The model is trained using historical housing data and is evaluated using key metrics like MAE, MSE, and R².

---

## Tools & Libraries

* **Python**
* **Pandas** for data loading and manipulation
* **Matplotlib** for visualization
* **Scikit-learn** for preprocessing, model training, and evaluation

---

## Project Steps

### 1. Data Import & Preprocessing

* The dataset is loaded and explored.
* Categorical variables are converted to numeric format using `LabelEncoder`.
* Features and target (`price`) are separated.

### 2. Model Training

* The dataset is split into training and testing sets (80:20).
* A linear regression model is trained using `LinearRegression()` from scikit-learn.

### 3. Prediction and Evaluation

* Predictions are made on the test data.
* Performance is evaluated using:

  * **Mean Absolute Error (MAE)**
  * **Mean Squared Error (MSE)**
  * **R² Score**

---

## Result Visualization

To visually assess the model’s performance, a scatter plot was generated comparing the predicted house prices to the actual prices. Each point represents a prediction–actual pair. The closer the points lie to the diagonal reference line, the more accurate the model’s predictions are. This plot provides a quick visual cue on how well the model is performing across the test data.

---

## Output

The model’s predictions are compiled into a CSV file that contains both the actual and predicted prices for the test data. This file helps in further analysis, verification, or reporting, making it easy to examine how well the model generalizes to unseen data.

---

## How to Use

1. Clone or download the repository.
2. Upload the dataset named `dataset.csv` to your notebook or project folder.
3. Run the notebook or Python script.
4. View the scatter plot and download the predictions.

---

## Future Improvements

* Try other regression algorithms like Ridge or Lasso
* Add feature importance visualizations
* Implement normalization or feature scaling
* Perform hyperparameter tuning
