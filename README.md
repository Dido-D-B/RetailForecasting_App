# Retail Forecasting App

A functional Streamlit app that predicts daily unit sales for a selected store-item-date combination.

![Screenshot 2025-06-13 at 03 18 04](https://github.com/user-attachments/assets/2ac4e16d-239e-40fb-8e78-966d38f34f4e)


## Features

- Dropdown selection for valid store-item-date combinations
- Daily forecast with model prediction
- Interactive 10-day forecast chart
- Historical trend visualization
- CSV export option
- Responsive design with mobile adjustments

## Try the App

👉 [Open the App](https://retailforecastingapp-nwuukzuxmjkoqed66zcxcu.streamlit.app/)

## Model

- **XGBoost Regressor**
- Pretrained model file hosted on Google Drive
- Automatically downloaded when the app is first run

## Design

- Light frosted glass UI with a retail-themed background
- Custom CSS for improved layout and readability

## Files

- `forecastapp.py`: Main Streamlit application
- `df_input_light.csv`: Preprocessed input features
- `xgb_best_model.pkl`: Trained XGBoost model (loaded from Google Drive)
- `background.png`: Background image for styling
- `requirements.txt`: Python dependencies

## Setup Locally

```bash
git clone https://github.com/Dido-D-B/RetailForecasting_App.git
cd RetailForecasting_App
pip install -r requirements.txt
streamlit run forecastapp.py
