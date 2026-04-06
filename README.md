# Student Marks Analysis using Python

This project analyzes a student marksheet dataset containing records of 250 students.
The dataset includes marks in four subjects — Science, English, History, and Maths.
The goal is to perform data analysis and find useful insights like top performers,
pass/fail ratio, grade distribution, and section-wise or gender-wise comparisons.

---

## Dataset

| Property | Details |
|----------|---------|
| File | marksheet.csv |
| Records | 250 students |
| Columns | id, Name, Gender, Age, Section, Science, English, History, Maths |

---

## Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Features

- Loads and explores the dataset
- Calculates Total marks and Percentage for each student
- Assigns Grades (A+, A, B, C, D, F) based on percentage
- Determines Pass or Fail result (student fails if below 33 in any subject)
- Finds each student's best subject
- Shows top 5 and bottom 5 students
- Section-wise and gender-wise performance comparison
- 5 different visualizations — bar chart, pie charts, histogram, grouped bar chart, box plot
- Exports the final result to student_report_final.csv

---

## How to Run

1. Download both files — `Student_Marks_Analysis.ipynb` and `marksheet.csv`
2. Place both files in the same folder
3. Open the notebook in Jupyter Notebook or VS Code
4. Run all cells from top to bottom

---
---

## Output Files

| File | Description |
|------|-------------|
| student_report_final.csv | Processed data with all new columns |
| chart1_subject_avg.png | Average marks per subject |
| chart2_pie.png | Pass/Fail and grade distribution |
| chart3_histogram.png | Percentage distribution of students |
| chart4_section_subjects.png | Section-wise subject performance |
| chart5_gender_box.png | Gender-wise percentage comparison |

---

## Author

Muawiyah  
DAIET Programme — Semester 6
