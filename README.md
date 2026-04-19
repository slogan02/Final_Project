# Final_Project

# Student Performance Classification Model

## Overview
This project predicts student academic performance using a multi-class classification approach. The target variable, GradeClass, groups students into A–F categories based on significant factors.

## Dataset
Source: Kaggle Student Performance Dataset  
https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset 
- 2,391 students  
- 15 features  
- Target: GradeClass (0–4)

## Models
- Random Forest Classifier
- Neural Network

## Results
- Random Forest:   71.12% accuracy,
                   71.23% precision,
                   71.12% recall,
                   70.74% F1,
                   80.06% RMSE,
                   37.37% MAE,
   Training Time : 2.423443 seconds
  
- Neural Network:  70.56% accuracy,
                   69.69% precision,
                   70.56% recall,
                   70.05% F1,
                   81.73% RMSE,
                   37.99% MAE,
   Training Time : 1.099335 seconds
  
## Features Engineered
- StudyEfficiency
- TotalSupport
- ActivityScore
- SupportPerActivity
- RiskScore

## Key Insights
Attendance, risk score, and study effificiency are the strongest predictors of student performance
Engineered features improved model accuracy and interpretability
Random Forest outperformed Neural Network due to dataset size and structure

## Final Recommendation

The Random Forest model is recommended for deployment due to its superior accuracy, efficiency, and interpretability, making it well-suited for educational decision support.

## How to Run
1. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn
2. Run:
   jupyter notebook Final_Project.ipynb
