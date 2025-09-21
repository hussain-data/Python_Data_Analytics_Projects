# Python_Data_Analytics_Projects
---
# HR Data Analysis Project
![image alt](https://github.com/hussain-data/Python_Data_Analytics_Projects/blob/01b9876623dec5f093d6edf9fbba5b065d758ab8/HR-Analytics.webp)
This project analyzes HR data to gain insights into employee status, work modes, departmental statistics, and salary distributions. The analysis is performed using Python with libraries such as Pandas for data manipulation and Matplotlib/Seaborn for data visualization.

## Table of Contents
- [Features]
- [Usage]
- [Data Overview]
- [Analysis Questions]

## Features
- **Data Cleaning:** Removes unnecessary columns and converts data types for analysis.
- **Employee Status Distribution:** Analyzes and visualizes the distribution of employee statuses (Active, Resigned, Retired, Terminated).
- **Work Mode Distribution:** Shows the breakdown of employees working on-site versus remotely.
- **Departmental Analysis:** Provides insights into the number of employees in each department.
- **Salary Analysis:** Explores average salaries by department and job title, and the correlation between performance rating and salary.
- **Hiring Trends:** Tracks the number of hires over time.
- **Attrition Analysis:** Identifies departments with the highest employee attrition rates.
    
 ## Usage
The project is available as a Jupyter Notebook (HR Data Analysis.ipynb). You can run the notebook to see the full analysis and visualizations.
 ## Data Overview
The dataset contains the following columns:
Employee_ID, Full_Name, Department, Job_Title, Hire_Date, Location, 
Performance_Rating, Experience_Years, Status, Work_Mode, Salary_INR.

## Analysis Questions
 **This project answers the following questions:**
1. What is the distribution of Employee Status (Active, Resigned, Retired, Terminated)?
2. What is the distribution of work modes (On-site, Remote)?
3. How many employees are there in each department?
4. What is the average salary by Department?
5. Which job title has the highest average salary?
6. What is the average salary in different Departments based on Job Title?
7. How many employees Resigned & Terminated in each department?
8. How does salary vary with years of experience?
9. What is the average performance rating by department?
10. Which Country has the highest concentration of employees?
11. Is there a correlation between performance rating and salary?
12. How has the number of hires changed over time (per year)?
13. Compare salaries of Remote vs On-Site employees; is there a significant difference?
14. Find the Top 10 employees with the highest salary in each department.
15. Identify the department with the highest attrition rate (Resigned %).
---
# 🎬 Netflix Data Analysis Project
![Netflix Banner Image](https://github.com/hussain-data/Python_Data_Analytics_Projects/blob/e39ead79f3c308735b385d1ff0f60dea5d2831f5/hussain-data.png) [![Language](https://img.shields.io/badge/Language-Python_3-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-red.svg)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Library-Seaborn-purple.svg)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 📌 Project Overview

This project is an exploratory data analysis (EDA) of the Netflix dataset, which contains information on movies and TV shows available up to 2021. The primary objective is to clean, analyze, and visualize the data to uncover trends and insights about the Netflix content library. This analysis serves as a practical demonstration of data manipulation and visualization skills using Python.

## 💡 Key Insights
Here are the top insights discovered from the analysis:

-   **Peak Content Year:** **2019** was the year with the highest volume of new content added to Netflix.
-   **Content Composition:** The library is dominated by **Movies**, making up approximately **69%** of the content, while TV Shows account for the remaining 31%.
-   **Top Content Producer:** The **United States** is the leading producer of content on the platform.
-   **Most Common Rating:** The **TV-MA** (Mature Audience) rating is the most frequent, indicating a large catalog targeted at adults.

## 🛠️ Technical Details

### Tech Stack
-   **Python 3**
-   **Pandas**: For data cleaning, wrangling, and analysis.
-   **Seaborn** & **Matplotlib**: For generating data visualizations.
-   **Jupyter Notebook**: For interactive analysis and reporting.

### Dataset
-   **Source**: [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
-   **Description**: The dataset includes columns such as `Show_Id`, `Category`, `Title`, `Director`, `Country`, `Release_Date`, `Rating`, `Type`, and `Duration`.

## ✅ Analysis Walkthrough

The Jupyter Notebook (`Netflix Data Analytics.ipynb`) performs the following analytical tasks:

-   [x] **Data Loading and Inspection**: Initial loading and review of the dataset's structure and data types.
-   [x] **Data Cleaning**: Handled duplicate records and investigated null values using a heatmap.
-   [x] **Date Conversion**: Converted the `Release_Date` column to a proper datetime format for time-based analysis.
-   [x] **Content Filtering**: Performed various filtering operations to answer specific questions, such as:
    -   Finding all movies released in 2020.
    -   Listing all TV shows produced in India.
    -   Identifying TV shows with an 'R' rating released after 2018.
-   [x] **Trend Analysis**:
    -   Counted and plotted the number of releases by year.
    -   Identified the top 10 directors by content volume.
    -   Determined the country with the most TV shows.
-   [x] **Attribute Parsing**: Extracted numerical values from the `Duration` column to find the maximum movie length.

---
![image alt](https://github.com/hussain-data/Python_Data_Analytics_Projects/blob/1fb042d6fbe9bc56866f8e472ca01d3fb240f9fa/weather_image.png)
