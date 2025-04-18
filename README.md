# ATM Simulation with PIN Authentication

## Overview
This is a simple ATM simulation program written in C that allows users to perform basic banking operations such as balance inquiry, deposits, withdrawals, and PIN changes. The program uses a menu-driven interface with PIN authentication to ensure secure access to the ATM system.

## Features
- **PIN Authentication**: The user is required to enter a PIN to access the ATM system. The system allows up to 3 attempts to enter the correct PIN.
- **Balance Inquiry**: View the current account balance.
- **Deposit**: Deposit money into the account.
- **Withdrawal**: Withdraw money from the account with balance verification.
- **PIN Change**: Change the PIN after providing the correct old PIN.
- **Exit**: Option to exit the ATM simulation.

## Requirements
- **C Compiler**: A C compiler like GCC or MinGW.
- **Operating System**: Compatible with Windows, Linux, or macOS.

## Usage
1. **Compile the code**:
    ```bash
    gcc atm_simulation.c -o atm_simulation
    ```

2. **Run the program**:
    ```bash
    ./atm_simulation
    ```

3. **Authenticate**: When prompted, enter the PIN (default is `1234`). You have 3 attempts to enter the correct PIN.
4. **Menu Options**: After successful authentication, you will see the following options:
   - **Check Balance**
   - **Deposit**
   - **Withdraw**
   - **Change PIN**
   - **Exit**

## Example

```plaintext
Enter PIN: 1234
ATM Menu:
1. Check Balance
2. Deposit
3. Withdraw
4. Change PIN
5. Exit
Select an option: 1
Your current balance is: $1000.00

Enter PIN: 1234
ATM Menu:
1. Check Balance
2. Deposit
3. Withdraw
4. Change PIN
5. Exit
Select an option: 2
Enter deposit amount: $500
You have successfully deposited $500.00. New balance: $1500.00
