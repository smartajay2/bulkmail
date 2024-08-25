BulkMail Web App
Description
BulkMail is a MERN stack web application that allows users to send bulk emails from a single email address to multiple recipients. The application supports importing email addresses from an Excel file and sending personalized emails to each address in the list with just one click. This tool is ideal for businesses and organizations looking to streamline their email marketing and communication efforts.

Features
MERN Stack: Built with MongoDB, Express.js, React, and Node.js.
Excel File Import: Upload Excel files containing email addresses.
Bulk Email Sending: Send emails to all addresses listed in the Excel file in one click.
Personalization: Customize email content for each recipient.
Prerequisites
Node.js and npm installed.
MongoDB server running.
An email service provider account (e.g., Gmail, SendGrid) for sending emails.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/smartajay2/bulkmail.git
Navigate to the project directory:

bash
Copy code
cd bulkmail
Install backend dependencies:

bash
Copy code
cd backend
npm install
Install frontend dependencies:

bash
Copy code
cd ../frontend
npm install
Set up environment variables:

Create a .env file in the backend directory.

Add your email service provider credentials and other configurations to the .env file. Example:

makefile
Copy code
EMAIL_SERVICE=your_email_service_provider
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
MONGO_URI=your_mongodb_connection_string
Start the development servers:

In the backend directory:

bash
Copy code
npm start
In the frontend directory:

bash
Copy code
npm start
Access the application:

Open your web browser and navigate to http://localhost:3000 to use the application.

Usage
Upload Excel File:

Go to the upload page.
Choose an Excel file (.xlsx format) containing the email addresses.
Click "Upload" to import the email addresses into the system.
Compose Email:

Navigate to the email composition page.
Enter the subject and body of the email.
You can use placeholders for personalization (e.g., {name}).
Send Bulk Email:

Review the email content.
Click "Send" to send the email to all recipients in the imported list.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing
Feel free to submit issues or pull requests if you find any bugs or have suggestions for improvements.

Contact
For any questions or support, please contact ajayjestin2@gmail.com.

