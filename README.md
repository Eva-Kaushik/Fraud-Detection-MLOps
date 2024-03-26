# Fraud-Detection-MLOps
# Fraud Detection System

## Overview
The Fraud Detection System is an AI-powered application designed to detect fraudulent activities in financial transactions. It leverages machine learning techniques to analyze historical data and predict the likelihood of a transaction being fraudulent.

## Features
- **Data Collection**: Collects data from NSFAS and University of Limpopo CSV files.
- **Data Preprocessing**: Cleans, preprocesses, and merges the data, handling missing values and performing feature engineering.
- **Model Training**: Trains a neural network classifier using TensorFlow/Keras.
- **Model Evaluation**: Evaluates the trained model's performance using accuracy, precision, recall, and F1 score.
- **SMS Confirmation**: Generates a random confirmation code and sends it via SMS to the user for confirmation.

## Requirements
- Python 3.x
- Pandas
- Scikit-learn
- Imbalanced-learn
- Keras
- TensorFlow
- H2O.ai
- Other dependencies listed in `requirements.txt`

## Usage
Installation: Install the required packages listed in `requirements.txt`.
   ```bash
   pip install -r requirements.txt
Data Preparation: Ensure that the NSFAS and University of Limpopo CSV files are available and correctly located. Update the file paths in the code if necessary.
Running the Application: Execute the main script fraud_detection.py.
bash
python fraud_detection.py
Result Analysis: Check the output for model evaluation metrics and the confirmation code sent via SMS.

## Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues for any suggestions, bug fixes, or improvements.
python Fraud Detection.py
