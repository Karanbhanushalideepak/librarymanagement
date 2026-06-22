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

## 📂 Project Architecture

```text
library-management-system/
├── admin/                 # Admin operations dashboard panel
│   ├── add-book.php       # Inventory entry handler
│   ├── manage-issued.php  # Tracking for active rentals
│   └── dashboard.php      # Analytics panel
├── config/
│   └── database.php       # PDO / MySQLi connection configurations
├── includes/
│   ├── header.php         # Navigation structural UI
│   └── footer.php         
├── database/
│   └── lms_db.sql         # Raw database schema backup file
├── index.php              # Main student login gateway interface
└── dashboard.php          # Student account history layout
