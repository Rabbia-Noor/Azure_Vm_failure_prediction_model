# Azure VM Failure Prediction Model

## Overview

This project is a data analytics and machine learning-based solution designed to predict potential failures in Azure Virtual Machines (VMs). It analyzes system performance metrics to identify patterns that indicate possible VM failure. The goal is to improve system reliability, reduce downtime, and support proactive maintenance in cloud environments.

The entire project is implemented in a single Jupyter Notebook:

Final_Data_Analytics_Project.ipynb

---

## Objective

The main objectives of this project are:

- To analyze Azure VM performance data
- To identify patterns associated with system failures
- To build a machine learning model for failure prediction
- To improve system reliability using predictive analytics

---

## Project File

- Final_Data_Analytics_Project.ipynb  
  This notebook contains all stages of the project including data preprocessing, exploratory data analysis, feature engineering, model building, and evaluation.

---

## Methodology

The project follows a standard data science workflow:

1. Data Loading
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Prediction of VM Failure

---

## Dataset Features

The dataset includes the following system performance metrics:

- CPU Usage
- Memory Usage
- Disk Activity
- Network Usage
- System Performance Indicators
- Failure Label (Target Variable)

---

## Machine Learning Models

The following supervised learning algorithms are used in this project:

- Logistic Regression
- Decision Tree
- Random Forest (if implemented in notebook)

These models are trained and compared to identify the best-performing approach for VM failure prediction.

---

## Evaluation Metrics

The models are evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Repository Structure

Azure_Vm_failure_prediction_model/
│
├── Final_Data_Analytics_Project.ipynb
└── README.md

---

## How to Run the Project

### Step 1: Clone the repository
git clone https://github.com/Rabbia-Noor/Azure_Vm_failure_prediction_model.git

### Step 2: Open Jupyter Notebook
jupyter notebook

### Step 3: Open the file
Final_Data_Analytics_Project.ipynb

Run all cells sequentially.

---

## Results

The trained model is capable of analyzing VM performance metrics and predicting potential failures. This helps in early detection of system issues and improves overall cloud reliability.

---

## Future Improvements

- Integration with real-time Azure monitoring systems
- Deployment on Azure cloud platform
- Development of a live monitoring dashboard
- Use of advanced deep learning models
- Automated alert system for failure detection

---

## Author

Rabbia Noor  
Computer Science Student | AI/ML Enthusiast  

GitHub: https://github.com/Rabbia-Noor
