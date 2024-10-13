# machine-failure-analysis

# Machine Failure Analysis Using Sensory Data

This project focuses on predicting machine failures using sensory data collected from various machines. The goal is to reduce downtime by identifying failures early, allowing for proactive maintenance.

## Project Overview

- **Objective**: To develop a predictive model for machine failures.
- **Dataset**: Includes sensor readings such as air quality, temperature, ultrasonic sensor data, and more.
- **Model**: Random Forest classifier with an accuracy of 88%.
- **Outcome**: The model helps predict machine failures with high accuracy, identifying key features such as VOC levels and air quality.

## Key Files

- `data.csv`: Sensor data used for training the model.
- `script.ipynb`: Jupyter notebook containing the code for data preprocessing and model training.
- `MACHINE FAILURE PREDICTION PROJECT - REPORT.pdf`: Project report explaining methodology, results, and insights.
- `random_forest_model.pkl`: Trained Random Forest model.
- `dashboard.docx`: Instructions for accessing the live Streamlit dashboard for real-time failure prediction.

## Results

- **Accuracy**: 88%
- **Key Features**: VOC levels, air quality, ultrasonic sensor data
- **Confusion Matrix**: 
[[90 12], [11 76]]


Explore the live dashboard here: [Streamlit Dashboard](https://vasvxpp5mbtdoxtqjbkney.streamlit.app/?embed_options=show_toolbardark_theme)
