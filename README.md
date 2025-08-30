Overview

This project explores the screen time patterns of Indian children based on demographics, device usage, and health impacts.
It combines data cleaning, visualization, statistical analysis, and machine learning to uncover insights about how screen habits affect kids in urban and rural areas.

Dataset

File: Indian_Kids_Screen_Time.csv

Features:

Age → Age of the child
Gender → Male / Female
Urban_or_Rural → Location type
Primary_Device → Main device used (Mobile, Tablet, TV, etc.)
Avg_Daily_Screen_Time_hr → Average daily hours of screen time
Exceeded_Recommended_Limit → Whether usage crossed safe limits
Health_Impacts → Reported health issues


Project Workflow
1. Data Cleaning
Removed missing values
Reset index
Checked unique values & handled categorical/numerical features

2. Exploratory Data Analysis
Countplots for categorical variables
Histograms & boxplots for numerical distributions
Outlier detection using IQR

3. Feature Engineering
Created Age Groups: 5–10, 11–15, 16–18
Added High_Screen_Time flag (1 if >4 hrs/day, else 0)

5. Data Visualizations
Correlation heatmap → Relationship among numerical variables
Grouped bar charts → Screen time comparison by gender & location
Stacked bar charts → Device usage across Urban vs Rural kids

Key Insights

- Urban children generally spend more screen time than rural children.
- Mobile phones are the most used devices.
- Kids with >4 hours daily screen time often reported eye strain & related health impacts.


