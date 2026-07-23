# 🏠 House Price Prediction Using Machine Learning

## Overview

This project predicts house prices using Machine Learning based on property features such as location, area, number of bedrooms, bathrooms, property age, and other relevant factors. The goal is to help buyers, sellers, and real estate professionals estimate property values accurately.

## Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Multiple regression algorithms
* Model evaluation using regression metrics
* Predict house prices from user inputs

## Dataset

The dataset contains housing-related information, including:

* Area (Square Feet)
* Number of Bedrooms
* Number of Bathrooms
* Location
* Property Age
* Parking
* Furnishing Status
* Other property features
* Target Variable: House Price

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Machine Learning Workflow

1. Load the dataset
2. Clean and preprocess data
3. Perform Exploratory Data Analysis (EDA)
4. Encode categorical variables
5. Split data into training and testing sets
6. Train regression models
7. Evaluate model performance
8. Predict house prices

## Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* XGBoost Regressor (Optional)

## Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## Project Structure

```
House-Price-Prediction/
│
├── data/
│   └── housing.csv
├── notebooks/
│   └── House_Price_Prediction.ipynb
├── models/
│   └── trained_model.pkl
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

## Installation

1. Clone the repository
2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
3. Run the project:

   ```
   python app.py
   ```

## Results

The model was trained and evaluated using standard regression metrics. The best-performing model was selected based on prediction accuracy and generalization performance.

## Future Improvements

* Hyperparameter tuning
* Deploy using Flask or Streamlit
* Integrate real-time housing datasets
* Add price trend visualization
* Improve prediction accuracy using ensemble models

## Author

**Rushikesh Patil**

## License

This project is licensed under the MIT License.
