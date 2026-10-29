# CodeAlpha Task 3 - Car Price Prediction

Part of the CodeAlpha Data Science Internship (October Batch).

## Goal
Predict the selling price of a used car using details such as year, present price, kilometres driven, fuel type, seller type, transmission, and number of owners.

## Steps
1. Loaded the car dataset and checked its structure
2. Removed duplicate and missing values
3. Separated features (X) and target (Selling_Price)
4. Applied One-Hot Encoding to categorical columns
5. Split the data into training and testing sets
6. Trained a Random Forest Regressor
7. Evaluated the model using MAE, RMSE, and R2 score
8. Plotted actual vs predicted prices

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## How to Run
Open `car_price_prediction.ipynb` in Google Colab, upload `car_data.csv` when asked, and run all cells from top to bottom.
