Bank Management System (C++)
📌 Overview

This is a simple Bank Management System written in C++ that allows you to create and manage bank accounts.
The program stores account data in a binary file, so account details persist even after closing the program.

✨ Features

Create new accounts

View account details

Deposit money

Withdraw money (with minimum balance rules)

Modify account details

Delete accounts

View all accounts in a list

🛠 Requirements

C++ compiler (e.g., MinGW-w64, GCC, or Clang)

VS Code or any C++ IDE

🚀 How to Run

Compile the program

g++ "Bank Management System.cpp" -o bank


Run the program

./bank

📂 Files Used

Bank_Management.dat → Stores account data in binary format

temp.dat → Used temporarily during account deletion

📜 Notes

Savings Account (S) requires a minimum balance of ₹500

Other Account (O) requires a minimum balance of ₹1000

Deposit and withdrawal amounts must be ₹10 or more
