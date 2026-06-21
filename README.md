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



<img width="1761" height="407" alt="image" src="https://github.com/user-attachments/assets/45ae12f6-9d2b-4133-944d-9053495d62b4" />




---

## GENDER DISTRIBUTION

Displays male and female student distribution.





<img width="1756" height="419" alt="image" src="https://github.com/user-attachments/assets/619e4c30-53b6-40cc-8bcd-7df5438fc5cc" />





---

## STUDY HOURS DISTRIBUTION

Shows how study hours are distributed among students.




<img width="1767" height="412" alt="image" src="https://github.com/user-attachments/assets/0da0896a-10d1-4cbf-bc88-d35ced7f1e94" />




---

## ATTENDANCE RATE DISTRIBUTION

Displays attendance percentage distribution.



<img width="1765" height="423" alt="image" src="https://github.com/user-attachments/assets/c7fb5895-26f0-42ae-abcd-47934ae46665" />





---

## FINAL EXAM SCORE DISTRIBUTION

Shows the frequency distribution of final examination scores.



<img width="1762" height="420" alt="image" src="https://github.com/user-attachments/assets/74447715-9582-47ab-b62f-554302ba22c4" />




---

## STUDY HOURS VS FINAL EXAM SCORE

Illustrates the relationship between study hours and academic performance.



<img width="687" height="470" alt="image" src="https://github.com/user-attachments/assets/fcc59e53-43df-4a75-908b-2f67a6a39a07" />




---

## ATTENDANCE VS FINAL EXAM SCORE

Shows how attendance influences final examination scores.




<img width="687" height="470" alt="image" src="https://github.com/user-attachments/assets/a4f56a32-9913-46c5-b2c6-a62e05a2de12" />




---

## OUTLIER DETECTION

Identifies unusual student performance patterns using Box Plot.



<img width="1759" height="417" alt="image" src="https://github.com/user-attachments/assets/53c393d8-a8dc-4e26-8133-150902e3c0db" />





---

## CORRELATION HEATMAP

Displays relationships among numerical variables affecting academic performance.



<img width="1765" height="418" alt="image" src="https://github.com/user-attachments/assets/b4986d38-2683-4d4a-bcb8-10084f8806e9" />




---

## RISK DISTRIBUTION

Students are classified into:

* High Risk
* Medium Risk
* Low Risk

This helps institutions identify students requiring additional academic support.




<img width="1767" height="421" alt="image" src="https://github.com/user-attachments/assets/8fa0dd29-babc-4c08-a8ad-50b47183c225" />


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





<img width="404" height="309" alt="image" src="https://github.com/user-attachments/assets/2d7fbfa1-5ef2-49e6-8111-1fa7246d2d62" />






### ROC-AUC Score

Evaluates classification performance.

### ROC Curve

Visual representation of model effectiveness.



<img width="556" height="375" alt="image" src="https://github.com/user-attachments/assets/51232e59-cae0-4e3c-9fdb-a8d8a81b07aa" />




---

## DASHBOARD FEATURES

### Pass vs Fail Distribution

Interactive visualization of academic outcomes.



<img width="1762" height="410" alt="image" src="https://github.com/user-attachments/assets/abc6b709-2cc8-465a-9121-416a617a698a" />





### Study Hours Analysis

Interactive analysis of study habits.


<img width="1763" height="415" alt="image" src="https://github.com/user-attachments/assets/9a40c28c-9ed8-4693-bffa-433a61bff507" />


### Attendance Analysis

Interactive visualization of attendance patterns.



<img width="1761" height="417" alt="image" src="https://github.com/user-attachments/assets/78c5619f-0c85-4bbb-ad10-c11bb6332a14" />



### Gender-wise Performance

Comparison of academic performance by gender.


<img width="1762" height="424" alt="image" src="https://github.com/user-attachments/assets/b7d9a24c-884e-4d1e-8c90-b2158977c090" />




### Internet Access Impact

Analyzes the effect of internet availability on student success.

### Student Risk Dashboard

Displays student risk categories for academic intervention.



<img width="1769" height="408" alt="image" src="https://github.com/user-attachments/assets/8058174a-8408-4ba9-b98b-f797bcf7a772" />




### Interactive Correlation Heatmap

Visual exploration of relationships among variables.



<img width="1764" height="416" alt="image" src="https://github.com/user-attachments/assets/0a9f99c4-e67d-473f-8ae6-dd7a7745e6be" />





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
