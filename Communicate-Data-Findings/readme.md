# PISA 2012 DATA ANALYSIS
## by Steve Choi


## Dataset

## Investigation Overview

> The Programme for International Student Assessment (PISA) is a triennial international survey which aims to evaluate education systems worldwide by testing the skills and knowledge of 15-year-old students who are nearing the end of their compulsory education. PISA assesses how well they can apply what they learn in school to real-life situations. Over 90 countries have participated in the assessment so far which began in 2000. Every three years students are tested in the key subjects: reading, mathematics and science. In one assessment there is a focus on one of the subjects. For example in the year 2000, the focus was on reading which allowed us to get more in-depth information on the students' reading skills. In addition to the three core subjects, students are tested in an innnovative domain such as collaborative problem solving in 2015 and global competence in 2018. Some countries also choose to administer an assessment in financial literacy.

## Dataset Overview

> Since the original dataset consists of approximately 500,000 rows and 635 columns, first step is to take a closer look at each column variable and select appropriate columns regarding the questions I want to ask.<br>
In this project, I will be exploring relationships between students' performance and their possessions to ask questions such as:
- Distribution of students by items and total number of possessions
- Student performance vs item
- Student average performance vs total number of possessions

> After cleaning and manipulating the original data, it was reduced down to 441,623 rows and 22 columns.
This includes 15 possession-related items (excluding 3 country items for consistency), 4 performance ratings (math, reading, science, and total), and 3 extra columns (`country`, `OECD`, and `gender`)<br>



## Summary of Findings

> - `Dictionary`, `DVD`, and `Desk` are three most popular items possessed by students.
- `Internet` and `Dictionary` had the most impact while `Poetry` and `Dishwasher` had the least impact on student performance.
- 75% of students owns more than 8 items or more.
- There is a positive correlation between student performance and the number of possessions.
- Female students outperformed male student in reading while male student performed slightly better in mathematics in general.