# Yulu-Bike-Sharing-Demand-Prediction

## Project Overview
Bike demand prediction is a crucial challenge for bike rental companies, as accurately forecasting demand helps optimize inventory management and pricing strategies. In this project, I developed a **supervised regression machine learning model** to predict bike demand for a given time period.

## Dataset
The dataset, sourced from a bike-sharing company, contains:
- Number of bikes rented
- Time and date details
- Weather conditions
- Seasonality factors
- Special conditions like holidays and working/non-working days

## Data Preprocessing
- **Handling Missing Values**: Filled or removed missing data to ensure consistency.
- **Feature Engineering**: Created new features based on date-time information and weather conditions.
- **Data Splitting**: Divided the dataset into **training** and **test** sets.

## Model Training and Evaluation
Multiple **machine learning models** were trained and tested to find the best-performing one. The final selected model was evaluated using the following metrics:

- **Mean Absolute Error (MAE):** 2.58
- **Root Mean Squared Error (RMSE):** Computed for error magnitude analysis
- **R-squared (R²) Score:** 0.88 (indicating high prediction accuracy)

## Key Insights
- **Temperature, weather conditions, and seasonality** were the most significant factors affecting bike demand.
- The model successfully captured demand patterns, leading to more accurate predictions.

## Technologies Used
- **Python** (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
- **Machine Learning Models** (Linear Regression, Random Forest, Gradient Boosting)
- **Google Colab**


For any questions, feel free to reach out!

