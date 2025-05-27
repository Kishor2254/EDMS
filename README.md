# 🗃️ Employee Database Management System (EDMS)

## 📖 Overview

The **Employee Database Management System (EDMS)** is a web application designed to help organizations manage employee records efficiently. Built using **HTML, CSS, JavaScript**, and **PHP**, this project uses **MySQL** as the database and is hosted locally using **XAMPP**.

The system allows administrators to add, edit, delete, and view employee details through a user-friendly interface.

---

## 🔧 Technologies Used

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: PHP  
- **Database**: MySQL (via XAMPP)  
- **Server**: Apache (XAMPP)

---

## 🚀 Features

- ✅ Add new employee records  
- ✏️ Edit existing employee information  
- 🗑️ Delete employee entries  
- 🔍 Search and view employee data  
- 📋 Responsive and simple user interface  
- 💾 Data persistence with MySQL

---

## 🛠️ Installation & Setup

### Step 1: Download or Clone the Repository

```bash
git clone https://github.com/kishor2254/edms.git

### Step 2: Set Up XAMPP
Install XAMPP if not already installed

Start Apache and MySQL from the XAMPP Control Panel

### Step 3: Import the Database
Open phpMyAdmin

Create a new database: edms_db

Import the SQL file: edms_db.sql (found in the root of the project)

### Step 4: Configure Database Connection
Open includes/config.php and update if needed:
  $host = "localhost";
$username = "root";
$password = "";
$database = "edms_db";

### Step 5: Run the Application
Move the project folder to htdocs in your XAMPP directory

Visit http://localhost/edms in your browser


