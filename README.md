# Login Page Servlet API

This Java code provides a basic implementation of a registration servlet for a web application. The servlet receives the student name, age, and mark as input parameters and inserts them into a MySQL database using JDBC.

## Prerequisites
- Java Development Kit (JDK)
- Java Servlet API
- MySQL database

## Setup
1. Make sure that the MySQL database is running.
2. Create a database named "bmc".
3. Create a table named "Student" in the "bmc" database with the following columns:
	- id (int, primary key, auto-increment)
	- name (varchar)
	- age (int)
	- mark (int)
4. Replace the MySQL username and password with your own credentials in the `RegistrationServelet` class.
5. Compile and run the servlet using your preferred development environment.

## Usage
1. Access the servlet through a web browser using the following URL: `http://localhost:8080/reg?stname=<student_name>&stage=<student_age>&stmark=<student_mark>`
2. Replace `<student_name>`, `<student_age>`, and `<student_mark>` with the appropriate values.
3. The servlet will insert the student information into the MySQL database and display a message indicating that the information was saved successfully.
