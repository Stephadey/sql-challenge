
# SQL Challenge

## Overview

This project involves creating a comprehensive database for Pewlett Hackard, a fictional company, to store and analyse data about their employees from the 1980s and 1990s. The project is divided into three main parts: Data Modelling, Data Engineering, and Data Analysis.

## Project Structure

### Data Modelling

-   An Entity Relationship Diagram (ERD) was created to visualise the structure of the database and its interrelations.

![enter image description here](https://github.com/Stephadey/sql-challenge/blob/main/EmployeeSQL/ERD.png?raw=true)
### Data Engineering

-   SQL table creation scripts were developed for six tables based on the provided CSV files: `departments`, `employees`, `dept_emp`, `dept_manager`, `salaries`, and `titles`.
-   Foreign key constraints were established to maintain referential integrity across the database.
-   Composite primary keys were used in `dept_emp` and `dept_manager` tables to uniquely identify each record.

### Data Analysis

-   SQL queries were written to answer specific questions regarding the employees' data, such as listing employee details, employment history, department managers, and frequency counts of employee last names.
## Installation

### Prerequisites

-   PostgreSQL or any SQL database management system that supports SQL standard.
-   Access to a command-line interface or a database management tool (e.g., pgAdmin for PostgreSQL, MySQL Workbench for MySQL).

### Database Setup

1.  **Clone the Repository**: Download or clone this repository to your local machine.
    
2.  **Create Database**:
    
    -   Open your SQL command-line tool or database management interface.
    -   Create a new database named `pewlett_hackard_db`.
3.  **Create Tables**:
    
    -   Navigate to the `EmployeeSQL` directory within the cloned repository.
    -   Run the SQL scripts provided in the `table-schemata.sql` file to create the necessary tables.
4.  **Import Data**:
    
    -   Use the SQL `COPY` command (PostgreSQL) or the equivalent in your DBMS to import data from the provided CSV files into the respective tables.

### Running Queries

-   Navigate to the `EmployeeSQL` directory.
-   Open the `queries.sql` file.
-   Execute the SQL queries in your database management tool or command-line interface to analyse the employee data.

## References
-   https://www.postgresql.org/docs/current/tutorial-fk.html
- Data generated by [Mockaroo, LLCLinks to an external site.](https://mockaroo.com/), (2022). Realistic Data Generator.
