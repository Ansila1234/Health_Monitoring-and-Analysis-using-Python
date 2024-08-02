# Health_Monitoring-and-Analysis-using-Python
This project presents a detailed analysis of health monitoring data using Python's powerful data analysis and visualization libraries such as Pandas, Seaborn, and Matplotlib. The analysis includes data preprocessing, handling missing values, statistical summaries, and visualizations of various health metrics.


## Objective:

Analyzed health data to monitor and assess various health metrics of 500 patients.

## Key Responsibilities:

### 1. Data Collection and Cleaning:

+ Imported and processed a dataset of 500 patient records using Pandas.
+ Handled missing values:
    + Filled 18 missing values in BodyTemperature with the median (98.61°F).
    + Filled 163 missing values in OxygenSaturation with the median (96%).

### 2. Data Analysis and Visualization:

+ Performed exploratory data analysis on 11 health metrics, including age, heart rate, blood pressure, respiratory rate, body temperature, activity level, oxygen saturation, sleep quality, stress level, and timestamp.
+ Created 12 visualizations to illustrate distributions and relationships, including:
     + Age Distribution
     + Heart Rate Distribution
     + Respiratory Rate Distribution
     + Body Temperature Distribution
     + Oxygen Saturation Distribution
     + Gender Distribution
     + Correlation Matrix of Numerical Health Metrics
     + Heart Rate by Activity Level
     + Blood Pressure Distribution (Systolic and Diastolic)
     + Heart Rate and Oxygen Saturation by Gender
     + Heart Rate and Oxygen Saturation by Sleep Quality and Stress Level
     + Respiratory Rate and Body Temperature by Activity Level

### 3. Statistical Analysis:

+ Generated summary statistics for all health metrics:
     + Mean age of patients: 51.15 years
     + Mean heart rate: 80.13 bpm
     + Mean respiratory rate: 17.52 breaths per minute
     + Mean body temperature: 98.58°F
     + Mean oxygen saturation: 96.3%
+ Analyzed gender distribution:
     + 53% male patients
     + 47% female patients

### 4. Data Categorization:

+ Categorized patients into groups for more insightful analysis:
     + Age Groups: Young (≤35 years), Middle-aged (36-55 years), Senior (≥56 years)
     + Blood Pressure Categories: Normal, Elevated, Hypertension Stage 1, Hypertension Stage 2
     + Heart Rate Categories: Low (<60 bpm), Normal (60-100 bpm), High (>100 bpm)
     + Oxygen Saturation Categories: Low (<94%), Normal (≥94%)
+ Created visualizations for categorical data, showing the distribution of patients in each category.

### 5.Technologies and Tools Used:

 +  Programming Languages: Python
 + Libraries: Pandas, Matplotlib, Seaborn
 + Techniques: Data cleaning, data visualization, statistical analysis, data categorization

## Impact:

The analysis provided comprehensive insights into the health status of 500 patients, identifying key trends and potential health risks.
Visualizations and statistical summaries enabled better understanding and reporting of patient health metrics, aiding in more informed decision-making.
