

# Used Cars Price Prediction

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

## Project Overview

The objective of this project is to predict the price of used cars based on the following features:

- **Year of manufacture**
- **Kilometers driven**
- **Fuel type**
- **Car city**

### The workflow involves:

- Data preprocessing and cleaning
- Encoding categorical variables
- Feature scaling and normalization
- Model training using **Random Forest Regressor**
- Model evaluation using metrics like:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **R² score**
- Visualization of:
  - Actual vs predicted prices
  - Feature importance

## Dataset Information

The dataset used for this project contains information about used cars. Below is a description of the dataset:

- **File Format**: CSV
- **Columns**: The dataset includes features like:
  - `car_price_in_rupees`
  - `year_of_manufacture`
  - `kms_driven`
  - `fuel_type`
  - `city`
- **Source**: A local dataset (you can replace this with a link to your dataset if hosted online).

### Data Cleaning:
- Missing values are filled with:
  - Mean for numerical columns
  - Mode for categorical columns
- **Outliers** are removed using Z-scores.
- **Categorical variables** are one-hot encoded.

## Setup Instructions

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/used-car-price-prediction.git
cd used-car-price-prediction

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
