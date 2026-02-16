# Student-Performance-Analysis
Demographic & Academic Factors In Educational Outcomes

# Project Overview
This project conducts a comprehensive analysis of student performance data using R, examining relationships between demographic factors, study habits, and academic achievement. The analysis explores how parental education, extracurricular participation, age, and study hours influence student scores across math, reading, and writing subjects.

# Tools Used: R, RStudio, ggplot2, readr

# Dataset: Student_Performance.csv containing student demographics and test scores

# Objective: Apply data visualization techniques to uncover patterns in student performance and demonstrate proficiency in R-based analytics

# Methodology & Analysis
Data Preparation
-Created composite metrics: Total_Score (sum of all subject scores) and Average_Score
-Transformed Age to factor variable for categorical analysis
Calculated summary statistics across all performance indicators

# Key Visualizations
1. Bar Chart: Students by Parental Education
-Visualized distribution of students across parental education levels
-Revealed that most students have parents with High School or Some College education

2. Scatter Plot: Study Hours vs Math Score
-Plotted relationship between daily study hours and math performance
-Added linear regression line revealing weak positive correlation
-Color-coded by gender to identify demographic patterns

3. Histogram: Distribution of Total Scores
-Displayed frequency distribution of combined student scores
-Overlaid mean score line (red dashed) for central tendency reference
-Showed wide score range across the student population

4. Box Plot: Math Scores by Extracurricular Participation
-Compared performance distributions between students with and without extracurricular activities
-Used color coding (lightblue = Yes, lightcoral = No) for clear visual distinction
-Revealed observable performance differences between groups

5. Line Chart: Average Scores by Age
-Tracked subject-wise performance trends across age groups
-Multi-line visualization comparing Math, Reading, and Writing scores
-Identified varying score patterns across different age demographics

# Key Findings
# Finding	Insight
a. Parental Education	Most students have parents with High School or Some College education
b. Study Habits	Weak positive correlation between study hours and math scores
c. Score Distribution	Total scores vary widely across the student population
d. Extracurricular Impact	Observable performance differences between participants and non-participants
e. Age Trends	Distinct score patterns emerge across different age groups

# Technical Implementation
-Data Manipulation: Custom aggregation using sapply() and tapply() functions
-Statistical Summary: Calculated means, counts, and distributions for key variables
-Visualization: Five distinct chart types implementing ggplot2 best practices
-Code Structure: Well-commented R script with clear section organization

# Install required packages
install.packages(c("ggplot2", "readr"))

# Learning Outcomes
-Gained proficiency in R for data analysis and visualization
-Developed skills in creating multiple chart types with ggplot2
-Learned to derive actionable insights from educational data

Mastered data transformation and aggregation techniques in R

