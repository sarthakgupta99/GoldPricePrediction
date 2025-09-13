# Gold Price Prediction using Machine Learning

## Overview 📈

This project demonstrates the development of a machine learning model to predict gold prices using various financial indicators. The project follows a complete data science pipeline, from data preprocessing and exploratory data analysis (EDA) to model training and evaluation. The goal is to build a robust predictive model that can accurately forecast the price of gold based on other relevant financial assets.

## Key Features ✨

* **Data Preprocessing**: The dataset was cleaned and prepared for modeling. This included handling missing values, applying a square root transformation to address data skewness, and using a custom function to handle outliers.
* **Feature Engineering**: A new feature, `price_trend`, was created using a rolling mean to capture the short-term trend in gold prices.
* **Exploratory Data Analysis (EDA)**: The notebook includes a correlation matrix heatmap and distribution plots to understand the relationships between different financial indicators and the target variable.
* **Model Training and Hyperparameter Tuning**: Several regression models were trained and evaluated, including **Lasso**, **Random Forest**, and **XGBoost**. **GridSearchCV** was used to find the optimal hyperparameters for the models, ensuring high performance.
* **Performance Evaluation**: The final model was evaluated using the R-squared metric, achieving a score of **over 97%** on the test data.
* **Feature Importance Analysis**: The project includes a feature importance plot to identify which financial indicators have the most significant impact on gold prices, providing valuable insights into the model's predictions.

## Technology Stack 💻

* **Python**: The primary programming language used for the project.
* **Pandas**: For data manipulation and analysis.
* **NumPy**: For numerical operations.
* **Scikit-learn**: For machine learning models and data preprocessing techniques like `StandardScaler` and `train_test_split`.
* **XGBoost**: For implementing the high-performance XGBoost regression model.
* **Matplotlib** and **Seaborn**: For data visualization and plotting.
