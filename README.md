# 🏦 Bank Management System (C++)

A **console-based Bank Management System** built using **Object-Oriented Programming (OOP) in C++**.
This project simulates basic banking operations such as **account creation, login, deposits, withdrawals, balance inquiry, and transaction history**, with **persistent file storage**.

---

## 📌 Features

* Create a new bank account
* Secure login using account number and password
* Deposit and withdraw money
* Enforced minimum balance (₹500)
* Check account balance
* View account details
* View transaction history
* Persistent storage using file handling
* Colorful and user-friendly console UI

---

## 🛠️ Technologies Used

* **Language:** C++
* **Paradigm:** Object-Oriented Programming (OOP)
* **Concepts Used:**

  * Classes & Objects
  * Encapsulation
  * File Handling (`fstream`)
  * Vectors (`std::vector`)
  * Menu-driven programming

---

## 📂 Project Structure

```text
Bank.cpp        // Main source file (single-file project)
PBOI.txt        // Stores IFSC / account counter (auto-generated)
PBOIxxxx.txt    // Individual account data files
```

Each account is stored in a **separate text file**, ensuring data persistence even after program termination.

---

## ▶️ How to Compile and Run

### Using VS Code / Terminal (Recommended)

```bash
g++ -std=c++17 Bank.cpp -o Bank
./Bank        # Linux / macOS
.\\Bank       # Windows
```

### Using Dev-C++

* Open the project/file
* Ensure **Project Type = Console Application**
* Use **Execute → Compile & Run (F11)**

---

## 🔐 Default Rules & Constraints

* Minimum balance must always be **₹500**
* Password is required for login
* Account number is auto-generated

---

## 🖥️ Sample Functionalities

* **Account Creation:** Collects user details and generates a unique account number
* **Login:** Validates credentials using stored file data
* **Transactions:** Automatically recorded and displayed

---

## 📈 Future Improvements (Planned)

* Password encryption / hashing
* Date & time stamping for transactions
* Multiple account handling using dynamic objects
* Exception handling
* Split project into `.h` and `.cpp` files
* Improved validation for user inputs

---

## 🎓 Academic Use

This project is suitable for:

* **OOP in C++ coursework**
* **2nd / 3rd semester mini-projects**
* **Viva and lab evaluations**

---

## 👤 Author

**Aryan**
C++ | OOP | DSA Learner

---

## 📜 License

This project is created for **educational purposes** and is free to use or modify.

---

⭐ If you find this project helpful, feel free to star the repository!
