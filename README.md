# Kazu Bank System

## Overview
Kazu Bank System is a simple banking application written in Python that automatically Creates a database in Mysql and It allows users to create accounts, login, deposit, withdraw funds, and view transaction histories.

## Features
- User account creation
- User login
- Deposit funds
- Withdraw funds
- Display account balance
- View transaction history

## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/kazubank.git
    cd kazubank
    ```

2. **Install the "My sql connector to start with the project:**
    ```bash
    pip install mysql-connector-python
    ```

3. **Set up MySQL database:**
    - Create a MySQL database named `kazubank2`.
    - Update the `db_config` dictionary in the code with your MySQL credentials.

4. **Initialize the database:**
    ```python
    python -c 'from main import initialize_database; initialize_database()'
    ```
5. **initialize_database():**
   Initializes the database with required tables.

7. **User class**
    Represents a user and contains methods for deposit, withdrawal, balance display, and transaction logging.

9. **BankSystem class**
     Handles user account creation, login, and main menu navigation.

## Usage
Run the main program to start the banking system:
```bash
python main.py
