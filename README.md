# 📊 Student Performance Analysis & Prediction

A machine learning project that predicts a student's final marks from study habits and past performance, using **Linear Regression**.

## Problem
Can a student's final marks be predicted from how much they study, how regularly they attend, and how they scored before?

## Dataset
- 20 students (small learning dataset)
- Features: `Study Hours`, `Attendance`, `Previous Marks`
- Target: `Final Marks`
- Files: `student_data.csv` (raw), `student_performance_final.csv` (processed)

## Approach
1. Loaded and explored the data with **Pandas**
2. Visualised relationships between each feature and final marks with **Matplotlib**
3. Split the data into training and test sets 
4. Trained a **Linear Regression** model with **scikit-learn**
5. Evaluated it on the test set

## Results
| Metric | Value |
|---|---|
| MAE | 0.65 |
| R² Score | 0.98 |

## Limitations
The dataset has only 20 records, so these results may not generalise. Future work: use a larger dataset and cross-validation.

## Tech Stack
Python · Pandas · Matplotlib · scikit-learn · Jupyter Notebook

## How to Run
```bash
git clone https://github.com/omkar2304-git/Student-Performance-Analysis.git
cd Student-Performance-Analysis
pip install pandas matplotlib scikit-learn jupyter
jupyter notebook student_performance.ipynb
```

## Author
Omkar Tasnuse · [LinkedIn](https://www.linkedin.com/in/omkar-m-tasnuse-a787b7395/)
