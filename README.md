# employee-management-system-
                            oop project 
# 🏢 Employee Management System (OOP-based C++)

A console-based **Employee Management System** built using **Object-Oriented Programming (OOP)** principles in C++. This project efficiently manages both Full-Time and Part-Time employees, handles file persistence, and includes robust input validation.

---

## 🚀 Features

* **Object-Oriented Design:** Implements core OOP concepts including Inheritance, Polymorphism, Encapsulation, and Abstraction.
* **Employee Types:** 
  * **Full-Time Employees:** Managed with specific salary structures.
  * **Part-Time Employees:** Managed with hourly wage calculations.
* **Data Persistence:** Automatically saves and loads employee records from `.dat` text/data files.
* **Input Validation:** Ensures robust user inputs to prevent crashes caused by invalid data types.
* **Interactive CLI:** Clean and user-friendly console screens for smooth navigation and management.

---

## 📂 Project Structure

```text
Employee-Mangement-System-OOP-main/
│
├── .vscode/               # VS Code workspace settings
├── a.exe                  # Compiled executable file
├── main.cpp               # Entry point of the application
├── person.h / .cpp        # Base Person class
├── Employee.h / .cpp      # Abstract/Base Employee class[cite: 1]
├── FullTimeEmployee.h / .cpp  # Derived class for Full-Time employees[cite: 1]
├── PartTimeEmployee.h / .cpp  # Derived class for Part-Time employees[cite: 1]
├── EmployeeManager.h / .cpp   # Handles collections and operations on employees[cite: 1]
├── dateType.h / .cpp      # Date handling utility class[cite: 1]
├── input_validation.h / .cpp  # Input validation helper functions[cite: 1]
├── screen.h               # Console UI helper[cite: 1]
├── FullTimeEmployees.dat  # Storage file for full-time records[cite: 1]
└── PartTimeEmployees.dat  # Storage file for part-time records[cite: 1]
