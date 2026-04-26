# ATM Simulation System (Python + MySQL)

🧾Overview

A console-based ATM simulation system built using Python and MySQL that mimics real-world banking operations such as user authentication, balance management, and transaction handling.

The project focuses on clean code structure, security practices, and database integration.

✨ Features

🔐 Secure Login System (Password Hashing using SHA-256)
🧑 User Registration (Auto-generated Account Number & Password)
💰 Balance Inquiry
➕ Deposit Money
➖ Withdraw Money
🧾 Transaction History (with timestamps)
🔑 Change Password (with validation)
⚠️ Input Validation & Error Handling

🛠️ Tech Stack

Language: Python
Database: MySQL

Libraries used:
  mysql-connector-python`
  hashlib

📂 Project Structure

ATM/
│── main.py            # Entry point (menu handling)
│── db.py              # Database connection
│── auth.py            # Registration & login logic
│── operations.py      # Banking operations
│── database.sql       # Database schema
│── .gitignore
│── README.md

⚙️ Setup Instructions
#### Windows (CMD):
1️⃣ set DB_PASSWORD=your_mysql_password

2️⃣ Run the project
python main.py

#Sample Flow

1. Register
2. Login
3. Exit

After Login:
1. Balance
2. Deposit
3. Withdraw
4. View Transactions
5. Change Password
6. Logout

🧠 Key Concepts Demonstrated

Modular Programming (Separation of Concerns)
Secure Password Handling (Hashing)
Database Design & CRUD Operations
Input Validation & Error Handling

🚀 Future Improvements

💸 Money Transfer Between Accounts
🌐 Web Application (Django / Flask)
📊 Dashboard & Analytics
🔐 OTP-based Authentication

👩‍💻 Author

Prashanthi Valusa