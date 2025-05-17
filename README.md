# TensorFlow-Lite-Intent Classifier

## Overview
This notebook trains a Random Forest and XGBoost classifiers to detect malicious apps capable of implicit intent hijacking. It compares Random Forest and XGBoost, selects the best model RF and converts the model to TensorFlow Lite (TFLite) as `model.tflite` for deployment on an Android.

## Purpose
The notebook aims to:
- Preprocess a dataset of Android app features.
- Train and evaluate machine learning models.
- Generate a lightweight TF Lite model for mobile inference.

## Requirements
- **Python Version**: 3.7 or higher
- **Libraries**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `xgboost`
  - `tensorflow`
  - `matplotlib`
- **Environment**: Jupyter Notebook or JupyterLab

## Installation
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd ML_model_intent_classifier

2. **Set Up Environment**:
   - Create a virtual environment (optional):
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install required packages**:
     ```bash
     pip install pandas numpy scikit-learn xgboost tensorflow matplotlib

4. **Download Dataset**:
   -Ensure the dataset file dataset.csv (6,514,978 bytes) is in the directory, or update the notebook to point to your dataset location.

# Results
![image](https://github.com/user-attachments/assets/cbb388eb-60c9-463f-8948-e1b92eab18e1)

## ROC-AUC Score Evaluation
![image](https://github.com/user-attachments/assets/674c65e9-e845-4261-b964-4ef44a87b702)

## RF & XGBoost Evaluation
![image](https://github.com/user-attachments/assets/0b3f0a8d-1642-4c13-a365-66c6796179c0)


## Evaluation of TF Lite model
![image](https://github.com/user-attachments/assets/d5b6d180-9219-431c-9705-e1187bbe3c58)


