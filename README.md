# User Management Backend (Java + MySQL)

This project implements a complete user management system (CRUD) using Java, MySQL, and JDBC.  
The goal is to demonstrate backend development skills, database manipulation, and clean code organization.

--------------------------------------------------------------------------------

Technologies Used:
- Java 17
- MySQL 8
- JDBC
- Maven

--------------------------------------------------------------------------------

Features:
- Create a user
- List all users
- Update an existing user
- Delete a user by ID
- Find a user by ID
- Automatic table creation (DatabaseInitializer)

--------------------------------------------------------------------------------

Project Structure:
- model/User.java → Data model
- repository/UserRepository.java → SQL operations (CRUD)
- config/DatabaseInitializer.java → Database and table creation
- App.java → Console interface that interacts with the repository

--------------------------------------------------------------------------------

MySQL Configuration:

1. Create the database:
   CREATE DATABASE users_db;

2. Edit the credentials in DatabaseInitializer.java:
   URL, USER and PASSWORD

3. The "users" table is created automatically when the program runs:
   id INT AUTO_INCREMENT PRIMARY KEY  
   name VARCHAR(100)  
   email VARCHAR(100)  
   age INT  

--------------------------------------------------------------------------------

How to Run:

1. Open the project in VS Code.
2. Ensure that MySQL is running.
3. Open the file App.java.
4. Click “Run” or execute via command line.

--------------------------------------------------------------------------------

Program Flow:

The system displays a menu with the following options:
1. Create user  
2. List users  
3. Update user  
4. Delete user  
5. Find user by ID  
0. Exit  

Each operation interacts directly with the MySQL database through the UserRepository.

--------------------------------------------------------------------------------

Project Goal:

Show competency in:
- Implementing a complete CRUD system
- Working with relational databases using JDBC
- Separating responsibilities (model, repository, application)
- Writing clean and professional Java code

--------------------------------------------------------------------------------

Author:
Guilherme Teves  
Java Junior Developer  
GitHub: https://github.com/GuilhermeTevess
