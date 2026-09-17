Multiple Linear Regression – House Price Analysis
📌 Overview
This project uses Multiple Linear Regression to predict house prices using housing data from King County, Seattle.
The dataset is divided into separate files for training and testing, allowing the models to learn from one dataset and evaluate their predictions on another dataset that was not used during training.

🎯 Objectives
Load and explore the training, testing, and full datasets.
Use separate datasets for model training and testing.
Create new features using feature engineering.
Build and compare 3 Linear Regression models.
Analyze model coefficients and predictions.
Evaluate model performance using Mean Squared Error (MSE).

📂 Datasets
kc_house_train_data.csv — used to train the models.
kc_house_test_data.csv — used to test and evaluate the trained models.
kc_house_data.csv — full dataset used for additional analysis.

🛠️ Libraries
Pandas
NumPy
Scikit-Learn

🔧 Feature Engineering
Created new features to explore different relationships between the variables:
bedrooms_squared
bed_bath_rooms
log_sqft_living
lat_plus_long
These engineered features were used in different model configurations to examine their effect on model performance.

🤖 Models
Three Multiple Linear Regression models were created using different combinations of the original and engineered features.
The models were trained using the training dataset and evaluated using the testing dataset.

📊 Evaluation
Model performance is evaluated using Mean Squared Error (MSE) to measure the difference between the actual house prices and the prices predicted by each model.
Using separate training and testing datasets helps evaluate how well the models perform on unseen data.
