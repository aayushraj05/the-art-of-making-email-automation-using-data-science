# Email Sending System with SQLite, CSV, and SMTP

This Python script provides a simple solution to load email data from a CSV file, store it in an SQLite database, and send personalized emails using Gmail’s SMTP server. The script is cross-platform and can be used on both Windows and POSIX-based systems.

## Features
- **Email Validation**: Ensures emails are in a valid format before sending.
- **SQLite Database**: Stores user email addresses and names.
- **CSV File Support**: Reads email and name data from a CSV file and loads it into the SQLite database.
- **Gmail SMTP**: Sends emails to all users stored in the database using Gmail’s SMTP server.

## Requirements

- **Python 3.x**: Make sure you have Python installed.
- **Libraries**:
  - `sqlite3`: For database operations (built-in Python library).
  - `smtplib`: For sending emails (built-in Python library).
  - `re`: For regular expression-based email validation (built-in Python library).
  - `email.mime`: For constructing email messages.
  - `csv`: For handling CSV file operations (built-in Python library).
  - `os`: For operating system interactions (built-in Python library).
  
  You can install any additional required libraries using:
  ```bash
  pip install email
