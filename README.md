# USA Housing Dataset Machine Learning
Project Description
This project aims to apply various machine learning techniques on the USA Housing dataset. The dataset contains information about various housing features and is used to predict housing prices.

## Dataset
The dataset consists of 4140 rows and 18 columns, including various features such as price, number of bedrooms, number of bathrooms, living area size, lot size, and other relevant attributes.

### Data Preprocessing
Label Encoding: Categorical variables (e.g., date, street, city, state/ZIP code, country) are converted to numerical values using LabelEncoder.
Feature Scaling: Features are scaled using MinMaxScaler to normalize the data and improve model performance.
Splitting the Dataset: The dataset is split into training (70%), validation (15%), and test (15%) sets.

### Machine Learning Models
Linear Regression: A baseline model to predict housing prices using linear relationships between features.
Decision Tree Regressor: A model to capture non-linear relationships and interactions between features.
Random Forest Regressor: An ensemble method to improve prediction accuracy and robustness by combining multiple decision trees.
Gradient Boosting Regressor: An advanced ensemble technique to boost model performance by sequentially correcting errors made by previous models.

### Model Evaluation
Models are evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared. The best-performing model is selected based on these evaluation metrics.

### Results
Linear Regression: [Insert MAE, MSE, R-squared here]
Decision Tree Regressor: [Insert MAE, MSE, R-squared here]
Random Forest Regressor: [Insert MAE, MSE, R-squared here]
Gradient Boosting Regressor: [Insert MAE, MSE, R-squared here]

### Usage
Clone the repository:
git clone [repository-url]

Navigate to the project directory:
cd [project-directory]

Install the required dependencies:
pip install -r requirements.txt

Run the main script:
python main.py

### Requirements
Python 3.x
pandas
numpy
scikit-learn
matplotlib
