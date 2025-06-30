# Movie-Ratings-and-Revenue-Prediction

This project uses machine learning to predict two key success metrics for movies: box office revenue and user vote average (rating). It leverages the "TMDB 5000 Movie Dataset" and a multi-output regression model to make its predictions.

The script performs a complete machine learning workflow:
1. Data loading and merging
2. Data cleaning and preprocessing
3. Feature engineering
4. Model training and evaluation
5. Visualization of results

Dataset:
This project requires the TMDB 5000 Movie Dataset from Kaggle.

The script will run through all the steps and print the following to the console:
Data loading and cleaning progress.

Model training status.

Evaluation Metrics (RMSE, MAE, R-squared) for both revenue and rating predictions.

Feature importances, showing which features were most influential for each prediction.

Finally, it will display several plots to visualize the model's performance, including:
Actual vs. Predicted Scatter Plots for both revenue and rating.

Residual Plots to analyze prediction errors.

Feature Importance Bar Charts to compare the influence of each feature.
