# sql-challenge

This repo contains SQL files that analyze employees hired between 1980 and 1990 from the company Pewlett Hackard.

Running schema.sql will create tables in an SQL database

The "data" folder contains .CSV files with employee data
    To import the data contained in the CSV files:
        First run schema.sql
        Next import the following CSV files into the corresponding tables of the same name in the following order to avoid errors
                titles.csv
                departments.csv
                employees.csv
        Finally, when importing into the dept_emp, dept_manager and salaries tables, deselect the "id" columns. The .CSV files do not contain these id columns.

employee_queries.sql contains SQL code to query specified criteria about the employees
    
