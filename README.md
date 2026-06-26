# 🏥 Hospital Management System

A Java-based Hospital Management System developed using Object-Oriented Programming (OOP) principles and PostgreSQL for database management. The application integrates Java with PostgreSQL using JDBC to provide efficient management of hospital operations, including patient records, doctor information, appointments, and billing.

This project demonstrates practical implementation of Java programming, relational database design, SQL, and JDBC connectivity while following a structured and object-oriented software development approach.

---

# 📖 Overview

The Hospital Management System is a console-based application designed to simplify hospital record management. It enables users to maintain patient information, doctor details, appointment scheduling, and billing records in a secure PostgreSQL database.

The project emphasizes clean code organization, database connectivity, and the application of core Object-Oriented Programming concepts to solve real-world problems.

---

# 🚀 Key Features

- Patient Registration and Management
- Doctor Information Management
- Appointment Scheduling System
- Billing and Payment Management
- Card and Cash Payment Processing
- File Handling for Record Storage
- PostgreSQL Database Integration
- JDBC Connectivity
- SQL-Based Data Management
- DAO (Data Access Object) Implementation
- Report Generation Using SQL JOIN Queries

---

# 🛠 Technologies Used

- Java
- PostgreSQL
- JDBC (Java Database Connectivity)
- SQL
- IntelliJ IDEA
- Git
- GitHub

---

# 💻 Object-Oriented Programming Concepts

This project demonstrates the practical implementation of the following OOP concepts:

- Abstraction
- Encapsulation
- Inheritance
- Runtime Polymorphism
- Interfaces
- Composition
- Constructors
- Method Overriding
- Getters and Setters

---

# 🗄 Database Design

The system is built on a relational PostgreSQL database consisting of four interconnected tables:

- Patient
- Doctor
- Appointment
- Bill

The database design incorporates:

- Primary Keys
- Foreign Keys
- One-to-Many Relationships
- Relational Integrity
- SQL JOIN Operations

---

# 📂 Project Structure

```text
HospitalManagementSystem
│
├── DatabaseConnection.java
├── Person.java
├── Patient.java
├── Doctor.java
├── Appointment.java
├── Bill.java
├── Payment.java
├── CardPayment.java
├── CashPayment.java
├── FileManager.java
├── PatientDAO.java
├── DoctorDAO.java
├── AppointmentDAO.java
├── BillDAO.java
├── TestConnection.java
└── Main.java
```

---

# 📊 Database Operations

The project implements the following SQL operations:

- CREATE TABLE
- INSERT
- UPDATE
- SELECT
- INNER JOIN
- Primary Key Constraints
- Foreign Key Constraints
- Relational Reports

---

# ⚙️ Installation and Setup

## 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Hospital-Management-System.git
```

## 2. Open the Project

Import the project into IntelliJ IDEA.

## 3. Create the Database

Create a PostgreSQL database and execute the SQL script included in this repository.

## 4. Configure JDBC

Update the database configuration in `DatabaseConnection.java`.

```java
private static final String URL =
"jdbc:postgresql://localhost:5432/Hospital Management System";

private static final String USER = "postgres";
private static final String PASSWORD = "your_password";
```

## 5. Add the PostgreSQL JDBC Driver

Download the PostgreSQL JDBC Driver and add it to the project's libraries.

## 6. Run the Application

Execute `Main.java` to start the application.

---

# 📸 Application Output

The application provides the following functionality:

- Display Patient Information
- Display Doctor Information
- Schedule Appointments
- Generate Bills
- Retrieve Data from PostgreSQL
- Generate Database Reports

---

# 🎯 Learning Outcomes

This project strengthened my understanding of:

- Java Programming
- Object-Oriented Programming
- JDBC
- PostgreSQL
- SQL
- Relational Database Design
- DAO Design Pattern
- Git and GitHub
- Software Development Best Practices

---

# 👨‍💻 About the Developer

I am a Software Engineering student with a strong passion for Java development, database systems, and software engineering. I enjoy building practical applications that strengthen my programming knowledge and improve my problem-solving skills.

I am continuously expanding my expertise in:

- Java Development
- PostgreSQL
- Data Structures and Algorithms
- Spring Boot
- RESTful APIs
- Software Design Principles

My goal is to become a professional Java Developer by building real-world projects and continuously improving my technical skills.

---

# 📫 Contact

**GitHub:** https://github.com/yourusername

**LinkedIn:** https://www.linkedin.com/in/yourusername

**Email:** your.email@example.com

---

# ⭐ Acknowledgements

This project was developed as part of my Software Engineering studies and personal learning journey. It reflects my practical understanding of Java, Object-Oriented Programming, JDBC, SQL, PostgreSQL, and software design principles.

I remain committed to continuous learning and building software solutions that demonstrate clean architecture, maintainable code, and effective database integration.
