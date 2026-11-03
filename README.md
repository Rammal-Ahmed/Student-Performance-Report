# Student Performance Report

A Python-based student assessment application designed to calculate academic performance, evaluate examination results, and generate a structured student report.

Built as a practical Python project, it brings together fundamental programming concepts to process student marks, calculate performance statistics, assign grades, and determine examination results.

---

## Overview

The Student Performance Report is a console-based application that evaluates a student's academic performance across five subjects: Chemistry, Mathematics, Physics, English, and Science.

The program collects the student's name, roll number, and obtained marks in each subject. It then calculates the total marks, average, overall percentage, highest and lowest subject scores, and assigns a grade based on predefined grading criteria.

Finally, it evaluates the student's pass or fail status and displays the results in a structured performance report.

## Features

- Student information input
- Individual subject marks collection
- Automatic total marks calculation
- Average marks calculation
- Overall percentage calculation
- Automatic grade assignment
- Highest subject marks identification
- Lowest subject marks identification
- Pass/fail result evaluation
- Formatted student performance report
- Percentage display up to two decimal places

---

## Subjects & Evaluation

The application evaluates student performance across the following five subjects:

| No. | Subject |
|---:|---|
| 1 | Chemistry |
| 2 | Mathematics |
| 3 | Physics |
| 4 | English |
| 5 | Science |

The overall percentage is calculated using the following formula:

**Percentage = (Total Obtained Marks / 550) × 100**

The average is calculated by dividing the total obtained marks by the five subjects.

---

## Grading Criteria

The application assigns grades according to the student's overall percentage.

| Percentage | Grade |
|---|---|
| 85% or above | A |
| 70% – 84.99% | B |
| 60% – 69.99% | C |
| 50% – 59.99% | D |
| Below 50% | F |

## Passing Criteria

The passing percentage is set to 40%.

| Percentage | Examination Result |
|---|---|
| 40% or above | Pass |
| Below 40% | Fail |

The grade and examination result are evaluated separately according to the implemented conditions.

---

## Technologies & Concepts

**Programming Language:** Python 3

**Core Concepts Used:**

- Variables and data types
- User input using `input()`
- Type conversion using `int()` and `float()`
- Conditional statements (`if`, `elif`, `else`)
- Arithmetic operations
- Built-in functions (`max()`, `min()`)
- Percentage and average calculations
- String formatting using `.center()` and `.format()`
- Formatted output using f-strings
- Logical decision-making

No external Python libraries are required.

---

## Sample Run

### Student Input

```text
Enter Student Name: Ahmed Khan
Enter Roll No: 1024
Enter your Chemistry obtained marks: 85
Enter your Maths obtained marks: 90
Enter your Physics obtained marks: 78
Enter your English obtained marks: 88
Enter your Science obtained marks: 92
```

### Generated Performance Report

```text
----------------------------------------
       STUDENT PERFORMANCE REPORT
----------------------------------------

Student Name:  Ahmed Khan
Roll No:  1024
Total Marks:  433
Average Marks:  86.6
Percentage:  78.73%
Grade:  B
Passing Percentage: 40%
Highest Marks:  92
Lowest Marks:  78
Result:  Congratulations, You Pass the exam

========================================
    SEE YOU IN THE NEXT REPOSITORIES..!
========================================
```

---

## Getting Started

### Requirements

- Python 3
- Google Colab, Jupyter Notebook, VS Code, or another Python-compatible IDE
- No additional package installation required

### Installation & Execution

**1. Clone the repository**

```bash
git clone https://github.com/your-username/STUDENT-PERFORMANCE-REPORT.git
```

**2. Navigate to the project directory**

```bash
cd STUDENT-PERFORMANCE-REPORT
```

**3. Run the Python application**

```bash
python student_performance_report.py
```

Follow the on-screen prompts to enter student details and obtained marks for each subject.

---

## Project Structure

```text
STUDENT-PERFORMANCE-REPORT/
│
├── student_performance_report.py
├── README.md
└── LICENSE
```

An optional Jupyter Notebook version can also be included:

```text
STUDENT-PERFORMANCE-REPORT/
│
├── student_performance_report.py
├── STUDENT_PERFORMANCE_REPORT.ipynb
├── README.md
└── LICENSE
```

---

## Learning Objectives

This project provides practical experience in applying Python fundamentals to an academic performance evaluation scenario.

The main focus is on:

- Processing student information and subject marks
- Performing total and average calculations
- Calculating percentages using mathematical expressions
- Applying conditional grading criteria
- Evaluating pass and fail conditions
- Identifying maximum and minimum values using built-in functions
- Formatting numerical results for better readability
- Organizing calculated information into a structured report

---

## Future Improvements

Potential enhancements to the application include:

- Adding input validation for student details and subject marks
- Supporting multiple student records
- Generating class performance summaries
- Maintaining student records in files
- Adding subject-wise grade evaluation
- Introducing automatic report generation
- Improving report formatting and customization

---

## Author

**Rammal Ahmed**

AI & Data Science Enthusiast | Microsoft Dynamics 365 CRM Developer | Power Platform | UI/UX Designer | Graphic Designer & Illustrator

[LinkedIn] www.linkedin.com/in/rammal-ahmed-58184b325 · [GitHub] https://github.com/Rammal-Ahmed

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Project Status:** Completed
