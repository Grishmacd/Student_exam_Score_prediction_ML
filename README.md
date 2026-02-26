# Student_exam_Score_prediction_ML

This project builds a **Machine Learning regression model** to predict student exam scores using academic and lifestyle factors.  
It demonstrates a complete beginner-friendly ML pipeline using Python and Scikit-learn.

Workflow followed:

Problem Statement → Data Creation → Basic EDA → Train/Test Split → Model Training → Evaluation → Prediction

---

## Problem Statement

To predict a student’s exam score based on measurable inputs so that performance trends can be estimated in advance.

### Input Features
- Study_Hours  
- Attendance (%)  
- Sleep_Hours  

### Output
- Predicted Exam Score  

---

## Dataset

- Structured numeric dataset created inside the code  
- Converted into a Pandas DataFrame  
- Small sample dataset for demonstration  
- Can easily be replaced with a real CSV dataset  

---

## Basic EDA

- Displayed dataset preview using `df.head()`  
- Verified feature columns and target column  
- Observed general value ranges before training  

---

## Train-Test Split

Used:

- `test_size = 0.2` (80% training, 20% testing)  
- `random_state = 42` (ensures reproducibility)  

Training data → Model learns patterns  
Testing data → Model performance evaluation  

---

## Model Used

**Linear Regression**  
`sklearn.linear_model.LinearRegression`

Why this model:
- Simple and fast regression algorithm  
- Good baseline model for numeric prediction  
- Interpretable relationship between inputs and output  

---

## Evaluation Metrics

### Mean Squared Error (MSE)
Measures average squared prediction error.

### R² Score
Indicates how well the model explains score variation.  
Higher R² → Better model performance.

---

## Visualization

A scatter plot compares:

- Actual Scores  
- Predicted Scores  

Helps visually validate prediction accuracy.

---

## Output

- Printed MSE and R² Score  
- Actual vs Predicted comparison table  
- Scatter plot visualization  
- Predicted score for new student input `[7, 85, 8]`  

---

## Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Developer

**Grishma C.D**
