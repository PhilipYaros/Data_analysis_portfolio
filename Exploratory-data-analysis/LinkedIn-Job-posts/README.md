# LinkedIn Jobs Analysis

## Overview
This project aims to analyze data related to job postings on LinkedIn, providing insights into job trends, required skills, and other key factors that job seekers and professionals might find useful.

## Dataset Description
- **Source**: [1.3M Linkedin Jobs & Skills (2024)](https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024)
- **Structure**: 2 tables used:
  linkedin_job_postings.csv - including the columns as job_id, location, level, job_title etc.
  job_skills.csv - including a column that describes all the required skills for each job posted. 
- **Purpose**: I wanted to examine the skills required for different roles and levels, and to see if there are trends for different locations. 

## Analysis Process
1. **Data Cleaning**:
   - Handling missing values.
   - Standardizing column names and data formats.
2. **Exploratory Data Analysis (EDA)**:
   - Visualizing trends in job postings (e.g., by skills, location, or level).
   - Analyzing the most in-demand skills and roles.
   - Analyze differences bettwen countries (USA, UK, Austraila etc.)
3. **Insights and Patterns**:
   - Extracting key trends and observations from the data.
   - Identifying actionable insights for job seekers or recruiters.

## Results and Insights
- Summarize the main findings from the analysis, such as:
  - Top industries or locations for job opportunities.
  - some skills that required for all roles like communication and teamwork.
    We can also see that the senior and lead roles ask for different skills that junior roles don't, such as project managment for seniors, or supervisory 
 experience for lead roles. The skill of leadership is very important for senior roles in comparison to junior.
  - Changes in job trends over time 

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn 
- **Environment**: Jupyter Notebook

## How to Run
1. Clone the repository containing this project.
2. Install required libraries using the following command:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook LinkedIn_Jobs.ipynb
   ```
4. Run the notebook cells sequentially to reproduce the analysis.

## Future Work
- Incorporate additional datasets to expand the analysis.
- Apply machine learning techniques to predict job trends or required skills.
- Automate the process of updating job data for real-time insights.

