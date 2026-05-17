# Login Test Cases – SauceDemo

This project contains manual test cases for the login functionality.

---

## Test Case 1: Valid Login

Steps:
- Username: standard_user eingeben  
- Password: secret_sauce eingeben  
- Auf „Login“ klicken  

Expected Result:
Der Benutzer wird erfolgreich eingeloggt und sieht die Produktseite.

---

## Test Case 2: Invalid Login

Steps:
- Falschen Username oder Passwort eingeben  
- Auf „Login“ klicken  

Expected Result:
Eine Fehlermeldung wird angezeigt.

---

## Test Case 3: Empty Fields

Steps:
- Username und Passwort leer lassen  
- Auf „Login“ klicken  

Expected Result:
Validierungsnachricht wird angezeigt (z. B. „Username is required“).
