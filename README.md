# 🚗 Real-Time Traffic Accident Severity Prediction System

This project predicts the **severity of road accidents** (Slight, Serious, or Fatal Injury) based on environmental, road, vehicle, and driver-related factors.  
The purpose is to **support traffic authorities**, researchers, and emergency services in assessing accident impact quickly.

---

## 📌 Features
- Machine Learning based **Accident Severity Prediction**
- Advanced **Feature Engineering**
- Model trained on **balanced dataset**
- Web interface created using **Flask**
- **Ngrok integration** for public hosting
- Accepts **real-time input** and predicts severity instantly

---

## 🧠 Machine Learning Workflow

| Step | Description |
|-----|-------------|
| 1. Import Libraries | Load all required Python packages |
| 2. Load Dataset | Read CSV data and inspect structure |
| 3. EDA & Feature Engineering | Analyze patterns and create new derived features |
| 4. Target Variable Processing | Convert accident severity into classes |
| 5. Data Cleaning | Remove irrelevant columns + handle missing values |
| 6. Identify Column Types | Distinguish categorical and numerical variables |
| 7. Data Preprocessing | Label Encoding + Scaling |
| 8. Train-Test Split | Prepare training & testing data |
| 9. Model Selection & Training | Random Forest / CatBoost model used |
| 10. Model Evaluation | Classification report and accuracy score |
| 11. Feature Importance | Analyze contributing features |
| 12. Hyperparameter Tuning | Improve model performance |
| 13. Save Models | Save using `joblib` (model, scaler, encoders) |
| 14. Flask Deployment | UI + Predict Function |

---

## 💻 Technologies Used
- Python
- Pandas / NumPy
- Scikit-learn
- CatBoost / Random Forest
- Flask
- Pyngrok
- HTML / CSS

---

## 🧾 Dataset Description

| Feature | Description |
|--------|-------------|
| Time | Time of accident |
| Day_of_Week | Day accident occurred |
| Weather | Weather conditions |
| Vehicle_Type | Type of vehicle involved |
| Average_Speed | Speed of vehicle |
| Driving_Experience | Driver skill level |
| Type_of_Collision | Collision pattern |
| Area | Location type (Urban / Rural / Highway) |
| Road_Alignment | Road geometry |
| Traffic_Density | Traffic level |
| Road_Condition | Road surface state |
| Temperature (°C) | Environmental temperature |
| Hour | Extracted from Time |
| Day_or_Night | Derived from Hour |
| Is_Weekend | Derived from Day |
| Speed_Category | Derived from Average Speed |
| **Target:** Accident Severity | Slight, Serious, Fatal |

---

## 🚀 How to Run

1.Upload the dataset (RTA_Dataset.csv) into the notebook directory.

2.Run all the cells in the notebook in order.

3.Make sure model, scaler, and encoder file paths match your environment.

4.At the end, a Flask public link will be shown → Click the link to open the web app.

5.Enter the input values in the form and click Predict to view the accident severity result.



