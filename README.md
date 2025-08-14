# Task7-Employee-Database-App-JavaIntern
Employee Database App (Java JDBC)

A simple Java console application that connects to a MySQL database using JDBC and performs CRUD (Create, Read, Update, Delete) operations on an Employee table.

📌 Features

1.Add Employee – Insert employee details into the database
2.View Employees – Fetch and display all employee records
3.Update Employee – Modify employee details by ID
4.Delete Employee – Remove employee records by ID
5.Uses PreparedStatement for security against SQL Injection
6.Works with MySQL (can be adapted for PostgreSQL easily)

🛠 Tech Stack

Java (JDK 8 or above)
JDBC (Java Database Connectivity)
MySQL (or PostgreSQL with minor changes)
MySQL Connector/J (JDBC driver)

🚀 How to Run
1️⃣ Clone the Repository
git clone https://github.com/your-username/employee-database-app.git
cd employee-database-app

2️⃣ Add MySQL JDBC Driver
Download the MySQL Connector/J from:
https://dev.mysql.com/downloads/connector/j/
Place the .jar file in your project’s lib folder and add it to the classpath

3️⃣ Update Database Credentials
static final String DB_USER = "root";      // Your MySQL username
static final String DB_PASSWORD = "root";  // Your MySQL password

4️⃣ Compile and Run

🖥 Menu Example
===== Employee Database Menu =====
1. Add Employee
2. View Employees
3. Update Employee
4. Delete Employee
5. Exit
Choose an option: 1
Enter Name: Megha
Enter Position: Developer
Enter Salary: 50000
Employee added successfully!

✍️ Author
**Megha Rathi**
