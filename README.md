# Challenge-7

***Pewlett Hackard***

Objective
This project aims to model, build, and query a database for employees of the fictional company Pewlett Hackard, with a particular focus on employees who worked during the 1980s and 1990s. The project includes creating a database schema, importing data from CSV files, and performing various queries to extract specific information.

Database Design
The database design was performed using QuickDBD, a tool for quickly and efficiently creating Entity-Relationship Diagrams (ERD). The design includes the following tables:

Departments: Stores information about the company's departments.
Titles: Contains the different titles or positions within the company.
Employees: Records data of employees, including their employee number, name, last name, sex, birth date, and hire date.
Salaries: Saves the salaries of employees.
Dept_Emp: Associates employees with departments.
Dept_Manager: Associates managers with departments.
Each table is appropriately linked through primary and foreign keys to ensure referential integrity.

SQL Schema
The database schema was generated from QuickDBD and implemented in PostgreSQL. The SQL code includes the creation of tables with their respective primary and foreign keys, ensuring that the relationships between the tables are consistent with the ERD design.

Performed Queries
Several SQL queries were executed to answer specific questions about the employee data, such as listing employees hired in a specific year, finding employees with particular names, and calculating the frequency of surnames among employees.

Conclusion
This project demonstrates the ability to design and implement an effective relational database to manage complex employee information. The queries performed allow for valuable insights into the workforce of Pewlett Hackard.