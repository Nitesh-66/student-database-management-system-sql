
# Student Database Management System (SQL)

## Project Title

Student Database Management System

## Description

The Student Database Management System is a relational database project developed using MySQL.
It is designed to manage student records, faculty details, departments, courses, enrollments, attendance, and grades efficiently.

This project demonstrates the implementation of SQL concepts including:

* Database creation
* Table creation with primary and foreign keys
* CRUD operations
* SQL clauses (WHERE, HAVING, LIMIT)
* SQL operators (AND, OR, NOT)
* Sorting and grouping (ORDER BY, GROUP BY)
* Aggregate functions (SUM, AVG, MAX, MIN, COUNT)
* Joins (INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN using UNION)
* Subqueries
* Date and time functions
* String manipulation functions
* Window functions
* CASE expressions

---

## Database Name

student_db

---

## Tables Included

1. Departments
2. Students
3. Faculty
4. Courses
5. Enrollments
6. Attendance
7. Grades

---

## Table Relationships

* Students are linked to Departments using department_id
* Faculty are linked to Departments
* Courses are assigned to Faculty
* Enrollments connect Students and Courses
* Attendance tracks student presence per course
* Grades store marks obtained by students in courses

Foreign keys are implemented to maintain referential integrity.

---

## Features Implemented

### 1. CRUD Operations

* Insert new students, faculty, courses, and enrollments
* Update student contact details
* Delete student records

### 2. SQL Clauses

* Filtering using WHERE
* Group filtering using HAVING
* Limiting results using LIMIT

### 3. SQL Operators

* AND
* OR
* NOT

### 4. Sorting and Grouping

* Alphabetical listing of students
* Counting students per department
* Average marks per course

### 5. Aggregate Functions

* SUM
* AVG
* MAX
* MIN
* COUNT

### 6. Joins

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL OUTER JOIN (implemented using UNION)

### 7. Subqueries

* Students scoring above average
* Students missing more than a specific number of classes

### 8. Date and Time Functions

* Extract month from dates
* Calculate years difference
* Format dates

### 9. String Functions

* UPPER
* TRIM
* IFNULL

### 10. Window Functions

* RANK()
* Running totals
* Cumulative calculations

### 11. CASE Expressions

* Student performance classification
* Attendance categorization

---

## How to Run the Project

1. Open MySQL Workbench or any MySQL client.

2. Execute the script to create the database:

   CREATE DATABASE student_db;

3. Use the database:

   USE student_db;

4. Run the table creation queries.

5. Insert the sample data.

6. Execute the queries to test functionality.

---

## Learning Outcomes

This project helps in understanding:

* Relational database design
* Data normalization
* Query optimization
* Advanced SQL features
* Real-world academic database structure

---

## Author

Nitesh Kumar

