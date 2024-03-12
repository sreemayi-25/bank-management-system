# bank-management-system
This project is a simple command-line Bank Management System implemented in C++. It provides basic functionalities such as creating new accounts, depositing and withdrawing money, checking balances, displaying all account holders, closing accounts, and modifying account details.

## Features: ##
* New Account Creation: Users can create new accounts by providing necessary details like account number, account holder name, account type (Savings or Current), and initial deposit amount.
* Deposit and Withdrawal: Users can deposit or withdraw money from existing accounts.
* Balance Enquiry: Users can check the balance of any account by entering its account number.
* Display All Accounts: Displays a list of all existing account holders with their account numbers, names, types, and balances.
* Close Account: Allows users to close an existing account by providing its account number.
* Modify Account: Users can modify details of an existing account such as account holder name, account type, and balance.

## How to Use: ##
1. Clone the repository or download the source code.
2. Compile the source code using a C++ compiler (e.g., g++).
3. Execute the compiled binary to start the Bank Management System.
4. Follow the on-screen instructions to perform various operations like creating accounts, depositing/withdrawing money, etc.
5. Choose the "Exit" option to close the application.

## Note:  ##
This project uses dynamic memory allocation to manage accounts, which means memory is allocated or deallocated as needed during runtime.
Ensure that the initial deposit amount provided during account creation meets the minimum balance requirements (≥500 for Savings and ≥1000 for Current accounts).
```cpp
