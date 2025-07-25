# SQL-project---1-
HR Database Management System 🧑‍💼📊
📌 Overview
The HR Database Management System project is a comprehensive relational database built using SQL Server. It is designed to simulate a real-world HR environment and demonstrates the creation, manipulation, and querying of structured data using advanced SQL techniques.
This project covers multiple HR domains including employees, departments, job roles, dependents, locations, countries, and regions.

🎯 Objectives
Design a normalized relational schema for HR data
Populate tables with realistic records
Demonstrate proficiency in SQL through various SELECT, JOIN, ORDER BY, and WHERE operations
Enable querying and reporting for HR metrics such as salaries, hiring dates, and job distributions

🛠️ Technologies Used
SQL Server (SSMS)
T-SQL (Transact-SQL)
PowerPoint (for report documentation)
GitHub (version control and project publishing)

🧱 Database Structure
📂 Tables Included:
regions: Stores continent/region-level data
countries: Links countries to regions
locations: Stores office locations
departments: Maps departments to locations
jobs: Contains job titles and salary ranges
employees: Central HR table with links to jobs and departments
dependents: Stores employee family members

🔗 Relationships:
Foreign keys are used extensively to maintain referential integrity.
Cascading updates and deletes are enabled where applicable.

📊 Key Features
40+ employee records with realistic data
Salary analytics and employee hierarchy logic
Advanced queries with:
Filterng (WHERE, BETWEEN, IN, IS NULL)
Sorting (ORDER BY)
Grouping (GROUP BY, HAVING)
Subqueries and JOINs
Pagination using OFFSET-FETCH
Schema includes insert scripts and SELECT query solutions for all standard operations

📈 Project Outputs
✅ SQL Script File (.sql)
✅ PDF Report of Queries & Results
✅ PowerPoint Presentation for Submission

🚀 Getting Started
To run this project locally:

Open SQL Server Management Studio (SSMS)

Create a new database using:

sql
Copy
Edit
CREATE DATABASE HRdatabase;
USE HRdatabase;
Run the full script from Project 1 HR database.sql

Query the database using sample SELECT statements provided in the script

👤 Author
Chinmay Karandikar
[
](https://www.linkedin.com/in/chinmay-k-aa2954120/)
