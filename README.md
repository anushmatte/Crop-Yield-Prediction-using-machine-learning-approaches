🌾 Crop Yield Prediction using Machine Learning Approaches
Predicting crop yields is vital for optimizing agricultural productivity and ensuring food security. This project leverages machine learning techniques to forecast crop yields based on historical data and environmental factors, providing valuable insights for farmers, agronomists, and policymakers.

📂 Project Structure
Crop Yield Prediction.ipynb: Jupyter Notebook containing data preprocessing, exploratory data analysis, model training, and evaluation.

app.py: Backend script for the web application interface.

auth.py: Handles user authentication mechanisms.

database.py: Manages database connections and queries.

init_db.py: Initializes the SQLite database schema.

data.db: SQLite database file storing user and prediction data.

yield_df.csv: Dataset containing historical crop yield and environmental data.

encoder.pkl & label_encoder.pkl: Serialized encoders for preprocessing categorical variables.

generated-icon.png: Application icon for the web interface.

📊 Features
Data Preprocessing: Handles missing values, encodes categorical variables, and normalizes features.

Model Training: Implements machine learning algorithms (e.g., Linear Regression, Random Forest) to predict crop yields.

Web Application: User-friendly interface for inputting data and viewing predictions.

User Authentication: Secure login system to manage user access.

Database Integration: Stores user information and prediction history for future reference.
