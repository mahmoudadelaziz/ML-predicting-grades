# Student Exam Score Prediction with Linear Regression

This repository contains a simple linear regression model developed using the scikit-learn package to predict students' exam scores based on various attributes. The model is trained on two datasets: student-mat.csv (Math course) and student-por.csv (Portuguese language course).

## Dataset Features

Both datasets share the following attributes:

- **school**: Student's school ('GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
- **sex**: Student's sex ('F' - female or 'M' - male)
- **age**: Student's age (numeric: from 15 to 22)
- **address**: Student's home address type ('U' - urban or 'R' - rural)
- **famsize**: Family size ('LE3' - less or equal to 3 or 'GT3' - greater than 3)
- **Pstatus**: Parent's cohabitation status ('T' - living together or 'A' - apart)
- **Medu**: Mother's education (numeric: 0 - none, 1 - primary education to 4 - higher education)
- **Fedu**: Father's education (numeric: 0 - none, 1 - primary education to 4 - higher education)
- **Mjob**: Mother's job (nominal: 'teacher', 'health', 'services', 'at_home', 'other')
- **Fjob**: Father's job (nominal: 'teacher', 'health', 'services', 'at_home', 'other')
- ... (and more features)

## Course Grades (Targets)

The scores G1, G2, and G3 are the target variables for prediction, related to the course subject (Math or Portuguese):

- **G1**: First period grade (numeric: from 0 to 20)
- **G2**: Second period grade (numeric: from 0 to 20)
- **G3**: Final grade (numeric: from 0 to 20, output target)

## Dataset Source
The datasets used in this project are available from the UCI Machine Learning Repository. [Find the dataset here.](https://archive.ics.uci.edu/dataset/320/student+performance)

## Usage

The Jupyter Notebook files provided in this repository demonstrate the steps involved in data preprocessing, model training using linear regression, and evaluation of the predictive performance. The `student-mat.csv` and `student-por.csv` datasets are included for reference.

## Requirements

To run the code, ensure you have:
- Python installed
- JuPyter Notebooks
- Necessary libraries: `sklearn`, `NumPy`, `pandas`, `matplotlib`, and `seaborn`

## About This Project

This project serves as personal training and learning in machine learning and data analysis, focusing on predicting students' exam scores.

## How to Contribute

Contributions, feedback, and suggestions are welcome! Feel free to open issues or pull requests.
