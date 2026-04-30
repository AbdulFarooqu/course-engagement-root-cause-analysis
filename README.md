# Course Engagement Root Cause Analysis

## Project Overview

This project explores the mismatch between course ratings and student enrolment in online learning platforms. The main focus is to understand why some courses receive high ratings but still have low student engagement or enrolment.

The project combines Python-based data analysis, exploratory data analysis, root cause thinking, visualisation, and predictive modelling to identify possible reasons behind this mismatch.

## Project Title

**Popular but Underperforming: Understanding Mismatch Between Course Ratings and Student Engagement**

## Problem Statement

Course ratings are often treated as a sign of success. However, a highly rated course does not always attract high enrolment.

This project investigates the question:

**Why do some highly rated courses have low student engagement or enrolment?**

The goal is to move beyond surface-level metrics and understand the underlying factors that may influence student behaviour.

## Why This Project Matters

High ratings can create the impression that a course is successful. However, if enrolment or engagement is low, decision-makers may misunderstand the actual performance of the course.

This mismatch can affect:

- Course marketing decisions
- Academic planning
- Resource allocation
- Course improvement strategies
- Student engagement analysis

## Dataset

The project uses a structured dataset of online courses containing information such as:

- Course title
- Course rating
- Student enrolment count
- Course difficulty level
- Certificate type
- Course organisation/provider

The dataset was cleaned and prepared for analysis by converting enrolment values into numeric format, removing unsuitable records, and encoding categorical variables for modelling.

## Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

The project followed these steps:

1. Data loading and inspection
2. Data cleaning and preparation
3. Enrolment value conversion
4. Exploratory data analysis
5. Course rating vs enrolment comparison
6. Quadrant mapping
7. Root cause exploration
8. Feature encoding
9. Predictive modelling
10. Feature importance analysis
11. Business recommendations

## Key Analysis Areas

### 1. Rating vs Enrolment Mismatch

The analysis explored whether high course ratings always result in high enrolment. The results showed that some highly rated courses still had low enrolment, highlighting a gap between student sentiment and student action.

### 2. Quadrant Mapping

Courses were grouped into different performance categories based on rating and enrolment:

- Popular and well-enrolled
- Popular but underperforming
- Unpopular but well-enrolled
- Unpopular and low-enrolled

The main focus of this project was the **Popular but Underperforming** group.

### 3. Root Cause Exploration

The project investigated possible reasons behind the mismatch, including:

- Course difficulty level
- Certificate type
- Organisation/provider reputation
- Perceived value of the course
- Possible learner motivation and behavioural factors

### 4. Predictive Modelling

Linear Regression and Random Forest models were used to test whether course-level features could predict student enrolment.

The models showed low predictive performance, suggesting that visible course attributes alone may not fully explain student enrolment behaviour.

## Key Findings

- High course ratings do not always guarantee high enrolment.
- Course difficulty may influence whether students decide to enrol.
- Certificate type and perceived value may affect student decision-making.
- Organisation reputation had a strong influence, but did not fully explain enrolment behaviour.
- Low model performance suggests that hidden behavioural and contextual factors may also influence engagement.
- Ratings should not be used as the only measure of course success.

## Recommendations

Based on the analysis, the following recommendations were made:

- Combine course ratings with enrolment, completion, and engagement metrics.
- Improve course descriptions to clearly communicate value to learners.
- Investigate learner motivations and barriers before promoting courses.
- Consider certificate cost, difficulty level, and perceived usefulness when analysing course performance.
- Use root cause analysis to support evidence-based academic and marketing decisions.

## Repository Structure

```text
course-engagement-root-cause-analysis/
│
├── README.md
├── notebooks/
│   └── root_cause_analysis.ipynb
│
├── presentation/
│   └── course_engagement_root_cause_analysis.pdf
│
├── data/
│   └── README.md
│
├── requirements.txt
└── .gitignore
