# Student Performance Analysis Prediction System

## Overview

The **Student Performance Analysis Prediction System** is a Machine Learning project developed using **Python** and **Scikit-learn** to predict a student's **Exam Score** based on academic and behavioral factors. By analyzing historical student data, the model learns patterns that help estimate future student performance.

This project demonstrates the complete Machine Learning workflow, including:

* Data Collection and Loading
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Selection
* Model Training
* Model Evaluation
* Data Visualization
* Performance Prediction

---

## HOW TO RUN THE PROJECT

There are two ways to run the project:
1. Thorugh Google Colab as the Steps are defined Below in the Installation Steps.
2. Using the Dashboard User Interface made with React and FastAPI using the link:
   
   **https://student-analysis-model-lezc.vercel.app/**

   Github Repository Link of Dashboard:

   **https://github.com/abdullahmufeezz/Student-Performance-Analysis-Prediction-Model-DashboardUI**

---

## Installation Process

Follow these steps to execute the notebook successfully:

### Step 1: Open the Repository

Visit the GitHub repository:

**https://github.com/abdullahmufeezz/Students_Performance_Analysis_Prediction_System**

---

### Step 2: Open the Notebook

* Click on **Student_Performance_Analysis.ipynb**.
* At the top of the notebook preview, click **Open in Colab**.

---

### Step 3: Sign in to Google Colab

* Log in with your Google account if you are not already signed in.

---

### Step 4: Download the Dataset

* Return to the GitHub repository.
* Download the file named **Students_dataset.csv**.

---

### Step 5: Upload the Dataset

* In Google Colab, click the **Files** icon on the left sidebar.
* Click the **Upload** button.
* Select and upload **Students_dataset.csv**.

---

### Step 6: Run the Notebook

Execute the notebook cells in order from top to bottom:

1. Importing all Libraries
2. Loading and Exploring Dataset (EDA) + Cleaning Data
3. Feature Engineering (Features and Target)
4. Train Test-Split
5. Training Model
6. Predictions & Evaluation
7. Saving the Model
8. Checking Prediction Model for Student Score
9. To Download this Model Run Below (If you want to download model.pkl)
10. Study Hours vs Exam Score ( Visiuals = A chart Showing Study Hours and Exam Score)
11. Correlation Heatmap
12. Feature Importance Graph


Running the cells sequentially ensures that all required variables, models, and outputs are generated correctly.

---

## Required Libraries

1. Pandas
2. Numpy
3. Matplotlib.pyplot
4. Seaborn
5. joblib
6. from sklearn.model_selection import train_test_split
7. from sklearn.ensemble import RandomForestRegressor
8. from sklearn.metrics import mean_squared_error, r2_score, mean_absolute_error

---

## Expected Output

<img width="389" height="194.5" alt="image" src="https://github.com/user-attachments/assets/5f086bde-0c76-4a70-b0ac-a21837f6db2c" />



**Enter the student's academic and behavioral details (study_hours, attendence, sleep_hours, internet_usage, assignment_completed, and previous_score). The trained machine learning model will analyze the provided inputs and predict the expected exam score using patterns learned from the training dataset.**

---

## Links

* Google Colab Notebook: https://colab.research.google.com/drive/19Ibf-QiawheRePELJCGPCIEW69FfrlIb?usp=sharing
* Dataset Source: https://www.kaggle.com/datasets/shambhurajejagadale/student-performance-prediction-dataset

---

## Repository Structure

```text
Students_Performance_Analysis_Prediction_System/
│
├── Student_Performance_Analysis.ipynb                                  # Main Google Colab Notebook
├── Students_dataset.csv                                                # Dataset
├── Students Performance Prediction System (Project Report).pdf         # Project File
├── requirement.txt                                                     # requirement text file (used for backend while making dashboard UI)
└── README.md                                                           # Project Documentation
```
