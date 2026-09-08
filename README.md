SQL Data Analyst Job Market Analysis

Introduction

This project explores the Data Analyst job market using SQL and
PostgreSQL, focusing on salaries, job opportunities, and the skills
employers value most.

Questions Explored

What are the highest-paying Data Analyst jobs?

Which skills are required for top-paying roles?

Which skills are most in demand?

Which skills are associated with higher salaries?

Which skills are the most optimal to learn?

Tools Used

SQL -- querying and analyzing the data

PostgreSQL -- database management

VS Code -- writing and executing SQL queries

Git & GitHub -- version control and project sharing

Project Structure

SQL_PROJECT_DA/
├── csv_files/
│   ├── company_dim.csv
│   ├── job_postings_fact.csv
│   ├── skills_dim.csv
│   └── skills_job_dim.csv
│
├── sql_load/
│   ├── 1_create_database.sql
│   ├── 2_create_tables.sql
│   └── 3_modify_tables.sql
│
└── Project_sql/
    ├── 1_top_paying_jobs.sql
    ├── 2_top_paying_job_skills.sql
    ├── 3_top_demanded_skills.sql
    ├── 4_top_paying_skills.sql
    └── 5_optimal_skills.sql

Analysis

1. Top-Paying Data Analyst Jobs

Identifies the top 10 highest-paying Data Analyst roles, focusing on
remote positions with specified salaries.

2. Skills for Top-Paying Jobs

Analyzes the skills associated with the highest-paying Data Analyst jobs
to understand what employers expect for well-paid roles.

3. Most In-Demand Skills

Finds the skills most frequently requested in Data Analyst job postings,
highlighting the technologies employers commonly seek.

4. Skills Based on Salary

Compares average salaries across different skills to identify skills
associated with higher-paying Data Analyst opportunities.

5. Most Optimal Skills to Learn

Combines skill demand and salary information to identify skills that
offer strong value in the Data Analyst job market.

What I Learned

Through this project, I practiced:

Writing complex SQL queries

Using JOINs and CTEs

Filtering, grouping, and sorting data

Using aggregate functions such as COUNT() and AVG()

Analyzing relationships between skills, salaries, and job demand

Turning business questions into SQL-based insights

Conclusion

This project provides a practical view of the Data Analyst job market
and highlights the connection between job salaries, skill demand, and
career opportunities. It also strengthened my SQL and PostgreSQL
skills through hands-on analysis of a large job-posting dataset.
