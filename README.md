# 📧 Send Mail Using Python

Send emails using Python's `smtplib` and `email` libraries. This project provides a simple script for sending emails programmatically.

## Introduction

The Send Mail Using Python project enables you to send emails using a Python script. It uses the `smtplib` library for establishing an SMTP connection and the `email` library for creating and formatting email messages.

## Features

- **Easy Configuration:** Set up sender's email, password, recipient's email, subject, and message directly in the script.
- **Dynamic Email Content:** Customize the email subject and message content based on user input.
- **Secure SMTP Connection:** Utilizes a secure SMTP connection for sending emails.

## Prerequisites

Ensure you have Python installed on your system.

## Installation

1. Clone the GitHub repository:

    ```bash
    git clone https://github.com/codeterrayt/sendmailusingpython.git
    cd sendmailusingpython
    ```

2. Open `main.py` in a text editor.

3. Configure the following variables:
    - `server_login_mail`: Your email address for SMTP login.
    - `server_login_password`: Your email password for SMTP login.

4. Save the changes.

5. Run the script:

    ```bash
    python main.py
    ```

6. The script will prompt you for the recipient's email, subject, and message. Enter the details, and the email will be sent.

## Usage

1. Execute the script in a terminal.

2. Enter the recipient's email address when prompted.

3. Enter the subject and message content as instructed.

4. The script will send the email, and you will see a confirmation message.

## Development

Feel free to explore and modify the code to suit your specific needs. You can extend the functionality, add attachments, or integrate it into a larger project.

## Acknowledgments

This project uses the `smtplib` and `email` libraries for sending emails. Explore the [Python `smtplib` Documentation](https://docs.python.org/3/library/smtplib.html) and [Python `email` Documentation](https://docs.python.org/3/library/email.html) for more information.

📤 Happy Email Sending with Python! 🚀
