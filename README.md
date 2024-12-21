# linearregression
# Simple Linear Regression Model for Height Prediction

This Jupyter Notebook demonstrates a simple linear regression model to predict height based on weight.

## Data and Libraries

- **Data:** The model uses a dataset (height-weight.csv) containing height and weight measurements.
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, and Statsmodels are utilized for data manipulation, visualization, and model building.


## Data Exploration and Visualization

The notebook begins by loading the dataset, displaying the first few rows, and creating a scatter plot of height vs. weight to visualize the relationship.  Correlation analysis and pairplots are used to further explore the data.


## Model Training and Evaluation

- The dataset is split into training and testing sets.
- Feature scaling (StandardScaler) is applied to the training and testing data.
- A linear regression model is trained on the scaled training data.
- The model's coefficients (slope and intercept) are displayed.

## Model Performance

The model's performance is evaluated using metrics such as:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R2) score
- Adjusted R-squared

The Ordinary Least Squares (OLS) method from Statsmodels is also used to provide a more detailed model summary.

## Prediction

Finally, the trained model is used to predict the height for a new weight value.
