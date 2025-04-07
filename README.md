# Hibernate Project

This is a simple Java project using **Hibernate ORM** to save user data into a MySQL database.

## 📋 What It Does

- Connects to a MySQL database using Hibernate.
- Creates a table and saves user details like name, email, password, gender, and city.

## 🛠️ Technologies Used

- Java
- Hibernate
- MySQL
- Maven

## 📁 Main Files

- `App.java`: Main class to insert data using Hibernate.
- `User.java`: Entity class mapped to the database table.
- `hibernate.cfg.xml`: Hibernate configuration file for database connection.

## ▶️ How to Run

1. Make sure MySQL is running and a database named `hibernate_db` is created.
2. Update DB username/password in `hibernate.cfg.xml` if needed.
3. Open the project in any IDE (like Eclipse or IntelliJ).
4. Run the `App.java` file.

## ✅ Output

- A new table will be created (if not already).
- A user will be saved into the database.
- Console will show SQL logs.

---

Let me know if you want to include screenshots, database table structure, or how to fetch/update/delete users too! 😊
