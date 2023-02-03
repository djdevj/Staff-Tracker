# Staff Tracker Node/CLI

## Description

This is a command line (CLI) based app that can be used to track employee staff and their basic metrics (departments, roles, employees, department, role, and an employee role)

Results are presented in a table format.

Client can choose to view staff in the following ways with the following options:

### Employees
* View All Employees
* View Employees by Department
* View Employees by Manager
* Add Employee
* Remove Employee
* Update Employee Role
* Update Employee Manager

### Roles
* View All Roles
* Add Role
* Remove Role

### Departments
* View All Departments
* View Total Utilized Budget by Department
* Add Department
* Remove Department

## Technologies
* [Node.js](https://nodejs.org/)
* [Inquirer.js](https://www.npmjs.com/package/inquirer)
* [MySQL](https://www.npmjs.com/package/mysql)
* [Figlet](https://www.npmjs.com/package/figlet)

## Installation
To install dependencies, run the following:
`
npm i
`

Then build and seed the database with the files in the [sql folder](./sql/).

## Usage

After downloading the files and installing dependencies, run 
`
node app.js
`
## License
This repository is licensed under the [MIT license](./LICENSE).

