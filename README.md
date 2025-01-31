# Fake Banknote Detection with Python

## Notebooks 📓
- [Data Analysis Notebook](https://github.com/Melchmanu/-Fake-Banknote-Detection-with-Python/blob/main/Melchiori_Manuel_1_Notebook_analyse_012025.ipynb)
- [Application Notebook](https://github.com/Melchmanu/-Fake-Banknote-Detection-with-Python/blob/main/Melchiori_Manuel_1_Notebook_application_012025.ipynb)

## Overview
This project focuses on detecting counterfeit banknotes using various machine learning algorithms. The dataset, `billets.csv`, contains features extracted from genuine and forged banknotes (1,500 entries: 1,000 real and 500 fake). The goal is to classify the notes as either authentic or fake through supervised and unsupervised learning methods.

## Data Pipeline
The main steps of the project include:
- **Data Preprocessing**: 
  - Handled missing values using linear regression after normalizing the data.
- **Unsupervised Learning**: 
  - Applied K-Means Clustering to observe the natural distribution of clusters (using the elbow method for optimal K).
- **Supervised Learning**: 
  - Trained and evaluated four different machine learning models:
    - Logistic Regression
    - K-Nearest Neighbors (KNN)
    - Gradient Boosting
    - Random Forest
- **Application**: 
  - Built a Python-based app to detect counterfeit banknotes using the trained models.

## Files
- [`billets.csv`](https://github.com/Melchmanu/-Fake-Banknote-Detection-with-Python/blob/main/billets.csv): The dataset containing features of banknotes for training and testing.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Fake-Banknote-Detection
   cd Fake-Banknote-Detection

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

3.Run the notebooks to explore the analysis and use the app:
  ```bash
Open Melchiori_Manuel_1_Notebook_analyse_012025.ipynb to see the data preprocessing, unsupervised analysis, and training/evaluation of the models.

Open Melchiori_Manuel_1_Notebook_application_012025.ipynb to use the app for detecting counterfeit banknotes with trained models.




Key Features
Detect counterfeit banknotes using machine learning algorithms.

Comprehensive data preprocessing and model evaluation.

Python-based application for real-time counterfeit detection.

Future Improvements
Integrate additional features for improved accuracy.

Develop an enhanced user interface for the application.

Explore other machine learning algorithms for better performance.
