# 📚 Library Management System (LMS)

A robust, web-based Library Management System built using PHP and MySQL to automate college or school library operations, track book inventory, manage member subscriptions, and streamline issue/return workflows.

---

## 🛠️ Tech Stack:

![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

---

## 🌟 Key Features

* **🔑 Dual Role Dashboard:** Separate execution portals for Admin (Librarian) and Users (Students/Faculty).
* **📖 Book Inventory Management:** Full CRUD operations to add, update, catalog, and track book status (Available/Issued).
* **🔄 Issue & Return Tracking:** Seamlessly record transactions, calculate automated dynamic fine generation for overdue dates, and view histories.
* **👥 Member Tracking:** Comprehensive registry of student registrations, active statuses, and maximum borrowing limits.
* **📊 Search Filter:** Fast, responsive client-side searching by Book Title, Author, ISBN, or Category.

---

## 🚀 Getting Started

### 1. Database Setup
1. Open your local database manager dashboard (like **XAMPP / phpMyAdmin**).
2. Create a new database named exactly: `lms_db`.
3. Select the database, click the **Import** tab, and select the `.sql` file from this project to build your tables.

### 2. File Placement
1. Move the entire project directory into your local server's web root folder:
   * **Windows (XAMPP):** `C:/xampp/htdocs/`
   * **Linux (LAMP):** `/var/www/html/`

### 3. Server Initialization
1. Turn on the **Apache** and **MySQL** modules using your XAMPP Control Panel.
2. Open your preferred web browser and navigate directly to:
```text
   http://localhost/library-management-system/
