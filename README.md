# Gmail Client Code

A simple Python script to send emails using Gmail's SMTP server

## Description

This project provides a straightforward Python implementation for sending emails through Gmail's SMTP server using SSL encryption. It reads message content from a text file and sends it as an email with a timestamp in the subject line. Perfect for automated email notifications, log delivery, or simple email automation tasks.

## Features

- Send emails securely via Gmail's SMTP server with SSL encryption
- Read email body content from a text file (`message.txt`)
- Automatic timestamp in email subject line
- Support for MIME multipart messages

## Technologies Used

- Python 3
- smtplib (SMTP protocol client)
- ssl (TLS/SSL encryption)
- email.mime (MIME message construction)

## Installation

```bash
# Clone the repository
git clone https://github.com/bryanseah234/gmail-client-code.git

# Navigate to project directory
cd gmail-client-code
```

## Usage

1. Open `email.py` and configure the following fields:
   - Line 17: Replace `'email'` and `'password'` with your Gmail credentials
   - Line 19: Replace `"from who name"` with sender's display name
   - Line 20: Replace `"send to email"` with recipient's email address
   - Line 28: Replace both email addresses with sender and recipient emails

2. Create a `message.txt` file in the same directory with your email content

3. Run the script:
```bash
python email.py
```

**Note:** You will need to use an App Password for authentication. Generate one from your Google Account settings under Security > 2-Step Verification > App passwords.

## Disclaimer

1. FOR EDUCATIONAL PURPOSES ONLY
2. USE AT YOUR OWN DISCRETION
3. Never commit credentials to version control - consider using environment variables for sensitive data

## License

MIT License

---

**Author:** <a href="https://github.com/bryanseah234">bryanseah234</a>
