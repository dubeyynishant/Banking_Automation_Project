# 🏦 Banking Automation Project

A **Python-based Banking Automation System** designed to simulate real-world banking operations such as account creation, deposits, withdrawals, balance inquiry, transaction tracking, and email notifications. The project uses **SQLite** for data storage and follows a **modular programming approach** for better readability and maintenance.

---

## 📌 Project Overview

The **Banking Automation Project** is a console-based application that automates core banking functionalities. It is ideal for beginners and freshers who want to understand how banking systems work internally using Python, databases, and modular files.

This project demonstrates:

* Database connectivity using SQLite
* Structured and reusable Python modules
* Basic automation logic used in banking systems
* Email notification integration
* CRUD operations on financial data

---

## 🗂 Project Structure

```
Banking_Automation_Project/
│
├── main_project.py        # Main program (user interaction & flow control)
├── project_tables.py     # Database table creation & queries
├── project_mail.py       # Email notification functionality
├── project_outline.txt   # Project workflow & logic outline
├── bank.sqlite           # SQLite database file
├── requirements.txt      # Required Python libraries
```

---

## ⚙️ Features

✔ Create new bank accounts
✔ Store customer details securely
✔ Deposit money
✔ Withdraw money
✔ Check account balance
✔ Maintain transaction records
✔ SQLite database integration
✔ Email alerts for transactions
✔ Modular and beginner-friendly code

---

## 🧠 Technologies Used

* **Programming Language:** Python 3
* **Database:** SQLite
* **Libraries & Modules:**

  * `sqlite3`
  * `smtplib`
  * `email`
  * `datetime`
  * Other standard Python libraries

---

## 🗄 Database Details

* **Database Name:** `bank.sqlite`
* Stores:

  * Customer account details
  * Balance information
  * Transaction history
* Automatically created and updated using `project_tables.py`

---

## 🧩 File Description

### 🔹 `main_project.py`

* Entry point of the application
* Handles user input and menu-driven operations
* Calls database and email functions
* Controls complete banking workflow

### 🔹 `project_tables.py`

* Creates required database tables
* Handles SQL queries (INSERT, UPDATE, SELECT)
* Ensures structured data storage

### 🔹 `project_mail.py`

* Sends email notifications to customers
* Used for transaction alerts and confirmations
* Demonstrates email automation using Python

### 🔹 `project_outline.txt`

* Explains the project flow and logic
* Useful for understanding system design

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/dubeyynishant/Banking_Automation_Project.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd Banking_Automation_Project
```

### 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Project

```bash
python main_project.py
```

---

## 🧪 Sample Operations

* Create a new bank account
* Deposit ₹5000
* Withdraw ₹2000
* Check updated balance
* Receive email notification for transactions

---

## 🎯 Learning Outcomes

This project helps you understand:

* Python modular programming
* Database management with SQLite
* Real-world banking logic
* Email automation in Python
* Clean and maintainable code structure

---

## 🚀 Future Enhancements

* GUI using Tkinter or Streamlit
* Password-based authentication
* Interest calculation
* Loan management module
* Admin dashboard
* Web-based version

---

## 🤝 Contribution

Contributions are welcome!
Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is open-source and available for educational purposes.

---

## 👨‍💻 Author

**Nishant Dubey**

🔗 GitHub: [@dubeyynishant](https://github.com/dubeyynishant)


