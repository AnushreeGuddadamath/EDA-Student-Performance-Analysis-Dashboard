# Student Performance Analysis Dashboard

## Project Overview

The Student Performance Analysis Dashboard is an interactive Streamlit-based Exploratory Data Analysis (EDA) project designed to identify the key factors influencing student academic performance. The project analyzes study habits, attendance, internet access, school type, parental education, travel time, and subject scores to uncover actionable insights that support data-driven educational decisions.

The dashboard helps educators and institutions identify top-performing students for scholarships, detect low-performing students requiring intervention, and understand the factors that contribute most to academic success.

---

##Project Objectives

- Analyze factors affecting student academic performance.
- Evaluate the impact of attendance and study habits on academic outcomes.
- Measure the influence of internet access on student achievement.
- Compare performance across different school types.
- Identify top-performing students for scholarships and rewards.
- Detect low-performing students requiring targeted interventions.
- Determine the strongest predictors of overall student success.
- Support educational institutions with data-driven decision making.

---

##Research Questions

1. Do study hours positively impact overall performance?
2. Does internet access improve academic outcomes?
3. Does attendance have a strong positive relationship with scores?
4. Does parental education influence student achievement?
5. Are Math scores mostly concentrated around the average range?
6. Do certain study methods lead to better scores?
7. Does school type impact student performance?
8. Do students with shorter travel times perform better?
9. How can top performers be identified for scholarships?
10. Are English scores evenly distributed among students?
11. How can low-performing students be targeted for intervention?
12. Do Math, Science, and English scores strongly affect overall scores?
13. Do Science scores indicate moderate to strong academic performance?
14. How can top-performing students be targeted for rewards and recognition?
15. Are subject scores, attendance, and study hours the strongest predictors of overall performance?

---

##Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Plotly
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##Dataset Features

The dataset includes information such as:

- Student ID
- Age
- Gender
- School Type
- Parent Education
- Study Hours
- Attendance Percentage
- Internet Access
- Travel Time
- Study Method
- Math Score
- Science Score
- English Score
- Overall Score
- Final Grade

---

##Dashboard Features

### 1. Study Hours vs Overall Score
Analyzes whether increasing study hours leads to improved academic performance.

### 2. Attendance vs Overall Score
Evaluates the relationship between attendance percentage and student achievement.

### 3. Internet Access Analysis
Compares academic performance between students with and without internet access.

### 4. Parental Education Impact
Examines whether parental education influences student outcomes.

### 5. Study Method Analysis
Compares different learning methods such as:
- Self Study
- Group Study
- Coaching
- Online Courses

### 6. Travel Time Analysis
Investigates whether commuting time affects academic performance.

### 7. School Type Comparison
Compares overall scores between Public and Private schools.

### 8. Scholarship Candidate Identification
Identifies top-performing students eligible for scholarship programs.

### 9. Student Intervention Analysis
Detects low-performing students requiring academic support.

### 10. Subject Performance Analysis
Analyzes distributions of:
- Math Scores
- Science Scores
- English Scores

### 11. Correlation Analysis
Determines the strongest factors influencing overall student performance.

---

##Key Insights

### Internet Access is a Major Performance Driver
Students with internet access perform significantly better than those without access.

### Private Schools Show Higher Performance
Private school students achieve higher average scores compared to public school students.

### Study Hours Have Minimal Impact
The number of study hours alone does not strongly influence academic performance.

### Attendance Shows Weak Correlation
Attendance alone is not a strong predictor of academic success.

### Subject Scores are the Strongest Predictors
Math, Science, and English scores show the strongest relationship with overall academic performance.

### Travel Time Has Negligible Effect
Commute duration has little to no impact on student scores.

### Group Study Shows Slight Advantage
Group Study demonstrates a marginally higher percentage of top performers compared to other study methods.

---

##Business Impact

This project helps educational institutions:

- Improve student performance monitoring.
- Identify scholarship candidates.
- Detect at-risk students early.
- Optimize academic intervention programs.
- Support evidence-based educational planning.
- Improve resource allocation and policy decisions.

---

##Installation

### Clone Repository

```bash
git clone https://github.com/your-username/student-performance-analysis-dashboard.git
cd student-performance-analysis-dashboard
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn plotly streamlit
```

### Run the Streamlit Application

```bash
streamlit run dashboard_app.py
```

---

##Project Structure

```text
Student-Performance-Analysis/
│
├── dashboard_app.py
├── Student_Performance_Analysis_Cleaned.csv
├── Student_Performance_EDA.ipynb
├── requirements.txt
├── README.md
│
├── images/
│   ├── dashboard.png
│   ├── insights.png
│
└── outputs/
    ├── charts
    ├── reports
```

---

##Future Enhancements

- Machine Learning Performance Prediction
- Student Risk Classification
- Scholarship Recommendation System
- Attendance Prediction Models
- Advanced Academic Analytics
- Cloud Deployment using Streamlit Community Cloud

---

## ⭐ Project Highlights

✔ Interactive Streamlit Dashboard  
✔ End-to-End Exploratory Data Analysis  
✔ Statistical Insights & Correlation Analysis  
✔ Scholarship Candidate Identification  
✔ Student Intervention Framework  
✔ Professional Data Visualization  
✔ Real-World Educational Analytics Use Case
