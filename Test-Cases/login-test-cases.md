# Login Page Test Cases

## TC-001 Successful login

Preconditions:
User has a valid account.

Steps:
1. Open login page
2. Enter valid email
3. Enter correct password
4. Click "Login"

Expected result:
User is redirected to the dashboard.


## TC-002 Login with incorrect password

Preconditions:
User has a registered account.

Steps:
1. Open login page
2. Enter valid email
3. Enter wrong password
4. Click "Login"

Expected result:
Error message appears: "Invalid email or password".


## TC-003 Empty fields validation

Steps:
1. Open login page
2. Leave email empty
3. Leave password empty
4. Click "Login"

Expected result:
Validation message appears.
