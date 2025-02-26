# PHP Registration Task

This is a simple PHP registration system with user validation and password hashing.

## 📌 Features
- User registration with name, email, and password.
- Email validation to prevent duplicate accounts.
- Password hashing using `password_hash()`.
- Error handling for invalid inputs.

## 🛠 Installation  
Follow these steps to set up the project on your local machine:  

1️⃣ **Clone the Repository**  
```sh
git clone https://github.com/Youssef-M-Salama/phpRegistrationTask.git  
cd phpRegistrationTask  
2️⃣ Set Up the Database

Open phpMyAdmin or any MySQL client.
Create a new database named my_first_project.
Import the provided database.sql file (or copy and execute the SQL dump manually).
3️⃣ Configure Database Connection

Open config/database.php (or includes/db.php if applicable).
Update the database credentials according to your local setup:

$host = "localhost";  
$db_name = "my_first_project";  
$username = "root";  // Change if needed  
$password = "";      // Change if needed  

4️⃣ Start the Local Server

If using XAMPP, move the project folder to htdocs and start Apache & MySQL.
Open your browser and visit:
sh

http://localhost/phpRegistrationTask/  

5️⃣ Register and Log In

Open register.php to create a new account.
Navigate to login.php to log in.
After successful login, you'll be redirected to dashboard.php.
🚀 Now you're all set! Enjoy using your PHP registration system.
نسخ
تحرير






