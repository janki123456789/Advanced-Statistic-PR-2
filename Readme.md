# 📘 Student Performance Probability Analysis  
## Probability, Conditional Probability & Bayesian Analysis (Python)

---

## 📌 Project Overview
This project is a **probability and statistics analysis** performed on a **student performance dataset** using Python.  
The analysis is implemented in a Jupyter Notebook and focuses on understanding how **study hours, attendance, and group discussions** influence **final exam results**.

The project combines:
- Probability theory
- Dataset-based calculations
- Visual interpretation
- Logical reasoning using statistics

---

## 🎯 Objective
The main objective of this project is to apply **probability concepts on a real dataset** and build intuition about:

- Student performance patterns
- Relationship between academic behaviors and exam results
- Conditional probability and dependence
- Bayesian reasoning using historical information

All analysis is done **based on the given dataset** and shown clearly in the notebook.

---

## 🗂 Dataset Description
The dataset (`student_dataset.csv`) contains academic and behavioral information of students.

### 📌 Key Columns Used in Analysis
- `study_hours` – Weekly study hours of students  
- `attendance_percentage` – Class attendance percentage  
- `group_discussion` – Participation in group discussions (Yes/No)  
- `final_exam_result` – Exam result (Pass/Fail)  

### 🔗 Dataset Link
[student_dataset.csv](student_dataset.csv)

---

## 🧠 Analysis Performed (Based on PR-2.ipynb)

### 1️⃣ Understanding Probability Basics
- Explained **probability** using student-related examples
- Defined key terminology:
  - Experiment
  - Sample Space
  - Event
  - Outcome
- Dataset-based probability examples:
  - Probability that a student **passes the exam**
  - Probability that a student has **attendance > 80%**
  - Probability that a student **studies more than 10 hours/week**

---

### 2️⃣ Empirical vs Theoretical Probability
- **Empirical Probability** calculated directly from dataset frequencies
- **Theoretical Probability** explained using assumed equal likelihood
- Comparison between real data results and theoretical expectations

---

### 3️⃣ Random Variable & Probability Distribution
- Defined random variable:
  > **X = Number of students passing the final exam out of 3 randomly selected students**
- Constructed probability distribution table for X
- Calculated:
  - Mean (Expected Value)
  - Variance
- Interpretation based on exam pass probability

---

### 4️⃣ Venn Diagram Analysis
A Venn diagram is used to visualize:
- Students studying **more than 10 hours per week**
- Students having **attendance greater than 80%**
- Intersection representing students satisfying **both conditions**

#### 🖼 Venn Diagram Output
![Vennchart](vennchart.png)

This visualization helps in understanding **overlapping academic behaviors**.

---

### 5️⃣ Contingency Table & Probability Calculations
A contingency table is created using:
- `group_discussion` (Yes / No)
- `final_exam_result` (Pass / Fail)

From this table, the following probabilities are calculated:
- **Joint Probability**  
  P(Group Discussion AND Pass)
- **Marginal Probability**  
  P(Pass)
- **Conditional Probability**  
  P(Pass | Group Discussion)

All values are calculated directly from the dataset.

---

### 6️⃣ Relationship Between Events
- Conditional probability results are interpreted in **simple language**
- Determined whether:
  - Group discussion participation and passing exam are  
    **Independent or Dependent events**
- Justification is provided using probability rules

---

### 7️⃣ Bayes’ Theorem Application
Using given historical probabilities:
- P(High Attendance | Pass)
- P(High Attendance | Fail)
- P(High Attendance)

Bayes’ Theorem is applied to compute:
- **P(Pass | High Attendance)**

This section demonstrates **decision-making under uncertainty**.

---

## 📈 Visual Outputs
- Venn Diagram (Study Hours vs Attendance)
- Probability Distribution Tables
- Contingency Tables
- Step-by-step calculations in notebook

---

## 🛠 Tools & Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook  
- GitHub  

## Author

Janki Dholariya
