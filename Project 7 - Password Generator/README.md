Password Generator
This project provides a customizable password generator along with a strength-checking function to assess the generated password's security level.

Features
Customizable Password Generation: Specify password length, use of uppercase letters, and symbols.
Secure Generation: Utilizes Python’s secrets module for cryptographic security.
Strength Check: Verifies if the password meets specific strength requirements, including length, uppercase letters, and symbols.

How It Works
Password Generation:
Instantiates a Password object where you can customize:
length: Length of the password (default is 12).
uppercase: Whether to include uppercase letters (default is True).
symbols: Whether to include special characters (default is True).
Uses the generate() method to produce a random password.
Strength Check:

The check_strength() method evaluates if a password meets the following criteria:
At least 16 characters long.
Contains at least one uppercase letter.
Contains at least one special symbol.
If all criteria are met, the password is considered strong.

Usage
Generating a Password
Create an instance of the Password class and generate a password:
password = Password(length=12, uppercase=True, symbols=True)
new_password = password.generate()
print("Generated Password:", new_password)

Checking Password Strength
Check if the generated password is strong:
if password.check_strength(new_password):
    print("The password is strong.")
else:
    print("The password is weak.")

Example Output
Generated Password: fJ3!k9Pb&8L
The password is weak.

Requirements
Python 3.x
No additional libraries are required, as the project uses built-in modules.
