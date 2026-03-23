# 🗄️ Bash Shell Script DBMS

## 📌 Project Overview

This project is a **Database Management System (DBMS)** implemented using **Bash scripting**. It allows users to store, manage, and retrieve data from the hard disk through a **CLI (Command Line Interface)**.

The system simulates core database functionalities such as managing databases, tables, and performing CRUD operations.

---

## 🚀 Features

### 🧭 Main Menu

* Create Database
* List Databases
* Connect to Database
* Drop Database

### 📂 Database Menu (After Connection)

* Create Table
* List Tables
* Drop Table
* Insert into Table
* Select From Table
* Delete From Table
* Update Table

---

## 🛠️ Technical Details

* Each **database** is stored as a directory
* Each **table** is stored as a file inside its database directory
* Metadata file is used to store:

  * Column names
  * Data types
  * Primary key

### ✅ Supported Validations

* Data type validation (e.g., int, string)
* Primary key constraint (no duplicates)
* Input validation for user entries

### 📊 Output Formatting

* Data displayed in a clean and readable table format in the terminal

---

## 👥 Team Work Distribution

### 👩‍💻 Nada Ayman

**Main Menu:**

* Connect to Database
* Drop Database

**Database Menu:**

* Create Table
* Drop Table
* Delete From Table

---

### 👩‍💻 Zahwa Kandeel

**Main Menu:**

* Create Database
* List Databases

**Database Menu:**

* List Tables
* Insert into Table
* Select From Table

---

### 🤝 Shared Tasks (Both Members)

These tasks require collaboration due to their complexity:

* Update Table

---
