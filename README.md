# Student Performance Analysis Using Python

## 1. Project Overview

The **Student Performance Analysis** project uses Python and data analysis techniques to investigate student academic performance.

Educational institutions collect student data such as study hours, attendance, assignment scores, and final examination results. However, analyzing these records is necessary to understand performance patterns and identify students who may need additional academic support.

This project explores the relationships between these variables, examines overall academic performance, and identifies patterns that may help educators make more informed decisions.

The project also demonstrates the importance of data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization in solving real-world problems.

> **Note:** This project uses a synthetic dataset created for educational and portfolio purposes. It does not contain real student records.

---

## 2. Business Problem

Educational institutions need to understand the factors associated with student academic performance so they can identify students who may require additional academic support.

However, student records may contain information about study hours, attendance, assignment scores, and final examination results without a clear understanding of how these variables relate to one another.

This project investigates these relationships to uncover useful patterns and develop data-driven recommendations that could support academic improvement.

---

## 3. Project Objectives

The main objectives of this project are to:

* Assess overall student academic performance.
* Calculate average, median, minimum, and maximum examination scores.
* Determine the percentage of students who pass and achieve high scores.
* Investigate the relationship between study hours and final examination scores.
* Examine the relationship between attendance and academic performance.
* Investigate whether high assignment scores are associated with high final examination scores.
* Compare academic performance across different age groups and gender categories.
* Identify missing values, duplicate records, inconsistent categories, and invalid observations.
* Create visualizations to communicate important findings.
* Develop evidence-based recommendations based on the analysis.

---

## 4. Research Questions

The analysis will address the following questions.

### A. Overall Academic Performance

1. What is the average final examination score?
2. What is the median final examination score?
3. What are the minimum and maximum final examination scores?
4. What percentage of students scored at least 70?
5. What percentage of students passed the examination?
6. How are final examination scores distributed?

### B. Study Hours and Academic Performance

1. Is there an association between study hours and final examination scores?
2. Do students who study for more hours generally achieve higher scores?
3. How do average scores differ among students with different study-hour patterns?
4. Are there students who study for many hours but still achieve low scores?

### C. Attendance and Academic Performance

1. Is attendance associated with final examination scores?
2. How do students with attendance below 80% compare with those whose attendance is at least 80%?
3. Are there students with high attendance but low examination scores?
4. Are there students with low attendance but high examination scores?

### D. Assignment Scores and Final Examination Scores

1. Are high assignment scores associated with high final examination scores?
2. What is the relationship between assignment scores and final examination scores?
3. Are there students who perform well in assignments but poorly in final examinations?

### E. Demographic Analysis

1. How does average academic performance vary across age groups?
2. Are there differences in average examination scores across gender categories?

Demographic comparisons will be interpreted carefully and will not be treated as evidence that gender or age causes differences in academic performance.

### F. Data Quality Assessment

1. Does the dataset contain missing values?
2. Are there duplicate records?
3. Are categorical values recorded inconsistently?
4. Are there invalid or implausible observations?
5. How should data quality issues be handled before analysis?

---

## 5. Dataset Description

The project uses a synthetic student performance dataset containing approximately 500 original student records, with additional duplicate rows deliberately introduced for data-cleaning practice.

The raw dataset contains **508 rows and 10 columns**.

### Dataset Columns

| Column             | Description                                 |
| ------------------ | ------------------------------------------- |
| `Student_ID`       | Unique identifier intended for each student |
| `Student_Name`     | Student's name                              |
| `Gender`           | Recorded gender category                    |
| `Class`            | Class assigned to the student               |
| `Year_of_Study`    | Student's year of study                     |
| `Age`              | Student's age                               |
| `Study_Hours`      | Number of hours spent studying              |
| `Attendance`       | Student attendance percentage               |
| `Assignment_Score` | Student's assignment score                  |
| `Final_Score`      | Student's final examination score           |

### Data Quality Challenges

The dataset deliberately contains data quality issues to simulate problems that data analysts may encounter in real-world datasets.

These include:

* Missing values.
* Duplicate records.
* Inconsistent categorical labels.
* Invalid age values.
* Negative or implausibly high study hours.
* Attendance percentages outside the valid 0–100 range.
* Assignment and final examination scores outside the valid 0–100 range.

These issues will be investigated and documented before the final analysis.

**Important:** The raw dataset will be preserved. Cleaning decisions will be justified rather than automatically deleting every missing value, duplicate, or unusual observation.

---

## 6. Tools and Technologies

The project uses the following tools and libraries:

* **Python:** Main programming language.
* **Pandas:** Data manipulation, cleaning, grouping, and analysis.
* **NumPy:** Numerical calculations and statistical operations.
* **Matplotlib:** Data visualization.
* **Jupyter Notebook:** Interactive environment for analysis.
* **Visual Studio Code:** Development environment.
* **Git and GitHub:** Version control and project documentation.

---

## 7. Project Methodology

The project follows a structured data analysis workflow.

### Phase 1: Problem Definition

* Define the business problem.
* Establish project objectives.
* Formulate research questions.
* Identify the variables required for analysis.

### Phase 2: Data Understanding

* Load the raw dataset.
* Inspect the first and last records.
* Examine dataset dimensions and column names.
* Investigate data types and missing values.
* Assess the initial quality of the data.

### Phase 3: Data Cleaning

* Identify and investigate missing values.
* Detect and investigate duplicate records.
* Standardize inconsistent categorical values.
* Validate numeric ranges.
* Investigate unusual observations.
* Document cleaning decisions.
* Preserve the original raw dataset.

### Phase 4: Exploratory Data Analysis (EDA)

* Calculate descriptive statistics.
* Analyze score distributions.
* Examine relationships between study hours, attendance, assignment scores, and final scores.
* Compare performance across relevant groups.

### Phase 5: Data Visualization

Create appropriate visualizations to communicate the findings, including:

* Histograms for score distributions.
* Bar charts for categorical comparisons.
* Scatter plots for relationships between numerical variables.
* Box plots for score distributions and potential outliers.
* Additional charts where they improve understanding.

### Phase 6: Findings and Recommendations

* Summarize the main findings.
* Explain the significance of the observed patterns.
* Develop recommendations supported by the analysis.
* Document limitations and opportunities for further investigation.

---

## 8. Statistical and Analytical Techniques

The project may use the following techniques where appropriate:

* Mean, median, and mode.
* Minimum, maximum, and standard deviation.
* Percentage calculations.
* Grouped averages and comparisons.
* Correlation analysis.
* Distribution analysis.
* Outlier investigation.
* Data quality validation.

Correlation will be interpreted as an association between variables, not proof of causation.

---

## 9. Project Structure

The project will be organized as follows:

```text
Student_Performance_Analysis/
│
├── data/
│   ├── raw_student_performance_500.csv
│   └── cleaned_student_performance.csv
│
├── notebooks/
│   └── student_performance_analysis.ipynb
│
├── visuals/
│   ├── score_distribution.png
│   ├── study_hours_vs_final_score.png
│   └── attendance_vs_final_score.png
│
├── reports/
│   └── student_performance_analysis_report.pdf
│
├── README.md
└── requirements.txt
```

*This is the intended project structure. Files will be added as the project progresses.*

The raw dataset will remain unchanged. The cleaned dataset, notebook, visualizations, and report will be added as they are developed.

---

## 10. How to Run the Project

### Prerequisites

Install Python and Visual Studio Code, with support for Jupyter notebooks.

### Step 1: Clone the Repository

After publishing the project to GitHub, run:

```bash
git clone <https://github.com/JV-254/STUDENT-PERFORMANCE-ANALYSIS-USING-PYTHON>
```

Replace `<your-repository-url>` with your actual GitHub repository URL.

### Step 2: Navigate to the Project Directory

```bash
cd Student_Performance_Analysis
```

### Step 3: Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### Step 4: Install Dependencies

If a `requirements.txt` file is available, run:

```bash
pip install -r requirements.txt
```

The project requires the following core libraries:

```text
pandas
numpy
matplotlib
jupyter
```

These can also be installed directly:

```bash
pip install pandas numpy matplotlib jupyter
```

### Step 5: Open the Notebook

Open the project folder in Visual Studio Code and run:

```text
notebooks/student_performance_analysis.ipynb
```

Execute the notebook cells in order, ensuring the dataset paths match the project structure.

---

## 11. Expected Deliverables

The completed project will include:

* A documented business problem and research plan.
* A raw dataset and a cleaned dataset.
* A Jupyter notebook containing the analysis.
* Data quality assessment and cleaning documentation.
* Statistical summaries and visualizations.
* A written report explaining the findings.
* Data-driven recommendations.
* A GitHub repository demonstrating the project workflow.

---

## 12. Project Limitations

This project uses synthetic data, so its findings cannot be assumed to represent real students or educational institutions.

Relationships identified in the dataset do not establish causation. Other factors not included in the dataset may influence academic performance.

Additionally, conclusions will depend on data quality, the validity of analytical assumptions, and the methods used to handle missing and invalid values.

The project is intended primarily to demonstrate practical data analysis skills.

---

## 13. Author

**George Njau Wanjiku**

Aspiring Data Analyst | Problem Solver

### Areas of Interest

* Data Analysis
* Data Visualization
* Statistical Analysis
* Business Intelligence
* Data Science
* Machine Learning

### Technical Skills Demonstrated

Python | Pandas | NumPy | Matplotlib | Statistics | Data Cleaning | Exploratory Data Analysis

---

## 14. Project Status

**Status: In Progress**

The project is being developed in stages, beginning with problem definition and data understanding, followed by data cleaning, exploratory analysis, visualization, and reporting.

The final findings and recommendations will be documented after the analysis has been completed and validated.
