🏦 Online Banking System in C
📘 Project Overview
This is a Console-Based Online Banking System developed in the C programming language. It provides basic banking functionalities such as creating an account, logging in, checking balance, depositing money, withdrawing money, and viewing transaction history.

✨ Features
Account Creation

User Login

Check Balance

Deposit Money

Withdraw Money

Transaction History

Exit and Save Data to File

🛠️ Tools & Technologies
Programming Language: C

Compilation: GCC Compiler

Data Storage: File Handling (TXT file)

📁 File Structure
perl
Copy
Edit
online-banking-system-c/
├── main.c               # Main C program
├── users.txt            # Stores user data
├── transactions.txt     # Stores transaction logs
├── README.md            # Project documentation
└── Makefile             # (Optional) For easy compilation
🧾 How to Run
1. Compile the Code
Using GCC:


gcc main.c -o banking
2. Run the Program
bash
Copy
Edit

💡 Example Functional Flow
Register a new user with name, PIN, and initial deposit.

Login with account number and PIN.

Choose an operation from the menu:

Check Balance

Deposit Money

Withdraw Money

View Transactions

Logout

🔐 Security Notes
PINs are stored in plain text in this simple version. For real-world applications, hashing/encryption is a must.

No concurrency handling; designed for single-user command-line use.

📬 Contact
Author: Krish Rana
📧krrishrajput263@gmail.com.com
🎓 BCA Student, Chandigarh University

