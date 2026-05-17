# Bug Reports – Login Feature (SauceDemo)

This file contains reported bugs for the login functionality.

---

## BUG-01: No clear error message for empty login

Steps to reproduce:
- Go to login page  
- Leave username and password empty  
- Click on Login  

Actual Result:
A message is shown, but not clear enough for the user.

Expected Result:
A clear validation message should appear (e.g. "Username is required").

---

## BUG-02: Incorrect login shows generic error

Steps to reproduce:
- Enter invalid username  
- Enter invalid password  
- Click on Login  

Actual Result:
Generic error message is displayed.

Expected Result:
A clear message like "Username or Password is incorrect" should appear.
