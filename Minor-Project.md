Used Cars Price Prediction
This project aims to predict the prices of used cars using a machine learning approach. The dataset is cleaned, preprocessed, and used to train a Random Forest Regressor model to predict the price of used cars based on various features such as the car's age, kilometers driven, fuel type, and city. The project also includes data visualizations and model evaluation metrics.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Information](#dataset-information)
- [Setup Instructions](#setup-instructions)
- [Data Preprocessing](#data-preprocessing)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Results & Visualizations](#results--visualizations)
- [Contributing](#contributing)
- [Contact Information](#contact-information)


Project Overview
The objective of this project is to predict the price of used cars based on features like:

Year of manufacture
Kilometers driven
Fuel type
Car city
The workflow involves:

Data preprocessing and cleaning
Encoding categorical variables
Feature scaling and normalization
Model training using Random Forest Regressor
Model evaluation using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.
Visualization of actual vs. predicted prices and feature importance.
Dataset Information
The dataset used for this project contains information about used cars. Below is a description of the dataset:

File Format: CSV
Columns: The dataset includes features like car_price_in_rupees, year_of_manufacture, kms_driven, fuel_type, city, etc.
Source: A local dataset (you can replace this with a link to your dataset if hosted online).
Data Cleaning:
Missing values are filled.
Outliers are removed using Z-score.
Categorical variables are one-hot encoded.
Setup Instructions
Clone the repository:

bash
Copy
git clone https://github.com/your-username/used-car-price-prediction.git
cd used-car-price-prediction
Create a virtual environment:

bash
Copy
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install dependencies:

bash
Copy
pip install -r requirements.txt
Download or place your dataset in the data/ folder and update the data_url variable in the code to point to the correct file path.

Data Preprocessing
This step involves cleaning and preparing the dataset for model training:

Missing Values: Numerical columns are filled with the mean, and categorical columns are filled with the mode.
Currency and String Cleaning: The car_price_in_rupees column is cleaned by removing currency symbols and converting to numeric values (handling Lakh and Crore).
Outliers: Outliers are detected using Z-scores and removed.
One-Hot Encoding: Categorical variables like fuel_type and city are one-hot encoded.
Feature Scaling: Numerical features like kms_driven are standardized using StandardScaler.
Model Training and Evaluation
Model Selection
Random Forest Regressor is chosen as the model to predict car prices.
Hyperparameters are optimized using GridSearchCV to find the best model configuration.
Model Evaluation
The model's performance is evaluated using:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score
Results & Visualizations
Actual vs Predicted Prices: A scatter plot showing actual vs predicted prices. This helps visualize how accurate the model's predictions are.

![image](https://github.com/user-attachments/assets/04fe9866-2dfc-4de9-8897-c107fe4a7202)

Actual vs. Predicted Prices: Scatter plot comparing actual vs. predicted prices, where clustering along the diagonal indicates strong model performance.


Feature Importance: A bar chart visualizing the importance of each feature used by the Random Forest Regressor model.

Feature Importance: Bar chart ranking features by their importance in the model, showing their relative influence on predictions.

![image](https://github.com/user-attachments/assets/92bf8dd9-0869-4d53-8b0c-7386dedc6d68)


Residual Plot: A residual plot is generated to analyze the distribution of prediction errors.

![image](https://github.com/user-attachments/assets/a5de7856-1375-4ae8-8091-02e0e097afc0)

Residual Plot: Scatter plot of residuals vs. predicted prices, used to assess the model's errors and identify potential issues.



Contributing
We welcome contributions to improve this project. Please fork the repository, make your changes, and submit a pull request. If you want to add new features, improve model performance, or fix bugs, feel free to contribute!

For more details, refer to the CONTRIBUTING.md file.




Contact Information
For any questions, feel free to reach out:

Name: Boddeda Venkata Pavan Karthikeya
Email: sunny.penny041@gmail.com
LinkedIn: LinkedIn Profile
