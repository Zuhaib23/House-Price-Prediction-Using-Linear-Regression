🏠 House Price Prediction using Linear Regression
This project predicts house prices based on key features such as area, number of bedrooms, bathrooms, location access, and more. It uses a linear regression model trained on a real-world housing dataset.

📊 Project Overview
Goal: Predict housing prices accurately based on features.


Dataset: https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction

Model Used: Linear Regression
Language: Python
Libraries: pandas, seaborn, matplotlib, scikit-learn, joblib

🧠 Features Used
Area (sqft)
Number of bedrooms, bathrooms, stories
Main road access
Guest room, basement availability
Heating and air conditioning
Parking space
Preferred area status
Furnishing status

**📁 Files in This Repository**
File Name	Description
train_model.py	Loads and preprocesses data, trains model, saves model, includes full visualizations
predict_test.py	Tests model on the original dataset or holdout validation data
predict_on_new_data.py	Predicts house prices on completely new unseen data
Housing.csv	Original dataset (place this in your working directory)
new_housing_data.csv	Sample new data for testing prediction (optional)
house_price_model.pkl	Saved model after training

**📈 Visualizations**
Correlation heatmap between features
Actual vs Predicted Price scatter plot
Evaluation metrics: MSE, R² score







