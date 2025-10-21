# Bank-Application-using-Python
This project is a console-based Bank Application simulation developed in Python. It demonstrates fundamental programming concepts, including API integration, data persistence using JSON, user authentication, and core transactional logic (Deposit, Withdrawal, Balance Inquiry).

## Features
**User Generation:** Automatically populates a database with 10 unique user accounts (username and password) by fetching data from the external randomuser.me/api/.

**Data Persistence:** Uses the built-in json library to store and retrieve all user account information (username, password, and current Balance) in a local file named dump.json.

**User Authentication:** Implements a robust login mechanism with a search function to validate the entered username and a password check with a limited number of retries.

**Transactional Logic:** Supports four main menu options for logged-in users:

Deposit: Adds a specified amount to the user's current balance.

Withdrawal: Deducts a specified amount from the user's current balance (basic subtraction implemented).

Check Balance: Displays the user's available balance.

Exit: Terminates the session.

**Dependencies:** Primarily uses the standard Python libraries: requests for API calls, and json for file I/O.

## Technical Stack
Language: Python

Libraries: requests, json

API: https://randomuser.me/api/

Data Storage: JSON file (dump.json)
