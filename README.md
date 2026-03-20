# ⚡ Electric Motor Temperature Prediction using Machine Learning

A Machine Learning based system that predicts Permanent Magnet (PM) temperature of an electric motor using sensor inputs such as ambient temperature, coolant temperature, voltage, current, and motor speed.

This project demonstrates predictive maintenance using regression models and Flask deployment.
# Electric Motor Temperature Prediction using Machine Learning

## 📌 Project Overview
This project predicts the Permanent Magnet (PM) temperature of an electric motor using Machine Learning. The model is trained on motor sensor data such as ambient temperature, coolant temperature, voltages, currents, and motor speed.

The system includes:
- Data preprocessing
- Feature scaling
- Machine learning model training
- Flask web application for prediction
- Temperature status indicator (Normal / Medium / Danger)

---
## 📁 Project Structure

```
Electric-Motor-Temperature-Prediction/
│
├── Dataset/                     # Raw dataset (ignored in GitHub)
│   └── pmsm_temperature_data.csv
│
├── Training/                    # Model training notebooks / scripts
│   └── training_code.ipynb
│
├── Model/                       # Saved ML model and scaler
│   ├── model.save
│   └── transform.save
│
├── Flask/                       # Flask application files
│   ├── templates/
│   │   └── index.html
│   └── app.py
│
├── IBM_Scoring_Endpoint/        # Cloud deployment files (optional)
│
├── test_prediction.py           # Script to test predictions
├── requirements.txt             # Python dependencies
├── .gitignore                   # Ignore dataset & large files
└── README.md                    # Project documentation
```
## 🚀 Features
- Predicts motor PM temperature
- Real-time prediction using Flask API
- Scaled input features
- Clean frontend UI
- Color-based status display:
  - 🟢 Green → Normal
  - 🟠 Orange → Medium
  - 🔴 Red → Danger

---
## 📂 Dataset

⚠️ The dataset is not included in this repository due to GitHub file size limitations.

Please download the dataset from:
[koggle link:https://www.kaggle.com/datasets/wkirgsn/electric-motor-temperature]

After downloading, place it inside the `Dataset/` folder.
## 🤖 Trained Model

The trained model file is not uploaded to GitHub.

To generate the model:
1. Run the training notebook in the `Training/` folder.
2. Save the model inside the `Model/` folder.
## 🧠 Input Features
The model uses the following inputs:

- Ambient Temperature
- Coolant Temperature
- Voltage d-axis (u_d)
- Voltage q-axis (u_q)
- Motor Speed
- Current d-axis (i_d)
- Current q-axis (i_q)

---

## 🏗️ Project Structure
---

## 📊 Model Information
- Algorithm: Machine Learning Regression Model
- Scaler: StandardScaler
- Model saved using: joblib

---

## ❗ Note
Due to GitHub file size limitations, the dataset file is not included in this repository.

---

## 📌 Future Improvements
- Deploy to cloud (AWS / Render / Heroku)
- Add real-time sensor integration
- Improve UI with dashboard visualization
- Add performance monitoring

---

## 👨‍💻 Author
Team ID: LTVIP2026TMIDS81670
Team Size: 4
Team Leader: Kalla Aakash
Team member: Kavya Vunise
Team member: Koneti Manish
Team member: Koushik Reddy
Machine Learning & AI Enthusiast

---

## 📄 License
This project is for educational purposes.
