Name: Ballewar Janhvi Devendra
Domain: Full Stack Web Development
Duration: 25th July to 25th September 2024
Task: Build a Login and Signup Page using PHP

OVERVIEW:
1. Database Setup (MySQL)
Task: Create a database and a table to store user details.
Steps:
Set up a MySQL database named user_system.
Create a table users with columns: id, username, email, password, and created_at.
Ensure that passwords are securely stored (using hashing).

2. Frontend Development (HTML & CSS)
Task: Create HTML forms for the Login and Signup pages.
Steps:
Design the forms using HTML and CSS, ensuring a user-friendly interface.
Include fields like username, email, and password for signup, and username and password for login.
Use CSS to style the forms with proper layouts, input fields, and buttons.

3. Backend Development (PHP)
Task: Implement PHP logic to handle form submissions and interact with the database.
Steps:
Signup (signup.php):
Receive form data from the signup page.
Hash the user’s password using password_hash().
Store the user’s information (username, email, and hashed password) into the MySQL database.
Return a message indicating whether signup was successful or not.
Login (login.php):
Receive form data from the login page.
Fetch the user’s information from the database based on the entered username.
Verify the entered password using password_verify() against the stored hashed password.
Display appropriate messages based on login success or failure.

4. Connection and Integration
Task: Connect the frontend and backend.
Steps:
Link the signup form to signup.php for processing.
Link the login form to login.php for processing.
Ensure proper form validation and submission via POST methods.

Tools Used:
Frontend: HTML and CSS for creating forms and styling.
Backend: PHP to handle form submissions, password hashing, and database interaction.
Database: MySQL to store and retrieve user information.

Flow of the Task:
User Signup:
User fills the signup form → Data sent to signup.php → PHP stores data into the database → Message is displayed.
User Login:
User fills the login form → Data sent to login.php → PHP checks the database for matching credentials → Success or error message is displayed.

SUMMARY:
This task ensures that user data is securely handled and managed across the frontend and backend components, with proper integration between the client-side interface and the server-side logic.







