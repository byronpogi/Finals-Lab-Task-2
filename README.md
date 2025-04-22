# Finals-Lab-Task-1
Final Task 1: MySQL Portfolio – Company Database

This portfolio covers the basics of MySQL by creating a company database. It includes writing SQL queries, setting up tables, and showing how the tables are related through schemas or ER diagrams. I’ve also included the SQL code used to build the database structure.

Task 1: Employees Table
employee_id: INT, auto-increment, primary key

employee_name: VARCHAR(255), not null

manager_id: INT, foreign key referencing employee_id in the same table

Task 2: Departments Table
department_id: INT, auto-increment, primary key

department_name: VARCHAR(255), not null

Task 3: Employee_Departments Table
employee_id: INT, foreign key from employees

department_id: INT, foreign key from departments

Composite primary key on both columns

Task 4: Employee_Projects Table
employee_id: INT, foreign key from employees

project_name: VARCHAR(255), not null

Task 5: Managers Table
manager_id: INT, auto-increment, primary key

employee_id: INT, foreign key from employees

#Screenshots
![Image](https://github.com/user-attachments/assets/92ba29f4-20b6-4ab1-b17d-43aff67cd06b)
![Image](https://github.com/user-attachments/assets/5d19c68c-b932-43b4-8673-e0ca6eb47fef)
![Image](https://github.com/user-attachments/assets/b23fedb5-f3e6-495a-9634-d87f4d3396c6)
![Image](https://github.com/user-attachments/assets/5d47f6fd-d030-454d-80e8-5412092b62a7)
![Image](https://github.com/user-attachments/assets/89cfb204-3c69-43fa-a059-edce77df032b)
![Image](https://github.com/user-attachments/assets/f68505c0-b1bd-43fd-8807-f1e55b9b96b2)
![Image](https://github.com/user-attachments/assets/1297d0f3-4bf2-4c01-b767-0370add16d36)
![Image](https://github.com/user-attachments/assets/a6dafbcb-8e2f-4e98-a2b2-111e1604bb71)
![Image](https://github.com/user-attachments/assets/ea437389-a691-4e56-b20f-89910b66e434)
![Image](https://github.com/user-attachments/assets/30dda039-7410-45fa-afeb-082fbcd96677)
