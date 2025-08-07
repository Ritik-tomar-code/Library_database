# Society_Library_database

College Library SQL Database Project


Project Overview:

This is a SQL-based project to manage a college library system. It includes the creation of various tables and their relationships to handle data related to employees, students, publishers, authors, and books.

Database Used: MySQL

Tables Created:

1. EMPLOYEE - Stores library employee information
2. STUDENT - Stores student borrower information
3. PUBLISHER - Stores book publisher details
4. AUTHOR - Stores author details
5. BOOK - Stores book details and links to student, employee, and publisher
6. BOOK_AUTH - Links books to their authors

<img width="806" height="624" alt="table structure" src="https://github.com/user-attachments/assets/641b4a41-99ab-4d5b-9451-283ff0bceddd" />


Key Features:

- Use of PRIMARY KEY and FOREIGN KEY constraints
- Use of cascading updates
- Sample data inserted into each table
- Basic SELECT queries for each table

Relationships:

- BOOK table links to STUDENT (StudID), EMPLOYEE (EmpID), and PUBLISHER (PubID)
- BOOK_AUTH table links BOOK and AUTHOR using their IDs

How to Use:

1. Open MySQL or any SQL-compatible database tool
2. Run the provided SQL script
3. Use SELECT queries to view the data

Example SELECT Queries:

SELECT * FROM EMPLOYEE;
SELECT * FROM STUDENT;
SELECT * FROM PUBLISHER;
SELECT * FROM AUTHOR;
SELECT * FROM BOOK;
SELECT * FROM BOOK_AUTH;

Folder Structure:

College_Library_SQL_Project/
├── README.txt
└── college_library.sql

Author:

Ritik Tomar

