## Employee Management System (SQL)

## Objective

- The goal of this project is to create a database for an Employee Management System that manages employee information, departments, and salaries.
- We will demonstrate how to use subqueries to retrieve specific data and use functions to manipulate data.

## Tools Used

- SQL Server

## Database Structure

- ### Employees Table

- EmployeeID(INT, Primary Key, Auto-increment)
- FirstName(NVARCHAR(50), NOT NULL)
- LastName(NVARCHAR(50), NOT NULL)
- Email(NVARCHAR(100), NOT NULL)
- DepartmentID (INT, Foreign Key referencing Departments)
- Salary(DECIMAL(10, 2), NOT NULL)

- ### Departments Table

- DepartmentID (INT, Primary Key, Auto-increment)
- DepartmentName (NVARCHAR(100), NOT NULL)

## Key Concepts Used

- Primary Keys for unique identification
- Foreign Keys for table relationships
- Data Integrity using constraints (NOT NULL, UNIQUE, CHECK)
- SQL Joins for combining multiple tables

## Sample Queries

- Subquery to Find Employees with Above Average Salary
- Subquery to List Employees in a Specific Department
- Using Functions to Format Employee Names
- Using Function in a Query

  ## Summary of SQL Concepts Used

  - ### Subqueries:
    
  - Used to find employees with above-average salaries and to filter employees by department.

  - ### Functions:
  
  - Created a user-defined function to concatenate first and last names, enhancing query capabilities.
 
  ## Author

  Aishika Nandy
