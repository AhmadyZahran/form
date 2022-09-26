# form

Create simple Login and Sign up pages.

uses for this php and bootstrap

It contains :

1. Landing Page 
Your landing page will contain a welcoming message and two links one for the login page and the other one for the sign-up page 

2. Sign up Page 
Create a signup page containing the following input, all the inputs should be required and have validation as below:
Email: Should be an email input and follow the email pattern [regex] also the email is required
Mobile: Should be 14 digits also this field is required 
Full name: Should be in 4 sections fname, middle name, last name, family name validation must be done to make sure he entered a text 
Password: The password should be at least 8 characters and this field is required and should cover password strength rules such as (upper case, lower case, numbers, special character, no spaces ) 
Password Confirmation: The password should match the above field [Password]
Date of Birth: The date of birth should contain three fields Day, Month, Year (DD, MM, YYYY) if the registered above 16 years old he can register else error appear 

3.  Login
After the user is registered his information should be stored in an associative array. The inserted information in the login form must match the signup, if all the information is validated the user should be redirected to the welcome page otherwise an alert message will be displayed.

4. Welcome Page 
The user will be redirected to this page if his information is valid, this page will display the user email and static welcoming message 

5. Admin Login : 
 create a superuser, this user can log in from the same admin page after he logged in.  
