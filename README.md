# Employee Tracker SQL
Welcome to the Employee Tracker! This application helps you manage your company's departments, roles, and employees efficiently through a simple command-line interface.

## Description
The Employee Tracker is a command-line application built using Node.js, Inquirer, and PostgreSQL. The application allows business owners or managers to interact with a company's employee database. Users can perform tasks such as viewing departments, roles, and employees, adding new departments, roles, and employees, and updating employee roles. This tool helps manage and organize business information efficiently through a simple and interactive CLI interface.

## User Story
- **AS A** business owner  
- **I WANT** to be able to view and manage the departments, roles, and employees in my company  
- **SO THAT** I can organize and plan my business  

## Acceptance Criteria
- **GIVEN** a command-line application that accepts user input  
- **WHEN** I start the application  
  - **THEN** I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role  
- **WHEN** I choose to view all departments  
  - **THEN** I am presented with a formatted table showing department names and department ids  
- **WHEN** I choose to view all roles  
  - **THEN** I am presented with the job title, role id, the department that role belongs to, and the salary for that role  
- **WHEN** I choose to view all employees  
  - **THEN** I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to  
- **WHEN** I choose to add a department  
  - **THEN** I am prompted to enter the name of the department and that department is added to the database  
- **WHEN** I choose to add a role  
  - **THEN** I am prompted to enter the name, salary, and department for the role and that role is added to the database  
- **WHEN** I choose to add an employee  
  - **THEN** I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database  
- **WHEN** I choose to update an employee role  
  - **THEN** I am prompted to select an employee to update and their new role and this information is updated in the database  

## Installation
- Clone the repo
- Install all dependencies: npm install
- Set up your PostgreSQL database (make .env file)
DB_HOST=localhost
DB_USER=<your-username>
DB_PASSWORD=<your-password>
DB_NAME=employee_tracker
DB_PORT=5432 <--- example
- Run the application: npm start

## Usage
   - Follow the prompts in the command-line interface to:
   - View all departments, roles, or employees.
   - Add a new department, role, or employee.
   - Update an employee's role.

## Features
- View all departments, roles, and employees in a formatted table.
- Add new departments, roles, and employees to the database.
- Update an employee's role.
- Interactive CLI interface using Inquirer.
- PostgreSQL database integration for data storage and retrieval.

### Bonus Features
- Update employee managers.
- View employees by manager or department.
- Delete departments, roles, and employees.
- View the total utilized budget of a department.


## Screenshots and Screen Recording
![Image Alt](https://github.com/DippaFudd/SQL--ET/blob/3a4e4b50732039106df3c49b5ff853e774e12689/2025-03-22%20(1).png)
![Image Alt](https://github.com/DippaFudd/SQL--ET/blob/3a4e4b50732039106df3c49b5ff853e774e12689/2025-03-22%20(3).png)
![Image Alt](https://github.com/DippaFudd/SQL--ET/blob/3a4e4b50732039106df3c49b5ff853e774e12689/2025-03-22%20(4).png)

Video link
https://app.screencastify.com/v3/watch/Tss6B58zzyu2VhsH51uX

