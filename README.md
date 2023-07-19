# Email Client

This Email Client is a Python program that allows users to send and receive emails using Gmail. It provides two main functionalities: sending emails and checking emails.

## Sending Emails

To send an email, follow these steps:

1. Run the program and choose option 1 to send emails.
2. Enter your email address and password when prompted.
3. Enter the recipient's email address.
4. Provide the subject and message for the email.
5. Optionally, you can specify a file attachment by providing the file path.
6. The program will use the SMTP protocol to securely send the email using the provided Gmail account.

## Checking Emails

To check emails, follow these steps:

1. Run the program and choose option 2 to check emails.
2. Enter your email address and password when prompted.
3. Enter the date (in the format YYYY-MM-DD) from which you want to retrieve emails.
4. Optionally, you can specify a desired sender's email address to filter the results.
5. The program will use the IMAP protocol to securely connect to the Gmail server and retrieve the emails.
6. The program will display the subject, sender, date, and optional attachments for each email matching the criteria.

## Prerequisites

- Python 3.x
- Required Python packages: `smtplib`, `email`, `imaplib`, `getpass`

## How to Run

1. Clone this repository to your local machine or download the source code.
2. Install the required Python packages if you haven't already (`pip install smtplib email imaplib getpass`).
3. Open a terminal or command prompt and navigate to the directory containing the source code.
4. Run the program using the command `python email_client.py`.
5. Follow the on-screen instructions to send or check emails.

## Note

- This program uses Gmail's SMTP and IMAP servers, so it requires a Gmail account to send and receive emails.
- Make sure to enable IMAP access for your Gmail account by going to the account settings.
- For security purposes, it is recommended to use an app password instead of your actual Gmail account password.

