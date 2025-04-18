# Breast Cancer Classification (Wisconsin Dataset)
This project applies machine learning techniques to accurately classify breast tumors as **benign** or **malignant** using features extracted from cell nuclei in digitized medical images. The aim is to support early diagnosis and assist healthcare professionals with reliable predictions based on input features from fine needle aspirates (FNA).

## Project Objective
To build, evaluate, and interpret machine learning classification models that can predict whether a tumor is **malignant** (cancerous) or **benign** (non-cancerous), based on 30 real-valued features from the **Wisconsin Breast Cancer Dataset**.

## Problem Statement
Breast cancer is one of the most common forms of cancer affecting women worldwide. Early detection is crucial for effective treatment and improved survival rates. The goal of this project is to use supervised learning algorithms to classify tumors using clinical attributes derived from digitized images of breast masses. Automating this process can reduce diagnosis time and support radiologists in making data-driven decisions. In the scope of this project will focus on the optimal model from the two, K-Nearest Neighbors and the Logistic Regression model. Deployment of the model is not part of the project.

## Dataset Overview
- **Source**: UCI Machine Learning Repository  
- **Instances**: 569 samples  
- **Features**: 30 numeric variables (e.g., radius, texture, perimeter, area, concavity, symmetry)  
- **Target**:  
  - `0` → **Malignant**  
  - `1` → **Benign**

## Technologies Used

- **Google Colab**
- **Python 3.11**
- **Pandas** – data handling  
- **NumPy** – numerical operations  
- **Matplotlib / Seaborn** – data visualization  
- **Scikit-learn** – machine learning models & evaluation

## Machine Learning Models

Implemented and compared:
- Logistic Regression
- K-Nearest Neighbors (KNN)

Each model was evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

## Results Summary

| Model              | Accuracy | Precision | Recall | F1 Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 99%     | 98%       | 98%    | 98%      |
| KNN (k=11)          | 95%     | 96%       | 91%    | 93%      |

> Logistic Regression gave the optimal results.

## Key Takeaways

- Feature scaling was crucial for Logistic Regression.
- Class imbalance was mild, metrics like **F1-score** provided a better picture than accuracy alone.
- The models show strong potential to assist in early cancer detection in clinical settings.

