
# ❤️ Heart Disease Prediction

![Heart Disease Prediction App Screenshot](https://github.com/rafi1105/Heart_Disease_Prediction/raw/main/assets/heart_disease_app_screenshot.png)

## Overview

Heart Disease Prediction is a web application that helps users assess their risk of heart disease based on various health parameters. By filling out a simple health assessment form, users can get a prediction of whether they might be at risk for heart disease. This project leverages machine learning techniques and a user-friendly interface built with Streamlit.

## Features

- **Interactive Health Assessment Form:** Collects detailed health information such as age, gender, blood tests, ECG results, and exercise performance.
- **Real-Time Prediction:** Instantly predicts the risk of heart disease based on user input.
- **User-Friendly Interface:** Clean and intuitive design for a seamless user experience.
- **Python & Streamlit:** Built entirely with Python and Streamlit, making it easy to deploy and extend.

## Demo

Below is a screenshot of the application interface:

![App Preview](image1)

## Getting Started

### Prerequisites

- Python 3.x installed on your system

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/rafi1105/Heart_Disease_Prediction.git
    cd Heart_Disease_Prediction
    ```

2. Install required packages:
    ```bash
    pip install streamlit
    ```

3. Run the Streamlit app:
    ```bash
    python -m streamlit run app.py
    ```

4. The app will open in your web browser. Fill out the health assessment form to check your heart disease risk.

## Project Structure

```
Heart_Disease_Prediction/
│
├── app.py               # Main Streamlit application
├── model.pkl            # Trained machine learning model (if present)
├── requirements.txt     # Python dependencies
├── assets/              # Images and other static files
└── readme.md            # Project documentation
```

## How It Works

1. **Input Collection:** Users provide their personal information and health metrics in the form.
2. **Model Prediction:** The backend uses a trained machine learning model to predict the likelihood of heart disease.
3. **Results Display:** The prediction is instantly displayed to the user.

## Parameters Collected

- Age and Sex
- Blood Pressure and Cholesterol Level
- Fasting Blood Sugar
- Resting ECG Results
- Chest Pain Type
- Maximum Heart Rate Achieved
- Exercise-Induced Angina
- ST Depression and Slope
- More...

## License

This project is licensed under the MIT License.

## Acknowledgements

- Built with Python and Streamlit.
- Inspired by publicly available heart disease datasets.

---

**Note:** This project is for educational purposes only and should NOT be used as a substitute for professional medical advice.

#install terminal
```bash
pip install streamlit
python -m streamlit run app.py

```
