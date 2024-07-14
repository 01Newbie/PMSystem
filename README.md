# PMSystem
# Project Management System (PMSystem)
The Project Management System (PMSystem) is a Java application designed to manage projects for a small structural engineering firm named "Poised". 
It allows users to perform various operations related to project management, including capturing new projects, updating project details, marking projects as finalized, and more.

# Features
Fetch and Display Projects: View all projects currently stored in the database.
Capture Information for New Project: Add a new project to the system with details such as project name, building type, address, deadlines, and contacts.
Update Existing Project: Modify details of an existing project in the database.
Delete Project: Remove a project from the database.
Mark Project as Finalized: Set a project's status to finalized once completed.
Find Incomplete Projects: Display projects that are not yet finalized.
Find Overdue Projects: Identify projects with deadlines that have passed without being finalized.
Search Project: Look up projects by project name or customer name.

# Setup Instructions
# Prerequisites
Java Development Kit (JDK) installed on your system
MySQL Server installed and running

# Steps to Run the Application
1. Clone the Repository:
2. Set Up the Database:
Create a MySQL database named PoisePMS.
Import the database schema using the PoisePMS.sql script provided.
3. Configure Database Connection:
Open the Main.java file in your preferred Java IDE.
Update the database connection details (DB_URL, DB_USER, DB_PASSWORD) in the Main class to match your MySQL setup.
4. Compile and Run the Application:
Compile the application:
Run the application:
5. Interact with the Application:
Follow the menu prompts in the console to perform various operations on projects.

# Database Schema
The application interacts with a MySQL database (PoisePMS) containing the following tables:
Projects: Stores details of each project, including project number, name, building type, addresses, financial details, deadlines, and contact information.

# Dependencies
MySQL Connector/J: JDBC driver for connecting Java applications to MySQL databases.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments
This project was developed as part of a capstone project for [Full Stack Web & Software Engineer].
