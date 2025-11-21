# ATM Simulation in Python

This project is a simple command-line ATM simulation implemented in Python using object-oriented programming.  
The `ATM` class allows a user to withdraw money, deposit money, use an additional account, and quit the session.

## Features

- Object-oriented design (`ATM` class)
- Money withdrawal with optional additional account balance
- Deposit functionality
- Input-driven menu system
- Friendly intro and exit messages
- Validation for insufficient balance and incorrect input

## Class Overview

### ATM(name, surname, account, addaccount)

**Parameters:**
- `name` – User’s first name  
- `surname` – User’s last name  
- `account` – Main account balance  
- `addaccount` – Additional account balance  

### Methods

#### Intro()
Displays a welcome message and starts the ATM options menu.

#### Options()
Presents available operations:
- `'w'` → Withdraw  
- `'d'` → Deposit  
- `'q'` → Quit  

#### Withdrow()
(typo kept as in the original code)  
Allows the user to:
- Use additional account  
- Withdraw only from the main account  
- Quit  

Validates balance before withdrawal.

#### Deposit()
Allows the user to deposit money into the main account.

#### Finish()
Displays a goodbye message and ends the session.

#### How to Run
Install Python 3.x

Place the script in a file named atm.py

Run the program:

python atm.py

Follow the on-screen menu to interact with the ATM.

#### License

This project currently has no license. You may add one if needed.
