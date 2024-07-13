# Employee Management System
# Overview
This project is a web application that allows administrators to perform CRUD (Create, Read, Update, Delete) operations on employee records. The application is built using Node.js and MongoDB, ensuring efficient and secure management of employee data. Proper validation and authentication mechanisms are implemented to protect sensitive information.

# Features
* Add Employees: Create new employee records with validated input.
* View Employees: Retrieve and display details of existing employee records.
* Update Employees: Modify information of existing employees.
* Delete Employees: Remove employee records from the system.
* Authentication: Secure login system to ensure only authorized users can access the application.
* Validation: Input validation to maintain data integrity and prevent errors.

# Technologies Used
* Node.js: Server-side JavaScript runtime environment.
* Express.js: Web application framework for Node.js.
* MongoDB: NoSQL database for storing employee data.
* Mongoose: ODM (Object Data Modeling) library for MongoDB and Node.js.
* 
# Installation
Prerequisites
Ensure you have the following installed on your system:

* Node.js
* MongoDB
* npm (Node Package Manager) or yarn

# Usage
1. Open your browser and navigate to http://localhost:5000.
2. Log in with your administrator credentials.
3. Perform CRUD operations on employee records:
   * Add a new employee.
   * View existing employee details.
   * Update employee information.
   * Delete employee records.
  
   
# Validation and Authentication
* Validation: All input fields are validated to ensure data integrity. Invalid or incomplete data will be rejected with appropriate error messages.
* Authentication: The system uses JSON Web Tokens (JWT) for secure authentication. Only authenticated users can perform CRUD operations.
