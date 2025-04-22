# USA House Price Prediction - Regression Model

## Dataset
The project uses the `USA_Housing.csv` dataset. This dataset contains various features related to houses in the USA, such as:

- Avg. Area Income
- Avg. Area House Age
- Avg. Area Number of Rooms
- Avg. Area Number of Bedrooms
- Area Population
- Price
- Address

## Methodology

1. **Data Pre-processing:** The dataset is loaded and cleaned. This includes handling missing values, removing irrelevant features (like 'Address'), and potentially transforming categorical variables.
2. **Data Splitting:** The dataset is split into training and testing sets to evaluate the model's performance on unseen data. Typically, a 90/10 or 80/20 split is used.
3. **Feature Scaling:** Features are scaled using StandardScaler to ensure they have a similar range of values, which can improve model performance.
4. **Model Training:** Three regression models are trained:
    - Linear Regression
    - Decision Tree Regressor
    - Random Forest Regressor
5. **Model Evaluation:** The models are evaluated using metrics like Mean Squared Error (MSE) and R-squared. The model with the best performance is selected.
6. **Visualization:** Scatter plots are used to visualize the actual vs. predicted values and assess the model's accuracy.

## Results

The notebook presents the evaluation metrics for each model. You can compare the MSE and R-squared values to determine which model performed the best on the given dataset.

## Usage

1. **Import Libraries:** Import necessary libraries like pandas, scikit-learn, matplotlib, and seaborn.
2. **Load Data:** Load the `USA_Housing.csv` dataset into a pandas DataFrame.
3. **Pre-process Data:** Clean and transform the data as described in the notebook.
4. **Split Data:** Split the data into training and testing sets.
5. **Train Models:** Train the Linear Regression, Decision Tree, and Random Forest models.
6. **Evaluate Models:** Evaluate the models using MSE and R-squared.
7. **Visualize Results:** Create scatter plots to visualize the actual vs. predicted values.

## Dependencies

- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn

## Conclusion

This project demonstrates the application of machine learning for predicting housing prices. By exploring different regression models, you can find the best approach for this dataset. Further improvements can be made by experimenting with hyperparameter tuning and feature engineering.
