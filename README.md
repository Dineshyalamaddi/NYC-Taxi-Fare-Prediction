# 🌟 NYC Taxi Fare Prediction 🌟

## 🚖 Overview
This project aims to predict the fare amount of taxi rides in New York City using historical data. By leveraging machine learning techniques, we built a robust regression model to predict fare amounts based on a variety of features such as pickup and dropoff locations, passenger count, and datetime information.

Through this project, we explore **data preprocessing**, **feature engineering**, and **model optimization** using techniques like **Random Forest Regressor** and **Hyperparameter Tuning** to achieve high-performance results.

---

## 🧑‍💻 Key Features
- **Data Preprocessing**: Handling missing values, feature scaling, datetime conversion, and feature extraction.
- **Exploratory Data Analysis (EDA)**: Insightful visualizations that uncover patterns and trends in the data, such as fare distribution and geographical patterns.
- **Feature Engineering**: Extraction of useful features like `pickup_month`, `pickup_hour`, and `day_of_week` to improve model performance.
- **Modeling**: Trained a **Random Forest Regressor** and fine-tuned hyperparameters using **RandomizedSearchCV**.
- **Model Evaluation**: Evaluated the model using **Root Mean Squared Error (RMSE)** and **R² Score** for performance.

---

## 📊 Dataset
  
The dataset consists of historical New York City taxi rides, with key features such as:
- **fare_amount**: The target variable to predict.
- **pickup_datetime**: Date and time of the ride.
- **passenger_count**: Number of passengers in the taxi.
- **pickup_longitude & pickup_latitude**: Coordinates of the pickup location.
- **dropoff_longitude & dropoff_latitude**: Coordinates of the dropoff location.

You can find the dataset in the [NYC Taxi Fare Prediction Dataset](https://www.kaggle.com/competitions/new-york-city-taxi-fare-prediction/data).

---

## 🔧 Installation

To run this project locally, clone this repository and install the required libraries.

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/NYC-Taxi-Fare-Prediction.git
    cd NYC-Taxi-Fare-Prediction
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## 📂 Project Files

- **`data_preprocessing.py`**: Handles missing values, scaling, and feature extraction.
- **`model_training.py`**: Trains the Random Forest Regressor model and performs hyperparameter optimization.
- **`visualizations.py`**: Contains various visualizations generated during the EDA phase.
- **`requirements.txt`**: Lists all necessary dependencies.
- **`notebooks/`**: Jupyter notebooks documenting the analysis and workflow.

---

## 🔍 Evaluation Metrics

The performance of the model was evaluated using the following metrics:
- **Root Mean Squared Error (RMSE)**: Measures the square root of the average squared differences between actual and predicted values.
- **R² Score**: Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.

---

## 🚀 Model Results

- **Best Parameters (RandomizedSearchCV)**:  
  `{'n_estimators': 200, 'min_samples_split': 2, 'min_samples_leaf': 4, 'max_depth': 30, 'bootstrap': True}`

- **Model Performance**:
    - **Root Mean Squared Error (RMSE)**: 14.64
    - **R² Score**: 0.67

---

## 🛠️ Future Improvements

- **Model Tuning**: Explore other algorithms such as **XGBoost** or **Gradient Boosting** to further improve accuracy.
- **Additional Features**: Integrate external features such as weather data, traffic information, or trip distance for better prediction.
- **Real-time Prediction API**: Develop a Flask or FastAPI app for real-time fare predictions based on new ride inputs.
- **Geospatial Analysis**: Perform further analysis on pickup and dropoff locations to understand the spatial distribution of fares.

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

- **Dinesh.yalamaddi**  
  [LinkedIn Profile](www.linkedin.com/in/dinesh-yalamaddi-b266392b3)
  
---

### ⭐ Thank you for checking out the project! Feel free to contribute or reach out for any suggestions.
