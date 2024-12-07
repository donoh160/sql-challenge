# sql-challenge

REPO INFORMATION:

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
        
table_relationships_dbd.png is an image showing the relationships between each of the six tables in the database. http://www.quickdatabasediagrams.com/ was used to create this image. 

employee_queries.sql contains SQL code to query specified criteria about the employees


CITATIONS:
After creating the table_relationships_dbd.png using QuickDBD, an sql file was exported which served as the base for the schema.sql file. Alterations were made to best suit the purposes of employee_queries.sql, however, most of the code remained from what was exported from QuickDBD.

Used XPERT Learning Assistant for help with creating tables and errors that arose when importing csv files

Researched using StackOverflow to help with some queries.


