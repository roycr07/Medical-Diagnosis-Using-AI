# Medical-Diagnosis-Using-AI
# Disease Prediction Web Application

## Overview
This project is a web-based disease prediction application developed using **Streamlit**. It allows users to input their medical data and predict the likelihood of having various diseases such as:
- Diabetes
- Heart Disease
- Parkinson's Disease
- Lung Cancer
- Hypo-Thyroid

The application leverages **machine learning models** trained for each disease to provide predictions based on user inputs.

## Features
- **User-friendly UI**: Built with Streamlit for easy interaction.
- **Multiple Disease Predictions**: Users can select from different diseases and get a diagnosis.
- **Model Integration**: Pre-trained models are loaded using Pickle to make predictions.
- **Custom Styling**: Includes a background image and hides Streamlit UI elements for a cleaner interface.

## Installation & Setup
### Prerequisites
Ensure you have **Python 3.7+** installed along with the necessary dependencies.

### Clone the Repository
```sh
https://github.com/your-repo/disease-prediction.git
cd disease-prediction
```

### Install Required Libraries
```sh
pip install -r requirements.txt
```

### Run the Application
```sh
streamlit run app.py
```

## File Structure
- **app.py**: Main Streamlit application.
- **Models/**: Contains the trained machine learning models (.sav files).
- **requirements.txt**: List of dependencies needed to run the project.
- **Notebooks/**: Jupyter notebooks for model training.

## Usage
1. Open the application in a web browser.
2. Select the disease you want to predict.
3. Enter the required medical parameters.
4. Click the **Predict** button to get the result.

## Dependencies
This project requires the following Python libraries:
- `streamlit`
- `pickle`
- `numpy`
- `pandas`
- `scikit-learn`

Install them using:
```sh
pip install streamlit pickle-mixin numpy pandas scikit-learn
```

## Author
Developed by **[Souradeep Roy]**.
Email : souradeep07roy@gmail.com

