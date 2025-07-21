# 🧾 Employee Payslip Generator

A **simple Java console application** that generates employee payslips with a detailed breakdown of **earnings**, **deductions**, and **net pay**. Ideal for learning **OOP concepts**, **console input handling**, and **formatted output** in Java.

---------------------------------------------------------------------------------------------

## ✨ Features

- ✅ **Employee Information Management**  
  Store and manage employee details including name, ID, designation, department, and attendance.

- 💰 **Payslip Calculation**  
  Automatically calculates **total earnings**, **deductions**, and **net pay** based on user input.

- 🧑‍💻 **Interactive Input**  
  Console-based interface to collect employee and salary data.

- 📄 **Formatted Output**  
  Clean, professional payslip format with clear alignment and labeled sections.
  
----------------------------------------------------------------------------------------------
 🛠️ Tech Stack (Bullet Format)
  -Java (JDK 8 or above) – Core programming language used for the entire application logic

  -Java Scanner – For interactive console input from the user

  -System.out.println – For displaying formatted output in the terminal

  -OOP (Object-Oriented Programming) – Used to organize code into classes like Employee, PaySlip, and Test

----------------------------------------------------------------------------------------------

## 📁 Project Structure
  src/
├── com/model/
│ └── Employee.java # Employee data model
├── com/service/
│ └── PaySlip.java # Payslip calculation and display logic
└── com/main/
└── Test.java # Main class with user interface

----------------------------------------------------------------------------------------------

## 📦 Classes Overview

### 🔹 [Employee.java](src/com/model/Employee.java) (Model)

- Stores:
  - Employee Name
  - Employee ID
  - Designation
  - Department
- Manages:
  - Attendance data: Working Days, Leave Days
  - Pay Period
- Provides getter and setter methods for all fields

---

### 🔹 [PaySlip.java](src/com/service/PaySlip.java) (Service)

- Handles:
  - Salary components such as basic pay, allowances, and deductions
- Calculates:
  - ✅ **Total Earnings**
  - ✅ **Total Deductions**
  - ✅ **Net Pay**
- Displays:
  - A formatted, console-based payslip output

---

### 🔹 [Test.java](src/com/main/Test.java) (Main)

- Provides an **interactive console interface**
- Collects user input for both employee and salary details
- Orchestrates the complete **payslip generation process**

----------------------------------------------------------------------------------------------

## 💼 Salary Components

### 📈 Earnings
- 🔹 Basic Pay  
- 🔹 Incentive Pay  
- 🔹 House Rent Allowance (HRA)  
- 🔹 Meal Allowance  

### 📉 Deductions
- 🔸 Provident Fund  
- 🔸 Professional Tax  
- 🔸 Loan
- 
----------------------------------------------------------------------------------------------
