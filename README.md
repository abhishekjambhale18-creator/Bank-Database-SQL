# 🏦 SQL Lab 1 – Bank Database Setup

![SQL](https://img.shields.io/badge/SQL-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Beginner--Intermediate-blue?style=for-the-badge)

> Building a Bank Database from scratch with table creation, structure modification, and basic DDL operations.

---

### 📌 Project Overview
This lab focuses on creating a **Bank Database** from scratch using SQL.  
It includes creating multiple related tables, renaming tables, modifying structures, and practicing basic DDL commands.

---

### ✨ Features
- Database and table creation
- Multiple related tables
- Table renaming
- Column addition and modification
- Basic data retrieval using `SELECT`
- Clean database design foundation

---

### 🗂️ Database Structure

#### 1. Customers
| Column      | Data Type    | Description            |
|-------------|--------------|------------------------|
| CustomerId  | INT          | Unique customer ID     |
| FirstName   | VARCHAR(50)  | Customer first name    |
| LastName    | VARCHAR(50)  | Customer last name     |
| Email       | VARCHAR(100) | Customer email         |
| Phone       | VARCHAR(20)  | Contact number         |
| DateOfBirth | DATE         | Customer date of birth |

#### 2. Accounts
| Column      | Data Type   | Description       |
|-------------|-------------|-------------------|
| AccountId   | INT         | Unique account ID |
| AccountType | VARCHAR(20) | Type of account   |
| Balance     | FLOAT       | Current balance   |

#### 3. Transactions
| Column          | Data Type   | Description           |
|-----------------|-------------|-----------------------|
| TransactionId   | INT         | Unique transaction ID |
| TransactionDate | DATE        | Date of transaction   |
| Amount          | FLOAT       | Transaction amount    |
| TransactionType | VARCHAR(20) | Credit / Debit        |

#### 4. Branches
| Column        | Data Type    | Description           |
|---------------|--------------|-----------------------|
| BranchId      | INT          | Unique branch ID      |
| BranchName    | VARCHAR(100) | Name of the branch    |
| BranchAddress | VARCHAR(200) | Branch address        |
| BranchPhone   | VARCHAR(15)  | Branch contact number |

#### 5. AccountBranches
| Column         | Data Type | Description                |
|----------------|-----------|----------------------------|
| AssignmentDate | DATE      | Date of account assignment |

#### 6. Loans
| Column       | Data Type | Description     |
|--------------|-----------|-----------------|
| LoanId       | INT       | Unique loan ID  |
| LoanAmount   | FLOAT     | Loan amount     |
| InterestRate | FLOAT     | Interest rate   |
| StartDate    | DATE      | Loan start date |
| EndDate      | DATE      | Loan end date   |

---

### 🛠️ Skills Demonstrated
- `CREATE DATABASE` & `CREATE TABLE`
- `SELECT`
- `RENAME TABLE`
- `ALTER TABLE` (ADD / MODIFY columns)
- Basic Database Design

---

### 🚀 How to Run
1. Open **MySQL Workbench** or any SQL client
2. Run the `Bank1.sql` script

---

### 🧰 Tools Used
MySQL

---

**Series Navigation**  
← Previous Lab | [Lab 2 – Bank Database Constraints](https://github.com/abhishekjambhale18-creator/Bank-Database-Constraints) →
