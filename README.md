# Food Delivery Time Prediction Model
## Project Overview
The Food Delivery Time Prediction Model aims to estimate the time required for food to be delivered to customers accurately. By providing precise delivery time predictions, the model enhances customer experience, optimizes delivery logistics, and improves overall operational efficiency for food delivery platforms.

## Methodology

<p align="center">
  <img src="Food_Delivery_Time_prediction/Methodology.png" alt="Project Schema" width="800"/>
</p>



### a) Data Collection
• Gathered the food delivery dataset from the provided data source and The dataset used for this project is located in the dataset folder and includes order details, location, city, delivery person information, weather conditions, and actual delivery times.

### b) Data Preprocessing
• Data Cleaning: Handled missing values, outliers, and inconsistencies in the dataset.
• Feature Engineering: Extracted relevant features for the prediction model.

### c) Model Development
• Utilized regression algorithms to train the food delivery time prediction model.
• Explored models such as Linear Regression, Decision Trees, Random Forests, and XGBoost to determine the best-performing model.

### d) Model Evaluation
• Evaluated model performance using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) score.

### e) Deployment
• Deployed the food delivery time prediction model as a standalone application using Streamlit.
• Integrated OpenCage API for geolocation functionality in the application.

#### OpenCage API Integration
• The application uses the OpenCage API for geolocation to convert addresses into latitude and longitude, with the relevant code snippet located in the main.py file.

## Technologies

• Programming Language: Python

• Development Environment: Jupyter

• Application Framework: Streamlit

## Python Packages Used

• Pandas

• NumPy

• Scikit-learn

• Matplotlib

• Seaborn

• XGBoost

## Project Files
• Dataset: ```Food-Delivery-Time-Prediction-Using-Machine-Learning.ipynb```

• Location Finder API: ```Location_finder_api.ipynb```

• Deployment Script: ```main.py```

• Model: ```model.pkl```

• Scaler: ```scaler.pkl```

• Requirements: ```requirements.txt```

## Steps Followed

1. Data Collection: 

    • Gathered the food delivery dataset from the provided data source.

2. Data Preprocessing:

    • Data cleaning to handle missing values, outliers, and inconsistencies.

    • Feature engineering to extract relevant features.

3. Model Development:

    • Trained various regression models including Linear Regression, Decision Trees, Random Forests, and XGBoost.

4. Model Evaluation:

    • Used metrics such as MSE, RMSE, and R² score to evaluate model performance.

5. Deployment:

    • Deployed the model using Streamlit for real-time predictions. Follow the steps above to run the application.

To run the deployed application, follow these steps:

1. Install Streamlit: Ensure that Streamlit is installed. You can install it using pip:
  ```pip install streamlit```

2. Run the Application: Navigate to the project directory and run the following command in the terminal:
  ```streamlit run main.py```

![Deployment]([https://github.com/Kaushik-Puttaswamy/Food-Delivery-Time-Prediction-Using-Machine-Learning/blob/main/Deployment.png](https://github.com/Dev-debasish-09/Food_Delivery_Time_prediction/blob/main/Screenshot%202025-08-15%20181239.png))

## Results and Evaluation Criteria
• Best-Performing Model: XGBoost

• R-squared (R²) Score: 0.82

## Future Improvements
• Incorporate additional features related to delivery partners, weather conditions, or traffic patterns to enhance prediction accuracy.

• Conduct more comprehensive data analysis to identify additional patterns or correlations.

• Fine-tune model parameters to potentially improve performance.


## Contact
Author: [Debasish Pradhan](https://www.linkedin.com/in/debasish-pradhan-609399237/)


