# 🚨 SENTINEL AI — Multi-Hazard Detection System

**Simulate. Detect. Analyze. Alert.**

SENTINEL AI is a deep learning-based multi-hazard detection prototype that simulates fire, flooding, gas leakage, and abnormal temperature using virtual IoT sensors, Deep Neural Networks (DNN), Autoencoder-based anomaly detection, and an interactive Streamlit dashboard.

## 🎯 Project Objectives

- Simulate environmental sensor readings without physical hardware.
- Classify environmental conditions using deep learning.
- Identify unusual sensor patterns using an Autoencoder.
- Estimate prototype risk levels and display simulated alerts.
- Visualize sensor readings, predictions, and analytics in a dashboard.

## ✨ Key Features

- 🌡️ Virtual temperature and humidity monitoring
- 🔥 Fire and abnormal temperature scenarios
- 🌊 Flood simulation
- 💨 Simulated gas and smoke detection
- 🧠 DNN-based hazard classification
- 📊 Autoencoder-based anomaly detection
- 🚨 Risk scoring and simulated alerts
- 📈 Interactive Streamlit dashboard
- 🔌 ESP32 circuit simulation using Wokwi

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy and pandas
- scikit-learn
- Streamlit
- ESP32 simulation
- Wokwi
- Plotly

## 🏗️ System Architecture

```text
Virtual IoT Sensors (Wokwi)
          |
          v
Sensor Data Generation
          |
          v
Data Preprocessing
          |
          v
DNN Hazard Classification
          |
          v
Autoencoder Anomaly Detection
          |
          v
Prototype Risk Estimation
          |
          v
Streamlit Dashboard
          |
          v
Simulated Alerts and Analytics
```

**Note:** The Wokwi simulation and Python dashboard are separate components unless a communication bridge is configured.

## 🧪 Hazard Classes

1. Normal Environment
2. Fire
3. Flood
4. Gas Leakage
5. Abnormal Temperature

## 📂 Project Structure

```text
sentinel-ai-multi-hazard/
├── app.py
├── requirements.txt
├── README.md
├── .streamlit/
│   └── config.toml
├── models/
│   ├── multi_hazard_dnn.keras
