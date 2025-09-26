# ATM System in Java

## Overview
This project is a simple **ATM System** implemented in Java. It allows users to **check balance**, **deposit money**, and **withdraw money** after authenticating with a PIN. The system demonstrates basic Java concepts such as classes, objects, methods, and user input handling.

## Features
- **PIN Authentication:** Users must enter the correct PIN to access the ATM.
- **Check Balance:** View the current account balance.
- **Deposit Money:** Add a specific amount to the balance.
- **Withdraw Money:** Withdraw an amount from the balance if sufficient funds are available.
- **Menu-driven Interface:** Users interact with the ATM via a console menu.
- **Input Validation:** Handles invalid deposits, withdrawals, and menu options.

## Prerequisites
- Java Development Kit (JDK) 8 or higher
- A Java IDE or code editor (e.g., IntelliJ IDEA, Eclipse, VS Code)
- Command-line interface (optional)

## How to Run
1. Clone or download the project.
2. Open the project in your preferred Java IDE.
3. Compile and run `ATMSystem.java`.
4. Follow the on-screen instructions:
   - Enter the PIN (default PIN: `1234`).
   - Choose an option from the menu:
     1. Check Balance
     2. Deposit Money
     3. Withdraw Money
     4. Exit
5. Perform multiple transactions until you choose to exit.

## Sample Interaction
Enter your PIN: 1234

===== ATM MENU =====

Check Balance

Deposit Money

Withdraw Money

Exit
Choose an option: 1
Your current balance is: $1000.0
Choose an option: 2
Enter deposit amount: 500
Successfully deposited $500.0
Choose an option: 3
Enter withdrawal amount: 300
Successfully withdrawn $300.0
Choose an option: 4
Thank you for using the ATM. Goodbye!


## Code Structure
- `ATM` class:
  - Handles account balance and PIN.
  - Contains methods for authentication, checking balance, depositing, and withdrawing money.
- `ATMSystem` class:
  - Main program to interact with the user.
  - Provides menu-driven options for performing ATM operations.

## Future Enhancements
- Allow multiple user accounts.
- Store account data in a file or database.
- Add PIN change functionality.
- Include transaction history for the user.
- Improve security for sensitive data handling.

## Author
- Dilmi Sooriyaarachchi

## License
This project is open-source and free to use for learning purposes.
