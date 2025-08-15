# 🚴 Food Delivery Time Prediction Model

## 📌 Project Overview
The **Food Delivery Time Prediction Model** estimates the delivery time for food orders with high accuracy.  
By predicting delivery times precisely, this project aims to:

- Enhance **customer satisfaction** by setting realistic expectations.
- Improve **delivery partner efficiency**.
- Optimize **logistics operations** for food delivery platforms.

---
## Project Structure

.
├── dataset/
│   └── food_delivery_data.csv
├── images/
│   ├── methodology.png
│   └── deployment.png
├── main.py
├── model.pkl
├── scaler.pkl
├── requirements.txt
├── Food-Delivery-Time-Prediction-Using-Machine-Learning.ipynb
├── Location_finder_api.ipynb
└── README.md


## 📊 Methodology

![Methodology]([images/methodology.png](https://github.com/Dev-debasish-09/Food_Delivery_Time_prediction/blob/main/Methodology.png))

### **a) Data Collection**
- Collected the dataset containing order details, delivery partner info, weather, traffic, and delivery times.
- Dataset stored in the `dataset` folder.

### **b) Data Preprocessing**
- **Data Cleaning**: Removed null values, handled outliers, fixed inconsistencies.
- **Feature Engineering**: Extracted features such as day, month, quarter, weekend indicator, and distances using geolocation.

### **c) Model Development**
- Trained regression models:
  - Linear Regression
  - Decision Trees
  - Random Forest
  - **XGBoost** (Best Performing)

### **d) Model Evaluation**
- Evaluation Metrics:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- **Best Model**: XGBoost with R² = **0.82**

### **e) Deployment**
- Built a **Streamlit** app for real-time predictions.
- Integrated **OpenCage API** for converting addresses to GPS coordinates.

---

## 🚀 Deployment

![Deployment](images/deployment.png)

### **Run the Application**
1. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
