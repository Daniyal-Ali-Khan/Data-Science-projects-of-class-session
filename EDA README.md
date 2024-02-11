
Exploratory Data Analysis (EDA) on Student Data

This Python script performs Exploratory Data Analysis (EDA) on the student_data.csv dataset. The dataset contains information about students, including their demographics, academic

performance, and other attributes.

Dataset Description

The student_data.csv dataset contains the following columns:

school: The student's school (binary: "GP" for Gabriel Pereira or "MS" for Mousinho da Silveira)

sex: Student's gender (binary: "F" for female or "M" for male)

age: Student's age (numeric: from 15 to 22)

address: Student's home address type (binary: "U" for urban or "R" for rural)

famsize: Family size (binary: "LE3" for less than or equal to 3 or "GT3" for greater than 3)

Pstatus: Parent's cohabitation status (binary: "T" for living together or "A" for apart)

Medu: Mother's education level (numeric: 0 - none, 1 - primary education, 2 – 5th to 9th grade, 3 – secondary education, or 4 – higher education)

Fedu: Father's education level (numeric: 0 - none, 1 - primary education, 2 – 5th to 9th grade, 3 – secondary education, or 4 – higher education)

Mjob: Mother's job

Fjob: Father's job

reason: Reason to choose this school

guardian: Student's guardian

traveltime: Home to school travel time

studytime: Weekly study time

failures: Number of past class failures

schoolsup: Extra educational support

famsup: Family educational support

paid: Extra paid classes within the course subject

activities: Extra-curricular activities

nursery: Attended nursery school

higher: Wants to take higher education

internet: Internet access at home

romantic: In a romantic relationship

famrel: Quality of family relationships

freetime: Free time after school

goout: Going out with friends

Dalc: Workday alcohol consumption

Walc: Weekend alcohol consumption

health: Current health status

absences: Number of school absences

G1: First period grade (numeric: from 0 to 20)

G2: Second period grade (numeric: from 0 to 20)

G3: Final grade (numeric: from 0 to 20)

Script Description

Python Script: student_data_analysis.py

Libraries Used:

Pandas: For data manipulation and analysis

Matplotlib: For data visualization
Seaborn: For statistical data visualization
