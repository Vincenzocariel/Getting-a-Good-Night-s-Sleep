# Getting-a-Good-Night-s-Sleep

 Sleep Health and Lifestyle Data Analysis

📌 Project Overview

Sleep plays a crucial role in overall health and productivity. In this project, we analyze a dataset of sleep and lifestyle habits to understand how occupation, sleep duration, sleep quality, and BMI categories relate to sleep disorders.

Using Python and Pandas, this analysis investigates patterns in sleep health across different professions and body mass index (BMI) groups.

⸻

🎯 Project Objectives

The goal of this project is to explore the dataset and answer the following key questions:

1️⃣ Which occupation has the lowest average sleep duration?

Calculate the average sleep duration for each occupation and identify the occupation with the lowest mean sleep duration.

The result is stored in:

lowest_sleep_occ


⸻

2️⃣ Which occupation has the lowest average sleep quality?

Determine the occupation with the lowest average sleep quality score.

The result is stored in:

lowest_sleep_quality_occ


⸻

3️⃣ Do the same occupations have the lowest sleep duration and sleep quality?

Compare the results from the previous two questions.

Store the result as a boolean variable:

same_occ

	•	True → the same occupation has both the lowest sleep duration and sleep quality
	•	False → they are different occupations

⸻

4️⃣ Insomnia ratios by BMI category

Investigate how BMI category relates to insomnia diagnoses.

For each BMI category, calculate the ratio of users diagnosed with insomnia relative to the total number of users in that category.

Store the results in a dictionary:

bmi_insomnia_ratios

Example format:

{
    "Normal": 0.08,
    "Overweight": 0.12,
    "Obese": 0.18
}

Each value should be a float rounded to two decimal places.

⸻

📂 Dataset

The dataset contains information about sleep and lifestyle factors for multiple individuals.

Key columns used in this project

Column	Description
Occupation	User profession
Sleep Duration	Average hours of sleep per night
Quality of Sleep	Sleep quality score
BMI Category	BMI classification (Normal, Overweight, Obese, etc.)
Sleep Disorder	Diagnosis status (None, Insomnia, Sleep Apnea)


⸻

🔎 Analysis Workflow

The analysis follows these main steps:
	1.	Data Exploration
	•	Inspect dataset structure and missing values.
	2.	Occupational Sleep Analysis
	•	Calculate average sleep duration by occupation.
	•	Calculate average sleep quality by occupation.
	3.	Sleep Disorder Analysis
	•	Group data by BMI category.
	•	Calculate insomnia ratios within each BMI group.
	4.	Results Interpretation
	•	Compare occupational sleep patterns.
	•	Explore relationships between BMI and insomnia.

