# 25-60745-1_CompanyApp

## Lab 2: Merging Login/Register and Employee CRUD into One App

*Student ID:* 25-60745-1  
*Project:* 25-60745-1_CompanyApp  
*Language:* C#  
*Framework:* .NET Framework 4.8  
*Database:* SQL Server LocalDB  
*Database Name:* dbCompanyApp  

---

## 1. Project Overview

This project merges two separate Windows Forms applications into one application.

The first application was a Login/Register system containing:

- frmLogin
- frmRegister
- frmDashboard
- Microsoft Access database (db_users.mdb)
- System.Data.OleDb

The second application was an Employee CRUD system containing:

- Employee CRUD operations
- SQL Server LocalDB
- System.Data.SqlClient

The final application combines both systems into one project and one database.

### Final Application Flow

```text
Login
   ↓
Dashboard
   ↓
Manage Employees
   ↓
Employee CRUD
   ↓
Logout
   ↓
Login
