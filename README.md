# Smart Irrigation System - AICTE Project 

This project is a smart irrigation system built using machine learning to predict irrigation needs based on sensor data.

## Files Included

- `app.py` – Streamlit web application that runs the prediction interface.
- `Farm_Irrigation_System.pkl` – Trained machine learning model file.
- `model_training.ipynb` – Colab notebook used to train and save the model.
- `README.md` – Project overview and setup instructions.

## How It Works

The Streamlit app automatically generates 20 random sensor values between 0 and 1 and uses the trained model to predict whether irrigation is required.

## How to Run Locally

1. **Install Streamlit** (only once):
   ```bash
   pip install streamlit
   streamlit run app.py
   pip install streamlit numpy joblib
   

