# sql-challenge
# Company Database Analysis

This project involves setting up an employee database using PostgreSQL and conducting a series of data analysis tasks. The database is built from a series of CSV files, each representing a table in the database.

## Database Setup

To set up the database, followed these steps:

1. Started by running the PostgreSQL server and log in using PGAdmin4.
2. Created a new database named `company_db`.
3. Imported each CSV file as a new table within database. Made sure to set the appropriate data types and primary keys.

The following tables are included:

- `departments`: Contains department information.
- `dept_emp`: Lists department and employee relationships.
- `dept_manager`: Lists which employees manage each department.
- `employees`: Contains employee information.
- `salaries`: Lists employee salaries.
- `titles`: Contains titles associated with each employee.

##Data Modeling

Data Modeling was created using QuickDBD and exported as PNG file in the EmployeeSQL folder in my local and pushed into the github.
##Data Engineering

All required columns are defined, primary keys set, tables correctly related assigned with Foreign Keys, and Not Null conditions. 
Created a table schema for six csv files. 

## Data Analysis

Once the database is set up, the following analyses were performed using SQL queries:

1. **Employee Details**: Retrieved employee numbers, last names, first names, sexes, and salaries.
2. **1986 Hires**: Listed all employees hired in the year 1986.
3. **Managers Per Department**: Displayed the managers for each department.
4. **Employee Departments**: Showed the department details for each employee.
5. **Named Hercules B**: Listed employees named Hercules with last names starting with 'B'.
6. **Sales Department Employees**: Retrieved all employees working in the Sales department.
7. **Sales and Development Employees**: Listed all employees in both the Sales and Development departments.
8. **Surname Frequency**: Counted how often each last name occurs, in descending order of frequency.

### Running the Analyses

To run the analysis, executed the provided SQL queries in PGAdmin4's query tool. The queries can be found in the `queries.sql` file.
