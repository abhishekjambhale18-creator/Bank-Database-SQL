# 🏦 Bank Database – SQL Project

![SQL](https://img.shields.io/badge/SQL-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Beginner--Intermediate-blue?style=for-the-badge)

> A structured SQL project demonstrating database design, table creation, data insertion, and basic DDL operations for a simple Banking System.

---

### 📌 Project Overview
This project focuses on building a **Bank Database** from scratch using SQL.  
It includes creating multiple related tables, modifying table structures, and inserting sample data to simulate a real-world banking system.

---

### ✨ Features
- Complete database and table creation
- Multiple interconnected tables
- Table renaming and structure modification
- Basic data retrieval using `SELECT`
- Clean and organized database design

---

### 🗂️ Database Structure

#### 1. Customers
Stores customer personal information.

| Column         | Data Type     | Description              |
|----------------|---------------|--------------------------|
| CustomerId     | INT           | Unique customer ID       |
| FirstName      | VARCHAR(50)   | Customer first name      |
| LastName       | VARCHAR(50)   | Customer last name       |
| Email          | VARCHAR(100)  | Customer email           |
| Phone          | VARCHAR(20)   | Contact number           |
| DateOfBirth    | DATE          | Customer date of birth   |

#### 2. Accounts
Stores account details.

| Column       | Data Type   | Description           |
|--------------|-------------|-----------------------|
| AccountId    | INT         | Unique account ID     |
| AccountType  | VARCHAR(20) | Type of account       |
| Balance      | FLOAT       | Current balance       |

#### 3. Transactions
Records all banking transactions.

| Column          | Data Type     | Description              |
|-----------------|---------------|--------------------------|
| TransactionId   | INT           | Unique transaction ID    |
| TransactionDate | DATE          | Date of transaction      |
| Amount          | FLOAT         | Transaction amount       |
| TransactionType | VARCHAR(20)   | Credit / Debit           |

#### 4. Branches
Stores bank branch information.

| Column        | Data Type      | Description            |
|---------------|----------------|------------------------|
| BranchId      | INT            | Unique branch ID       |
| BranchName    | VARCHAR(100)   | Name of the branch     |
| BranchAddress | VARCHAR(200)   | Branch address         |
| BranchPhone   | VARCHAR(15)    | Branch contact number  |

#### 5. AccountBranches
Links accounts to branches.

| Column         | Data Type | Description              |
|----------------|-----------|--------------------------|
| AssignmentDate | DATE      | Date of account assignment |

#### 6. Loans
Stores loan details.

| Column       | Data Type | Description             |
|--------------|-----------|-------------------------|
| LoanId       | INT       | Unique loan ID          |
| LoanAmount   | FLOAT     | Loan amount             |
| InterestRate | FLOAT     | Interest rate           |
| StartDate    | DATE      | Loan start date         |
| EndDate      | DATE      | Loan end date           |

---

### 🛠️ Skills Demonstrated
- `CREATE DATABASE` & `CREATE TABLE`
- `SELECT`
- `RENAME TABLE`
- `ALTER TABLE` (ADD / MODIFY columns)
- Basic Database Design

---

### 📂 Project Structure
