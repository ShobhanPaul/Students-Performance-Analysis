# Students Performance Analysis

This project explores the **Students Performance Dataset** from Kaggle to understand how students perform based on factors like gender, parental education, diet_quality, and test preparation.

## 📊 Objective

To analyze patterns and insights in student scores using Python data analysis libraries and visualizations.

## 🧰 Tools & Technologies

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

## 🔍 Dataset Overview

The dataset includes the following columns:

- `student_id`
- `age`
- `gender`
- `study_hours_per_day`
- `social_media_hours`
- `netflix_hours`
- `part_time_job`
- `attendance_percentage`
- `sleep_hours`
- `diet_quality`
- `exercise_frequency`
- `parental_education_level`
- `internet_quality`
- `mental_health_rating`
- `extracurricular_participation`
- `exam_score`

---

## 📈 Exploratory Data Analysis (So Far)

Here are the steps taken so far in the analysis:

1.KDE Plot** for the `age` column to understand age distribution.
2.Bar Plot** comparing number of male and female students (filtered by `part_time_job`).
3.Sum of Study Hours** filtered by `gender` and `part_time_job`.
4.KDE Plot** of `study_hours_per_day` to check its distribution.
5.Average Study Hours** across `gender` and `part_time_job`.
6.Bar Plot** of `social_media_hours` (summed) by `gender` and `part_time_job`.
7.Box Plot** of `age` distribution across `gender` and `part_time_job`.
8.Correlation Heatmap** among all numerical columns using Seaborn.
9.Bar Plot** of `netflix_hours` (summed) by `gender` and `part_time_job`.
10.Joint Plot** between `study_hours_per_day` and `attendance_percentage` with `gender` as hue.
11.Count Plot: Diet quality distribution by gender
12.Bar Plot: Avg exam scores by internet quality and gender
13.FacetGrid KDE Plot: Distribution of exam scores by gender and part-time job


---
## 👨‍💻 Author

**Shobhan**  
Aspiring Data Analyst | Focused on building real-world projects
