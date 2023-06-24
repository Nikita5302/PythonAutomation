# PythonAutomation
I've created this repository to showcase my skills and share my journey with you. Inside, you'll find a collection of Python scripts designed to automate various tasks and streamline processes.

# Automatic Process Logger and Emailer
This Python script allows you to monitor and log the current running processes on your system, and then automatically send an email with the log file as an attachment.

# Features:
1. Utilizes the psutil library to retrieve information about running processes.
2. Logs the process details to a text file (LogFile.text).
3. Sends an email with the log file as an attachment using the SMTP protocol.
4. Supports Gmail as the email provider, but can be modified for other providers.

# Prerequisites:
Python 3.x installed on your system.
Required libraries: psutil, logging, smtplib, email.

# Usage:
1. Set up your Gmail account and make sure to enable "Less secure app access" for sending emails.
2. Replace the sender_address and sender_pass variables with your Gmail address and password, respectively.
3. Update the receiver_address variable with the email address where you want to receive the log file.
4. Run the script and monitor the terminal for the progress and completion status.
5.Check the inbox of the receiver email address for the email with the log file attachment.
