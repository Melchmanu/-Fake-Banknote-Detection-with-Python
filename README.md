# Fake Banknote Detection with Python  

This project focuses on detecting counterfeit banknotes using various machine learning algorithms. The dataset, `billets.csv`, contains features extracted from genuine and forged banknotes (1,500 entries: 1,000 real and 500 fake). The goal is to classify the notes as either authentic or fake through supervised and unsupervised learning methods.  

## Overview  

### Data Pipeline  
1. **Data Preprocessing**:  
   - Handled missing values using linear regression after normalizing the data.  

2. **Unsupervised Learning**:  
   - Applied K-Means Clustering to observe the natural distribution of clusters (using the elbow method for optimal K).  

3. **Supervised Learning**:  
   - Trained and evaluated four different machine learning models:  
     - Logistic Regression  
     - K-Nearest Neighbors (KNN)  
     - Gradient Boosting  
     - Random Forest  

4. **Application**:  
   - Built a Python-based app to detect counterfeit banknotes using the trained models.  

## Files  

- **`Melchiori_Manuel_1_Notebook_analyse_012025.ipynb`**:  
   A detailed notebook explaining the preprocessing steps, unsupervised analysis (K-Means), and training/evaluation of supervised models.  

- **`Melchiori_Manuel_1_Notebook_application_012025.ipynb`**:  
   A streamlined notebook designed for users to input new data and detect counterfeit banknotes with trained models.  

- **`billets.csv`**:  
   The dataset containing features of banknotes for training and testing.  

## How to Use  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/<your-username>/Fake-Banknote-Detection  
   cd Fake-Banknote-Detection  
