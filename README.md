# Lab-Application
Student Registration Form
This is a simple student registration form web application that allows users to register students by providing their full name, gender, and email address. The registered students are stored in a MySQL database.

Requirements
PHP 7.0 or higher
MySQL database
Installation and Setup
Clone or download the project files to your local machine.

Create a new MySQL database for the application, e.g., registration.

Import the registration.sql file located in the project root directory into your MySQL database to create the necessary table.

Update the database connection details in the Registration.php file. Modify the following line to include your MySQL database credentials:

php

$conn = new mysqli('localhost', 'root', '', 'registration');
Replace 'localhost' with your MySQL server hostname, 'root' with your MySQL username, '' with your MySQL password (if any), and 'registration' with the name of your created database.

Save the changes to the Registration.php file.

Start a web server and make sure PHP is enabled.

Open the application in a web browser by accessing the Registration.php file. For example, if you are running the application locally, the URL might be http://localhost/Registration.php.

Usage
Access the application in a web browser to view the student registration form.
Fill in the required fields: Full Name, Gender, and Email Address.
Click the "Submit" button to register the student.
If the registration is successful, a success message will be displayed.
If there are any validation errors, such as missing or invalid fields, error messages will be displayed.
The registered students will be listed below the registration form.
License
This project is licensed under the MIT License.

Feel free to modify and enhance the application according to your needs.
