# COMP518 – Database Systems Assignment 3  
MSc Data Science and Artificial Intelligence  
University of Liverpool  

This repository contains my submission for Assignment 3 of the COMP518 Database Systems module. The assignment focused on schema design, relational integrity, and advanced SQL querying within a book publishing domain. It accounts for 25% of the module's final grade.

---

## Overview

The project was divided into two main parts:

### Part 1: Schema Design with MySQL  
Defined a relational database using `CREATE TABLE` statements based on a provided publishing schema. Key focus areas included:
- Proper use of primary and foreign keys to ensure **entity and referential integrity**
- Domain selection for attributes
- Link tables to represent many-to-many relationships (e.g., authors and publishers)

### Part 2: SQL Query Implementation  
Wrote seven complex SQL queries addressing a range of relational logic, including:
- Filtering based on multiple conditions (e.g., publishers selling specific book formats and genres)  
- Set-based logic (e.g., publishers stocking all books of a certain genre)  
- Aggregate subqueries and correlation (e.g., oldest authors per publisher, genre counts)  
- Multi-table joins to explore indirect relationships (e.g., author-publisher connections via book sales)

---

## Independent Work

Beyond the assignment requirements, I created and populated a **local MySQL database** to test each query using real sample data. This helped validate logic, refine joins, and ensure queries returned the intended results under realistic conditions.

---

## Key Topics & Skills
- SQL DDL & DML (`CREATE TABLE`, `SELECT`, `JOIN`, `GROUP BY`, `HAVING`, `NOT EXISTS`)  
- Data modeling with normalized schemas  
- Testing and debugging queries using MySQL Workbench  
- Handling relational constraints and business rules in query logic  

---

## Submission Notes  
- Final submission delivered as a `.txt` file with SQL code and inline comments  
- Structured for readability and clarity, with each query isolated and documented  

---

*This repository is shared for educational and portfolio purposes only. All work is original and submitted as part of assessed university coursework.*  
© 2024 Benjamin Yiu
