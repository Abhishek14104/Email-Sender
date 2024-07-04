# Email Sender Script
This Python script demonstrates how to send automated emails using the smtplib and email libraries. It loads recipient information from an Excel file and sends personalized emails using a Gmail account.

## Features
- Dynamic Email Sending: Reads recipient email addresses and names from an Excel file (list.xlsx).
- Personalized Messages: Each email includes a personalized message addressing the recipient by name.
- Secure Authentication: Uses TLS encryption to securely authenticate and send emails through Gmail's SMTP server.

## Usage
- Clone the Repository:\
-- git clone https://github.com/yourusername/email-sender.git \
-- cd email-sender

- Install Dependencies:\
-- pip install openpyxl

- Prepare Excel File:
Create an Excel file named list.xlsx.
Populate it with recipient email addresses in the first column and recipient names in the second column.

## Run the Script:

python send_email.py your_email@gmail.com your_password

Replace your_email@gmail.com with your Gmail address and your_password with your Gmail app password (not your regular password as that will raise error due to Google security policy).
--- To generate your email's app password go to your Google Account Manager then to Security then turn on 2-Step Verification and then create your app password.

## Example
Here's an example of how to use the script:
- python send_email.py pythontesting14104@gmail.com "your_password"
