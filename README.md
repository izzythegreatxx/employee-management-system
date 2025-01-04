This is a comprehensive Employee Management System designed in Python. It includes features for managing employee records, user authentication, and logging, along with advanced security features like CAPTCHA validation and session timeout.

-Features-
User Authentication:

Secure user registration and login using hashed passwords.
Login attempt restrictions and CAPTCHA verification.
Automatic session timeout after 10 minutes of inactivity.
Blocking users after repeated failed login attempts.
Employee Management:

Add, update, and remove employee records.
View a list of current employees.
Save and load employee data to/from a JSON file.
Security:

Password strength validation.
CAPTCHA to mitigate brute force attacks.
Logging of important events like user logins, employee updates, and invalid access attempts.
Logging:

Comprehensive logging to track user actions and errors in employee_management.log.

-Main functionalities-

Authentication:
Register and log in as a user.
Secure password storage using bcrypt hashing.
Temporary blocking of users after excessive failed login attempts.

Employee Management:
Add new employees with fields like ID, name, email, salary, start date, and title.
Update existing employee records.
Remove employees from the database.
View a complete list of all employees.

Data Persistence:
Save and load employee data in JSON format.
Save user credentials securely.

Logging:
All critical actions and warnings are logged for auditing.

-Prerequisites-

-Python 3.6 or later
Packages
-bcrypt (install using pip install bcyrypt) 
-json
