# SQL-Challenge

## Background

Welcome to the SQL-Challenge! In this project, you will be working as a data engineer at Pewlett Hackard, a fictional company. Your primary task is to conduct a research project focusing on employees from the 1980s and 1990s using the company's historical employee database, which is stored in six CSV files.

Your mission includes designing tables to store data from these CSV files, importing the data into a SQL database, and then performing data analysis. The project is divided into three main parts: data modeling, data engineering, and data analysis.

## Instructions

### Data Modeling

1. Inspect the CSV files and create an Entity Relationship Diagram (ERD) for the tables. You can use tools like QuickDBD for creating the sketch.

### Data Engineering

2. Utilize the provided information to create a table schema for each of the six CSV files. Ensure to:

   - Specify data types, primary keys, foreign keys, and other constraints.
   - Verify uniqueness for primary keys or create composite keys when necessary.
   - Create tables in the correct order to handle foreign keys.
   - Import each CSV file into its corresponding SQL table.

   **Hint:** Import data in the same order as table creation, and account for headers during imports.

### Data Analysis

3. Execute the following queries to derive valuable insights from the database:

   - List the employee number, last name, first name, sex, and salary of each employee.
   - List the first name, last name, and hire date for employees hired in 1986.
   - List the manager of each department with their department number, department name, employee number, last name, and first name.
   - List the department number for each employee along with their employee number, last name, first name, and department name.
   - List the first name, last name, and sex of employees named Hercules with last names starting with B.
   - List each employee in the Sales department with their employee number, last name, and first name.
   - List each employee in the Sales and Development departments with their employee number, last name, first name, and department name.
   - List the frequency counts, in descending order, of all employee last names.


