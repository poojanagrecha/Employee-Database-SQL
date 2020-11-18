# Employee Database SQL
 Created a SQL database for Employee Data and conducted Data Modeling, Data Engineering and Data Analysis on the data uploaded to database.
 # Background
 A research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

The next step is to design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, to perform the following:

Data Modeling

Data Engineering

Data Analysis

<b>Data Modeling</b>

In this step an ERD(Entity Relation Database) diagram was built with 6 tables to inspect the 6 CSV files.
![Image of ERD Diagram](https://github.com/poojanagrecha/Employee-Database-SQL/blob/main/EmployeeSQL/ERD.png)

    
<b>Data Engineering</b>
In this step we use the information to create a table schema for each of the six CSV files and import each CSV file into the corresponding SQL table.

<b>Data Analysis</b>

Once we have a complete database, we run the SQL queries to obtain the following:

List the following details of each employee: employee number, last name, first name, gender, and salary.

List employees who were hired in 1986.

List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name, and start and end employment dates.

List the department of each employee with the following information: employee number, last name, first name, and department name.

List all employees whose first name is "Hercules" and last names begin with "B."

List all employees in the Sales department, including their employee number, last name, first name, and department name.

List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

