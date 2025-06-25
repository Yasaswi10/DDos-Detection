# DDoS Attack Detection using Machine Learning and Hybrid Feature Selection (HFSA)

## 🔍 Project Overview

This project focuses on detecting and classifying **Distributed Denial of Service (DDoS)** attacks in IoT environments using various **Machine Learning (ML)** models. The objective is to build a highly accurate system capable of classifying multiple types of attacks efficiently.

We began with **46 features** from the dataset. To enhance performance and reduce complexity, we applied a **Hybrid Feature Selection Approach (HFSA)** — a combination of **Random Forest** and **Chi-Square** feature ranking — and selected the top **20 most relevant features**. This significantly improved model performance.

## 🚀 Key Highlights

- **ML Algorithms Used**:
  - **K-Nearest Neighbors (KNN)**
  - **Random Forest (RF)**
  - **XGBoost**
  - **Decision Tree**

- **Feature Selection**:
  - Started with all **46 features**
  - Applied **HFSA (Random Forest + Chi-Square)**
  - Best results obtained using top **20 selected features**

- **Dataset**:
  - Multi-class classification with **12 attack classes**

## 🧠 Models Summary

| Model           | Description                                        |
|----------------|----------------------------------------------------|
| KNN             | Distance-based classification algorithm            |
| Random Forest   | Ensemble learning using multiple decision trees    |
| XGBoost         | Gradient boosting with high accuracy               |
| Decision Tree   | Tree-based classification with low complexity      |
| HFSA (RF + Chi²)| Hybrid feature selection method combining filters  |

## 📊 Performance (Best Case)

- **Model**: **XGBoost**
- **Features Used**: 20 (from HFSA)
- **Classes**: 12

| Metric       | Value      |
|--------------|------------|
| Accuracy     | **99.95%** |
| Precision    | **99.95%** |
| Recall       | **99.95%** |
| F1 Score     | **99.95%** |
