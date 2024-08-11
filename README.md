# advance-bulk-sms-sender
Bulk SMS Sender is a web app that integrates with Twilio API to send bulk SMS messages. It features contact list import, message customization, and detailed sending logs. Ideal for marketing campaigns, notifications, and large-scale communication, with a user-friendly interface for efficient SMS management.

![Screenshot 2024-08-11 124623](https://github.com/user-attachments/assets/c17f087f-2780-4124-b2fc-b30cc16238ba)


Overview
This application is a Bulk SMS Sender that integrates with the Twilio API to send messages to multiple recipients simultaneously. The application includes functionalities for sending SMS, importing phone numbers from files, and viewing sending logs.

Prerequisites
Twilio Account: You must have an active Twilio account with an Account SID, Auth Token, and a verified phone number.
Web Server: This code is designed to be hosted on a web server.
JavaScript Enabled: Ensure that JavaScript is enabled in your browser.
Setup and Installation
Obtain Twilio Credentials:

![Screenshot 2024-08-11 124553](https://github.com/user-attachments/assets/83b53fa3-75ac-47d2-8a16-e2c10e7840e9)

Sign up or log in to your Twilio account.
Navigate to your Twilio console to get your Account SID and Auth Token.
Ensure you have a verified phone number (Twilio Phone Number) to send SMS.
Host the Application:

Upload the provided HTML file to your web server.
Ensure the file is accessible through a web browser.
How to Use
Access the Application:

Open the application in your web browser by navigating to the URL where it's hosted.
Send SMS:

Go to the Send SMS tab.
Enter your Twilio Account SID, Auth Token, and Twilio Phone Number.
Enter the recipient phone numbers (one per line).
Type the message you want to send.
Click Send Bulk SMS.
The progress bar will show the sending status. Once complete, you’ll see a summary of successfully sent and failed messages.
Import Phone Numbers:


![Screenshot 2024-08-11 124537](https://github.com/user-attachments/assets/a0b80901-8bdd-4361-ab22-a6ee80178fd4)

Go to the Import Numbers tab.
Upload a .csv or .txt file containing the phone numbers.
Once uploaded, the numbers will be automatically populated into the recipient field in the Send SMS tab.
View Sending Logs:

Go to the Sending Logs tab.
The table will show the date/time, recipient numbers, and the status (Success/Failed) of each message sent.
Important Notes
Security: The Twilio API calls in this demo are made directly from the frontend, which is not recommended for production use. For production, implement these API calls in a secure backend to protect your credentials.
Supported File Formats: Only .csv and .txt files are supported for importing phone numbers.
Footer Protection: The footer of the page is protected against removal or alteration. If the footer is tampered with, the page will automatically reload.
License
This application was created by CodeUpBrand. Feel free to modify it according to your needs.

Support
For any issues or further customization, contact support at CodeUpBrand.

