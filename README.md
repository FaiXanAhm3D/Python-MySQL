# Python + MySQL Database App 📚

This is a beginner-friendly Python project that connects to a **MySQL database** to perform basic CRUD operations (Create, Read, Update, Delete).

It serves as a simple command-line interface for managing data entries like students, employees, etc.

---

## 🔧 Features

- Add new records to the database
- View all existing records
- Update specific entries
- Delete entries from the database
- Clean terminal-based user interface

---

## 🛠️ Tech Stack

- Python 3
- MySQL
- `mysql.connector` (Python library)

---

## ⚙️ Setup Instructions

1. Make sure **MySQL** is installed and running.
2. Create a database and table (refer to `setup.sql` if provided).
3. Update your database connection settings in the script:
   ```python
   connection = mysql.connector.connect(
       host="localhost",
       user="your_mysql_username",
       password="your_mysql_password",
       database="your_database_name"
   )
4. Install the required package: pip install mysql-connector-python
