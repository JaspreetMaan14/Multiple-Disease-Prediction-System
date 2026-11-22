# Multiple Disease Prediction System Using Machine Learning

## About the Project

The **Multiple Disease Prediction System** is a machine learning-based web application developed using Python and Streamlit. It predicts the possibility of three different diseases: Diabetes, Heart Disease, and Parkinson's Disease.

The system uses separate machine learning models trained on their respective datasets. Users can select a disease, enter the required medical information, and receive a predicted result through a simple and interactive interface.

This project demonstrates the application of machine learning techniques in healthcare-related data analysis and disease classification.

## Diseases Covered

### 1. Diabetes Prediction
- Algorithm: Support Vector Machine (Linear Kernel)
- Dataset: Diabetes Dataset
- Input Features: 8
- Testing Accuracy: 77.27%

### 2. Heart Disease Prediction
- Algorithm: Logistic Regression
- Dataset: Heart Disease Dataset
- Input Features: 13
- Testing Accuracy: 81.97%

### 3. Parkinson's Disease Prediction
- Algorithm: Support Vector Machine (Linear Kernel)
- Dataset: Parkinson's Disease Dataset
- Input Features: 22
- Testing Accuracy: 87.18%

*Note: Accuracy values are based on the test datasets used during model development.*

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Streamlit
- Streamlit Option Menu
- Pickle
- Google Colab / Jupyter Notebook

## Project Structure

```text
Multiple-Disease-Prediction-System/
│
├── app.py
├── requirements.txt
├── README.md
│
├── datasets/
│   ├── diabetes.csv
│   ├── heart.csv
│   └── parkinsons.csv
│
├── saved_models/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav
│
└── notebooks/
    ├── Diabetes_Prediction.ipynb
    ├── Heart_Disease_Prediction.ipynb
    └── Parkinsons_Prediction.ipynb
```

## Installation and Setup

Follow these steps to run the project on your local system.

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Multiple-Disease-Prediction-System.git
```

### Step 2: Open the Project Folder

```bash
cd Multiple-Disease-Prediction-System
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Run the Streamlit Application

```bash
streamlit run app.py
```

The application will open in your default web browser.

## Model Training

Three separate machine learning models are developed using Google Colab/Jupyter Notebook.

- Diabetes Prediction: Linear Support Vector Machine
- Heart Disease Prediction: Logistic Regression
- Parkinson's Disease Prediction: Linear Support Vector Machine

The trained models are saved using the Pickle library and stored in the `saved_models` directory. The Streamlit application loads these models to generate predictions.

## Features

- Prediction for three different diseases.
- Separate machine learning models for each disease.
- Simple and interactive Streamlit interface.
- User-friendly navigation between prediction modules.
- Fast prediction based on user-provided input values.
- Organized datasets, trained models, and Jupyter notebooks.

## Future Scope

- Adding more disease prediction modules.
- Improving model performance through hyperparameter tuning.
- Introducing better input validation and preprocessing.
- Adding user authentication and prediction history.
- Improving the application interface and functionality.

