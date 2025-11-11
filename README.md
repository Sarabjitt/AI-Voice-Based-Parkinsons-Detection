# AI-Voice-Based-Parkinsons-Detection
Machine Learning project for early detection of Parkinson’s Disease from voice data using the UCI Parkinson’s dataset. Built and tested in Google Colab using Random Forest Classifier.
# 🧠 Parkinson’s Disease Detection using Machine Learning  

[Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
[Colab](https://img.shields.io/badge/Google%20Colab-Compatible-yellow.svg)
[License](https://img.shields.io/badge/License-MIT-green.svg)
[ML](https://img.shields.io/badge/ML-RandomForest-orange.svg)

## 📋 Project Overview  

This project detects **Parkinson’s Disease** using **machine learning techniques** based on vocal features.  
The dataset used comes from the **UCI Machine Learning Repository**, which contains biomedical voice measurements from people with and without Parkinson’s disease.  

The goal is to classify whether a person has Parkinson’s disease based on their voice characteristics.  

## ⚙️ Technologies Used  

 🐍 **Python**  
 📘 **Pandas** & **NumPy** — for data processing  
 📊 **Matplotlib** & **Seaborn** — for visualization  
 🌲 **Scikit-learn** — for training the Random Forest Classifier  
 💻 **Google Colab** — for development and testing  


## 🧩 Dataset  

 **Dataset Name:** Parkinson’s Dataset (UCI Repository)  
 **Files Used:** `parkinsons.data`, `parkinsons.names`  
 **Total Samples:** 195 voice recordings  
 **Features:** 22 biomedical voice measurements  
 **Target Variable:** `status`  
 `1` → Person has Parkinson’s  
 `0` → Healthy person  

## 🚀 How to Run  

1. **Upload the dataset** (`parkinsons.zip`) to your Colab session.  
2. **Open the notebook:** `Parkinsons_Detection.ipynb`  
3. Run all the cells sequentially.  
4. The model will train and show accuracy results.  

## 🧠 Model Details  

**Algorithm Used:** Random Forest Classifier  
**Accuracy Achieved:** ~94%  
**Evaluation Metrics:** Accuracy, Precision, Recall, F1-score  

