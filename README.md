# Predicting User Knowledge Levels Through Study Habits and Exam Performance

A machine learning project analyzing the *User Knowledge Modeling* dataset from the UCI Machine Learning Repository to predict students’ knowledge levels on Electrical DC Machines. The dataset includes study habits and exam performance metrics for 403 students.

## Objective
Predict whether a student’s knowledge level is **very low, low, middle, or high** based on:
- **STG**: Study time for goal object materials
- **SCG**: Repetition number for goal object materials
- **PEG**: Exam performance for goal objects
- **STR**: Study time for related objects
- **LPR**: Exam performance for related objects

## Methods
- **Data preprocessing**: Column selection, encoding, and scaling
- **Modeling**: Bayesian classifier, K-Nearest Neighbors, and an intuitive classifier (custom approach)
- **Evaluation**: Cross-validation, confusion matrix visualization
- **Tools**: Python, pandas, scikit-learn, Altair

## Results
- The intuitive classifier outperformed both the Bayesian classifier and KNN
- Key predictors included exam performance metrics (**PEG**, **LPR**) and study repetition (**SCG**)

## How to Run
1. Clone the repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
