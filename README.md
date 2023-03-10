# Password Manager

This is a simple password manager application written in Python. It allows users to store and retrieve passwords for different accounts in a secure and organized manner.

## Features

Store passwords for different accounts
Securely encrypt passwords using AES-256 encryption
Generate strong and secure passwords
Retrieve passwords when needed
View a list of all stored accounts
Installation

## Clone the repository:
bash
Copy code:
```
git clone https://github.com/divyanshv21/password-manager.git
```
Install the required dependencies:

1. Install the requirements
```
pip install -r requirements.txt
```
2. Run the application:
```
python password_manager.py
```

## Usage

Start the application by running the command python password_manager.py
You will be presented with a menu that allows you to select different options.
To add a new account, select "Add Account" from the menu and provide the necessary information.
To retrieve a password for an existing account, select "Retrieve Password" and enter the account name.
To view a list of all stored accounts, select "List Accounts".
To exit the application, select "Exit".

## Security

This password manager uses AES-256 encryption to securely store passwords. The encryption key is generated randomly and is not stored anywhere on the system. This ensures that even if an attacker gains access to the password database, they will not be able to retrieve the passwords without the encryption key.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or bug reports.
