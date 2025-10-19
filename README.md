# 💳 Bank Management System

A **Java-based desktop application** built in **IntelliJ IDEA** with **MySQL** integration.
The project simulates core banking operations such as **account creation, deposits, withdrawals, and PIN verification**, providing a simple yet effective system for managing customer accounts.

## 🚀 Features

* 🧾 **Account Creation** – Add new customers with personal and account details.
* 🔐 **PIN Generation** – Automatically generates a secure PIN for each new account.
* 💰 **Deposit & Withdraw** – Perform transactions with real-time balance updates.
* 🧍‍♂️ **Customer Authentication** – Users must enter a valid ID to access their PIN and perform transactions.
* 📋 **Data Storage** – All account information and transactions are stored securely in a **MySQL database**.
* 🖥️ **User Interface** – Simple, form-based interface for easy interaction.

---

## 🛠️ Technologies Used

* **Java (JDK 8+)**
* **IntelliJ IDEA**
* **MySQL Database**
* **JDBC (Java Database Connectivity)**
* **Command Line Interface (CMD)**

---

## ⚙️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/nimra-ijaz1/Bank-Management-System-.git
```

### 2. Open the Project

* Launch **IntelliJ IDEA** and open the cloned folder.

### 3. Set Up Database

* Create a MySQL database named `bank_management`.
* Import the provided SQL file (if available) or manually create tables for `customers`, `accounts`, and `transactions`.

### 4. Update Database Credentials

* In your Java file (e.g., `DatabaseConnection.java`), update:

```java
String url = "jdbc:mysql://localhost:3306/bank_management";
String user = "root";
String password = "your_password";
```

### 5. Compile and Run Using CMD

* Open **Command Prompt (CMD)** and navigate to the project directory:

```cmd
cd path\to\Bank-Management-System-
```

* Compile the Java files:

```cmd
javac -cp ".;path\to\mysql-connector-java.jar" *.java
```

* Run the main class:

```cmd
java -cp ".;path\to\mysql-connector-java.jar" MainClassName
```

> Replace `MainClassName` with the name of your main Java class (e.g., `BankManagementSystem`).


## 👩‍💻 Author

**Nimra Ijaz**

