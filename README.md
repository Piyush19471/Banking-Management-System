🏦 Simple Banking System
This project is a Java-based banking application utilizing JDBC for database interaction. It provides essential banking functionalities like user registration, account creation, and money transactions (debit, credit, transfer).

✨ Key Features:
👤 User Registration & Login:

Users can register with their name, email, and password.
Registered users can log in with credentials.
💳 Account Management:

Users can open a new bank account if they don't have one.
Each account has a unique account number, balance, and security pin.
Account numbers start from 10000100, incrementing sequentially.
💸 Transactions:

➖ Debit Money: Withdraw funds with account number, amount, and security pin.
➕ Credit Money: Deposit funds using account number and amount.
🔄 Transfer Money: Securely transfer money between accounts.
💰 Balance Inquiry: Check your balance after verifying with the security pin.
🔐 Security:

Transactions require a valid security pin.
Ensures sufficient balance before processing debit/transfer transactions.
🛠️ Code Components:
👤 User Class: Manages registration and login.
💳 Accounts Class: Handles account creation and existence checks.
📊 AccountManager Class: Manages debit, credit, transfer, and balance inquiry.
🖥️ BankingApp Class: Main entry point for user interaction.
🗄️ Database Schema:
User Table: Stores full_name, email, and password.
Accounts Table: Stores account_number, full_name, email, balance, and security_pin.
Enjoy seamless banking with our simple, secure system! 🚀

