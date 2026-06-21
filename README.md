# STUDENT EXAM PASS PREDICTION SYSTEM (LOGISTIC REGRESSION)

---

## PROJECT OVERVIEW

The **Student Exam Pass Prediction System** is an educational analytics project that analyzes student academic performance data using **Exploratory Data Analysis (EDA)**, **Logistic Regression**, and **Interactive Dashboard Visualization** techniques.

This project studies important student-related factors such as **study hours, attendance rate, past exam scores, parental education level, internet access, extracurricular activities, and final examination scores** using a real-world student performance dataset obtained from Kaggle.

The system helps educational institutions identify students who are at risk of failing examinations, understand academic performance patterns, support early intervention strategies, and improve overall student success through predictive analytics and visualization.

---

## PROBLEM STATEMENT

Educational institutions collect large amounts of student-related data. However, manually analyzing this information to identify students who may fail examinations is difficult, time-consuming, and inefficient.

Students with low attendance, poor study habits, low previous academic performance, or limited educational support may struggle academically.

Incorrect identification of student performance can result in:

* Increased failure rates
* Poor academic outcomes
* Delayed intervention by teachers
* Reduced student confidence
* Lower institutional performance

Therefore, there is a need for an automated system that can analyze student data, identify at-risk students, and predict pass/fail outcomes efficiently.

---

## DATASET DESCRIPTION

| COLUMN NAME                | DESCRIPTION                                 |
| -------------------------- | ------------------------------------------- |
| Student_ID                 | Unique identifier for each student          |
| Gender                     | Gender of student                           |
| Study_Hours_per_Week       | Average study hours per week                |
| Attendance_Rate            | Attendance percentage                       |
| Past_Exam_Scores           | Average score of previous exams             |
| Parental_Education_Level   | Education level of parents                  |
| Internet_Access_at_Home    | Internet availability at home               |
| Extracurricular_Activities | Participation in extracurricular activities |
| Final_Exam_Score           | Final examination score                     |
| Pass_Fail                  | Pass/Fail Status                            |

**Dataset Source:** Kaggle

**Dataset Name:** Student Performance Prediction Dataset

**Dataset Link:** https://www.kaggle.com/datasets/amrmaree/student-performance-prediction

---

## PROJECT OBJECTIVES

* Load and analyze the student performance dataset
* Perform data cleaning and preprocessing
* Handle missing values and duplicates
* Calculate descriptive statistics
* Analyze student academic behavior
* Study attendance and study habit patterns
* Identify factors influencing academic success
* Classify students based on risk levels
* Build a Logistic Regression model
* Evaluate model performance
* Create an interactive dashboard using Plotly
* Generate academic insights for decision-making

---

## LIBRARIES USED

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-Learn

---

## DATA CLEANING STEPS

* Loaded dataset from Kaggle
* Checked missing values using `isnull()`
* Removed duplicate records
* Verified data types
* Encoded categorical variables using Label Encoding
* Removed Student_ID column from modeling
* Applied feature scaling using StandardScaler
* Prepared dataset for machine learning and visualization

---

## DATA ANALYSIS PERFORMED

### Descriptive Statistics

* Average Study Hours per Week
* Average Attendance Rate
* Average Past Exam Score
* Average Final Exam Score
* Pass vs Fail Student Count
* Gender-wise Student Distribution

### Student Performance Analysis

* Pass vs Fail Comparison
* Study Hours Analysis
* Attendance Analysis
* Past Exam Score Analysis
* Internet Access Impact
* Extracurricular Activity Impact

### Group-Based Analysis

* Study Hours vs Pass/Fail
* Attendance vs Pass/Fail
* Past Scores vs Pass/Fail
* Gender vs Performance
* Internet Access vs Pass Rate
* Parental Education vs Student Performance
* Extracurricular Activities vs Performance

### Relationship Analysis

* Study Hours vs Final Exam Score
* Attendance vs Final Exam Score
* Past Exam Scores vs Final Exam Score
* Correlation Analysis
* Academic Performance Trends

### Risk Analysis

* High Risk Students
* Medium Risk Students
* Low Risk Students
* Early Identification of At-Risk Students

### Predictive Modeling

* Logistic Regression Model
* Pass/Fail Prediction
* Probability Prediction
* Model Evaluation

---

## DATA VISUALIZATION

| CHART            | PURPOSE                       | GRAPH UNDERSTANDING                 |
| ---------------- | ----------------------------- | ----------------------------------- |
| Bar Chart        | Pass vs Fail Distribution     | Shows academic success distribution |
| Pie Chart        | Gender Distribution           | Displays gender-wise student count  |
| Histogram        | Study Hours Distribution      | Study habits analysis               |
| Histogram        | Attendance Distribution       | Attendance pattern analysis         |
| Histogram        | Final Exam Score Distribution | Academic performance distribution   |
| Scatter Plot     | Study Hours vs Final Score    | Relationship analysis               |
| Scatter Plot     | Attendance vs Final Score     | Performance analysis                |
| Box Plot         | Final Exam Score              | Outlier detection                   |
| Heatmap          | Correlation Matrix            | Variable relationship analysis      |
| Pie Chart        | Risk Distribution             | Student risk classification         |
| Confusion Matrix | Model Evaluation              | Prediction accuracy analysis        |
| ROC Curve        | Classification Performance    | Model effectiveness evaluation      |

---

## PASS VS FAIL DISTRIBUTION

Shows the number of students who passed and failed examinations.

---

## GENDER DISTRIBUTION

Displays male and female student distribution.

---

## STUDY HOURS DISTRIBUTION

Shows how study hours are distributed among students.

---

## ATTENDANCE RATE DISTRIBUTION

Displays attendance percentage distribution.

---

## FINAL EXAM SCORE DISTRIBUTION

Shows the frequency distribution of final examination scores.

---

## STUDY HOURS VS FINAL EXAM SCORE

Illustrates the relationship between study hours and academic performance.

---

## ATTENDANCE VS FINAL EXAM SCORE

Shows how attendance influences final examination scores.

---

## OUTLIER DETECTION

Identifies unusual student performance patterns using Box Plot.

---

## CORRELATION HEATMAP

Displays relationships among numerical variables affecting academic performance.

---

## RISK DISTRIBUTION

Students are classified into:

* High Risk
* Medium Risk
* Low Risk

This helps institutions identify students requiring additional academic support.

---

## MODEL EVALUATION

### Accuracy Score

Measures overall prediction accuracy.

### Precision

Measures correctness of positive predictions.

### Recall

Measures model ability to identify actual passing students.

### F1 Score

Balances Precision and Recall.

### Confusion Matrix

Displays correct and incorrect predictions.

### ROC-AUC Score

Evaluates classification performance.

### ROC Curve

Visual representation of model effectiveness.

---

## DASHBOARD FEATURES

### Pass vs Fail Distribution

Interactive visualization of academic outcomes.

### Study Hours Analysis

Interactive analysis of study habits.

### Attendance Analysis

Interactive visualization of attendance patterns.

### Gender-wise Performance

Comparison of academic performance by gender.

### Internet Access Impact

Analyzes the effect of internet availability on student success.

### Student Risk Dashboard

Displays student risk categories for academic intervention.

### Interactive Correlation Heatmap

Visual exploration of relationships among variables.

### Dynamic Data Exploration

Allows users to interactively analyze student performance data.

---

## TECHNOLOGIES USED

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-Learn
* Google Colab / Jupyter Notebook

---

## EXPECTED OUTCOME

* Predict student pass/fail outcomes accurately
* Identify at-risk students early
* Improve academic intervention strategies
* Understand factors affecting student success
* Support data-driven educational decisions
* Enhance institutional performance
* Increase overall student success rates

---

## CONCLUSION

This project demonstrates how student performance data can be analyzed using **Python**, **EDA**, **Machine Learning**, and **Data Visualization Techniques**.

By applying **Logistic Regression**, **Risk Classification**, **Interactive Dashboards**, and **Performance Analytics**, the system transforms raw educational data into meaningful academic insights.

The project helps educational institutions identify struggling students early, improve intervention strategies, enhance academic planning, increase pass rates, and support evidence-based educational decision-making.
