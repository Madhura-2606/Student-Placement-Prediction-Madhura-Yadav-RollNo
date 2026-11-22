# Student-Placement-Prediction-Madhura-Yadav-RollNo
Machine Learning project to predict engineering students' placement status using Logistic Regression. The project analyzes academic performance, technical skills, internships, projects, and other student-related features using Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn. The model achieved 80.6% accuracy on the test dataset.

# Student Placement Prediction Using Machine Learning

## Project Description

This project, **Student Placement Prediction Using Machine Learning**, aims to predict whether an engineering student will get placed or not using Machine Learning techniques.

The project uses student academic performance, technical skills, communication skills, internships, projects, extracurricular activities, and other relevant features to predict placement status.

A Logistic Regression classification algorithm is used to build the prediction model.

## Student Information

| Details | Information |
|---|---|
| Student Name | Madhura Yadav |
| Roll Number | Not provided |
| Project Title | Student Placement Prediction Using Machine Learning |
| Algorithm | Logistic Regression |
| Programming Language | Python |
| Notebook | Untitled.ipynb |

## Objectives

- To analyze engineering student placement data.
- To perform data preprocessing and cleaning.
- To identify important student-related features.
- To understand placement trends through data visualization.
- To build a Machine Learning classification model.
- To predict whether a student is placed or not.
- To evaluate the performance of the trained model.

## Dataset Information

**Dataset Name:** `indian_engineering_placement_2026.csv`

**Dataset Size:**
- Total Records: 15,000
- Total Features: 25
- Target Variable: `Placement_Status`

### Dataset Features

The dataset contains the following information:

- Student ID
- Age
- Gender
- State
- Engineering Branch
- College Tier
- CGPA
- Attendance Percentage
- DSA Problems Solved
- Aptitude Score
- Communication Score
- Projects Count
- Internships Count
- Certifications Count
- Open Source Contributions
- GitHub Contributions
- LinkedIn Activity Score
- Hackathons Participated
- Competitive Programming Rating
- Study Hours Per Week
- Soft Skills Score
- Leadership Experience
- Extracurricular Activities
- Placement Status
- Package LPA

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Implementation

The following steps were performed in this project:

### 1. Data Loading
Imported the required Python libraries and loaded the engineering placement dataset using Pandas.

### 2. Data Exploration
- Displayed the first five records.
- Checked dataset dimensions.
- Examined column names and data types.
- Generated descriptive statistics.

### 3. Data Cleaning
- Checked missing values.
- Identified missing values in Open Source Contributions and LinkedIn Activity Score.
- Checked duplicate records.
- No duplicate records were found.

### 4. Exploratory Data Analysis
Analyzed student-related features to understand the dataset and placement information.

### 5. Data Preprocessing
Prepared the dataset for Machine Learning by handling categorical and numerical features.

### 6. Model Building
Used Logistic Regression from Scikit-learn to develop a classification model.

### 7. Model Evaluation
Evaluated the model using:
- Accuracy Score
- Confusion Matrix
- Classification Report

## Machine Learning Algorithm

### Logistic Regression

Logistic Regression is a supervised Machine Learning algorithm used for classification problems.

In this project, it predicts two possible placement categories:

- **Placed**
- **Not Placed**

The algorithm uses student-related features to estimate the placement outcome.

## Key Results

The model performance recorded for this project is:

| Evaluation Metric | Result |
|---|---:|
| Accuracy | 80.60% |
| Placed Precision | 0.84 |
| Placed Recall | 0.87 |
| Placed F1-Score | 0.85 |
| Not Placed Precision | 0.74 |
| Not Placed Recall | 0.69 |
| Not Placed F1-Score | 0.71 |

### Confusion Matrix

```text
[[724  322]
 [260 1694]]
```

The Logistic Regression model achieved **80.60% accuracy** on the test dataset.

## Sample Prediction

The trained model was used to predict the placement status of a sample student.

**Predicted Result:** Placed

Predicted probabilities:

- Not Placed: 1.37%
- Placed: 98.63%

## Conclusion

This project demonstrates the application of Machine Learning in predicting engineering student placement outcomes.

Using the Logistic Regression algorithm, the model achieved 80.60% accuracy.

The project provides practical experience in Python programming, data analysis, data preprocessing, exploratory data analysis, classification algorithms, and model evaluation.

It also demonstrates how student academic performance and skill-related information can be used for placement prediction.

## Project Files

The GitHub repository contains the following project files:

1. `Untitled.ipynb` – Jupyter Notebook containing the project implementation.
2. `README.md` – Project description, objectives, dataset information, methodology, and results.
3. `indian_engineering_placement_2026.csv` – Dataset used in the project, if permitted for public sharing.

## Faculty Submission GitHub ID

[https://github.com/complexiota](https://github.com/complexiota)

## Author

**Madhura Yadav**

Project: Student Placement Prediction Using Machine Learning

---

*This project is developed for academic purposes as part of a Regression and Classification Algorithms activity.*
