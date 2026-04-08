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
- Random Forest:   71.6% accuracy
                   71.3% precision
                   71.6% recall
                   71.1% F1
                   78.8% RMSE
                   36.7% MAE
   Training Time : 0.67 seconds
- Neural Network:  66.1% accuracy
                   67.8% precision
                   66.1% recall
                   66.8% F1
                   96.2% RMSE
                   48.4% MAE
   Training Time : 6.07 seconds
## Features Engineered
- StudyEfficiency
- SupportIndex
- ActivityScore

## How to Run
1. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn
2. Run:
   jupyter notebook Final_Project.ipynb
