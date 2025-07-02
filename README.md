# Flight Price Prediction – MLP Assignment 1

This repository contains my complete solution for **Assignment 1** of the **Machine Learning Practices (MLP)** course. The task was conducted as a Kaggle competition, where the objective is to predict flight ticket prices based on provided historical data.

---

## Assignment Overview

In this assignment, we were given a training dataset and a test dataset. The **labels for the test set were hidden**, and we had to **submit predicted prices** for the test data on Kaggle. The assignment is evaluated via a leaderboard based on model performance.

-  **Deadline**: July 2, 2025  
-  **Platform**: Kaggle Notebooks  
-  [Kaggle Competition Link](https://www.kaggle.com/t/1f1867586d484489bcc029150f4c0f1b)  
-  [Submission & Peer Review Guidelines](https://docs.google.com/document/d/e/2PACX-1vTGt489Zx6hsJUsAWXzsbPTpqnHPBrl7wtQkEoRkxGWptLTti53fOKtKpuZvLWpNva9KMarV-V25pUN/pub)  
-  [Submission Form](https://forms.gle/6shTk5CicYyZEBx59)

---

## Files Included

| File Name                                         | Description                                                        |
|--------------------------------------------------|--------------------------------------------------------------------|
| `mlp-flight-price-prediction-assignment-1.ipynb` | Kaggle Notebook containing full code, EDA, modeling, and results  |
| `video_walkthrough.mp4` *(Google Drive link below)* | A brief video walkthrough (under 10 min) explaining the notebook |
| `README.md`                                      | Project overview and instructions (this file)                      |

---

## Task & Methodology

### Key Steps Performed:
1. **Data Type Identification**  
2. **Descriptive Statistics of Numerical Columns**  
3. **Missing Value Handling**  
4. **Duplicate Removal**  
5. **Outlier Detection**  
6. **Data Visualization & Insight Extraction**  
7. **Feature Engineering**  
8. **Scaling Numerical Features & Encoding Categorical Variables**

---

## Models Trained

A minimum of 7 different models were trained on the dataset, including:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting  
- K-Nearest Neighbors  
- Support Vector Regression  
- XGBoost  

**Hyperparameter tuning** was performed on 3+ models using `GridSearchCV` and `RandomizedSearchCV`.

**Evaluation Metrics**:
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R² Score

---

## Walkthrough Video

A short video explaining the structure and thought process behind the notebook:  
**▶ [Watch Video on Google Drive](https://drive.google.com/file/d/1zlY3EcPFIIXW_j3ZhGd1gnK3C09rJzQu/view?usp=sharing)**

---

## Kaggle Notebook

**Notebook Link**:  
[Open on Kaggle](https://www.kaggle.com/code/dewanggandhi/mlp-flight-price-prediction-assignment-1)

---

## Author

**Dewang Gandhi**  
B.Tech Student | Machine Learning Enthusiast  
GitHub: [@dewanggandhi01](https://github.com/dewanggandhi01)  
Email: dewanggandhi01@gmail.com

---

## License

This project is intended for educational use only and submitted as part of an academic assignment. All rights reserved.
