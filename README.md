# Email Validator GUI
![Python](https://img.shields.io/badge/python-3.10-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

This is a simple Python GUI application that validates email addresses using regular expressions. It checks for basic email format validation and also validates email addresses for popular email services such as Gmail, Outlook (including Hotmail), and Yahoo.

## How to Use

1. Make sure you have Python installed on your system.
2. Install the required packages by running the following command:
   ```
   pip install tk
   ```
3. Run the script `email_validator_gui.py`.
4. Enter an email address in the provided input field and click the "Validate Email" button.
5. The application will display a message box indicating whether the email address is valid or not.

## Email Validation

The script uses regular expressions to perform email validation. The basic pattern for email validation is defined as follows:
```
^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$
```
This pattern checks for basic email format validation, ensuring that the email address contains a local part, "@" symbol, domain name, and top-level domain with at least two characters.

## Popular Email Services

The script also includes regular expression patterns to check for specific email services such as Gmail, Outlook (including Hotmail), and Yahoo. If the email address matches any of these patterns, the application displays a more specific validation message.

## Input Validation

Before performing email validation, the application checks if the input field is empty. If no email address is provided, a warning message will be displayed.

Please note that while this application performs basic email format validation, it does not guarantee the existence or deliverability of the email addresses.

## Examples of email addresses
Here are some examples of email addresses that can be tested using the Email Validator GUI:

### Valid Email Addresses:

john.doe@gmail.com
alice.smith@hotmail.com
mike123@yahoo.com
jane_doe@outlook.com
support@company.com

### Invalid Email Addresses:
john.doe
alice.smith@com
mike123@123
jane_doe@outlook
support@company
Email Addresses for Popular Services:

test123@gmail.com (Valid Gmail address)
user456@hotmail.com (Valid Outlook/Hotmail address)
example@yahoo.com (Valid Yahoo address)

Feel free to use and modify this code to enhance your Python programming skills! ^^
