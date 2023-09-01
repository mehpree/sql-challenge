# Employee Database Analysis with SQL

## Introduction

Welcome to the Pewlett Hackard employee database analysis project. As a data engineer, I've been tasked with working on a research project related to employees who worked at the company during the 1980s and 1990s. The project involves designing tables to store data from six CSV files, importing this data into a SQL database, and performing various data analysis tasks.

## Data Modeling

I began by inspecting the provided CSV files and sketching an Entity Relationship Diagram (ERD) of the tables. This ERD helped me visualize the relationships between different data components. Tools like QuickDBD were used to create the ERD, ensuring an organized structure for the database.

## Data Engineering

In the data engineering phase, I designed the table schema for each of the six CSV files. Several important considerations were kept in mind:

-   Defining appropriate data types for each column
-   Specifying primary keys and verifying their uniqueness
-   Managing foreign keys to establish relationships between tables
-   Creating tables in the correct order to handle foreign key dependencies

I carefully imported the data from the CSV files into their corresponding SQL tables, ensuring data integrity and maintaining data consistency.

## Data Analysis

The final part of the project involved answering various data analysis questions using SQL queries. Some of the key questions and insights include:

1.  Listing employee numbers, last names, first names, sexes, and salaries of all employees.
2.  Identifying employees hired in 1986 by listing their first names, last names, and hire dates.
3.  Listing department managers along with their department number, department name, employee number, last name, and first name.
4.  Associating department numbers with employee details, including employee number, last name, first name, and department name.
5.  Identifying employees named Hercules with last names starting with the letter B, listing their first names, last names, and sexes.
6.  Listing all employees in the Sales department, including their employee numbers, last names, and first names.
7.  Listing employees in the Sales and Development departments, including their employee numbers, last names, first names, and department names.
8.  Displaying the frequency counts, in descending order, of all employee last names to identify shared last names among employees.

This project provided valuable insights into the employee database at Pewlett Hackard during the 1980s and 1990s, showcasing the power of SQL for data analysis and database management.

## Conclusion

The successful completion of this project demonstrates the importance of data engineering and analysis in handling large datasets. It also highlights the significance of well-structured databases and effective SQL querying techniques for extracting meaningful insights from data.

### References
Data generated by  [Mockaroo, LLCLinks to an external site.](https://mockaroo.com/), (2022). Realistic Data Genera


