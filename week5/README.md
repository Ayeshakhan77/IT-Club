# Week 5: Introduction to Machine Learning Models

This repository contains my work for **Week 5** of my internship, where I explored the basics of **Machine Learning models** using my own dataset.

## 🎯 Objectives
- Split dataset into **training and testing sets**
- Train **Linear Regression**, **Decision Tree**, and **K-Nearest Neighbors (KNN)** models
- Evaluate models using **RMSE** (for regression) and **accuracy** (for classification)
- Perform **cross-validation** to check robustness
- Document the process in a **Jupyter Notebook**

## ⚙️ Steps Performed
1. **Data Preprocessing**
   - Handled missing values with `SimpleImputer`
   - Converted dataset into features (`X`) and target (`y`)
   - Scaled and cleaned data for training

2. **Model Training**
   - **Linear Regression** for predicting continuous values
   - **Decision Tree** for non-linear relationships
   - **K-Nearest Neighbors (KNN)** for similarity-based predictions

3. **Model Evaluation**
   - Used **train-test split** to validate results
   - Calculated **RMSE** and **accuracy**
   - Applied **cross-validation** for robustness

## 📊 Results
- Each model was trained and evaluated on my dataset
- Metrics such as **RMSE**, **accuracy**, and **cross-validation scores** were compared
- Decision Tree and KNN captured non-linear patterns better, while Linear Regression provided baseline performance

## 🚀 Tech Stack
- Python 🐍
- pandas, numpy
- scikit-learn
- matplotlib, seaborn (for visualization)
