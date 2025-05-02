#🎓 School Management System (EduTrack)

A desktop-based Java application built with Java Swing, JDBC, and SQL to manage school operations such as user login, class management, student records, exams, subjects, and marks entry. This project features role-based access for Admins and Teachers, real-time database connectivity, and full CRUD operations.


##🚀 Features

Secure Login System with Admin/Teacher roles and validation

Admin Dashboard with access to:

Create Users (Admin/Teacher)

Manage Classes, Subjects, Exams, Students, Teachers

Teacher Dashboard to:

Manage Students

Enter and View Marks

JTable integration for data viewing and editing

Full CRUD operations using SQL

Robust input validation and data consistency checks

Clean, modular code following separation of concerns



##🗂️ Project Structure

School-Management-System/

│

├── Code/           # Contains all .java source files

│   └── *.java

│

├── jar/            # Executable JAR file for running the project


│   └── SchoolManagementSystem.jar
│

├── src/            # Contains .java and compiled .class files

│   └── *.java

│   └── *.class

│

└── README.md       # Project description and setup guide


##🛠️ Technologies Used
Java (Swing for GUI)

JDBC (Java Database Connectivity)

SQL (MySQL/Oracle)

NetBeans or any Java IDE (for development)


##💻 How to Run
###Clone the repository

git clone https://github.com/your-username/School-Management-System.git


###Navigate to the project directory

cd School-Management-System

###Run the JAR file (Requires Java 8 or above)

java -jar jar/SchoolManagementSystem.jar

###Or open .java files in an IDE (like NetBeans or IntelliJ)

Make sure your database is set up correctly and update DB credentials in the code if needed



