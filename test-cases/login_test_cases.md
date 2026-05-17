# Login Testfälle - SauceDemo

## Positive Tests

TC-P01: Erfolgreicher Login  
Schritte: standard_user / secret_sauce eingeben, dann auf Login klicken.  
Erwartet: Man landet auf der Produktseite.

---

## Negative Tests

TC-N01: Falsches Passwort  
Schritte: standard_user eingeben, falsches Passwort eingeben, Login klicken.  
Erwartet: Fehlermeldung "Benutzername und Passwort stimmen nicht überein"

TC-N02: Falscher Benutzername  
Schritte: falschen Benutzername eingeben, secret_sauce als Passwort, Login klicken.  
Erwartet: Gleiche Fehlermeldung wie oben.

---

## Grenzfälle (Edge Cases)

TC-E01: Benutzername leer  
Schritte: Benutzername leer lassen, Passwort eingeben, Login klicken.  
Erwartet: "Benutzername ist erforderlich"

TC-E02: Passwort leer  
Schritte: Benutzername eingeben, Passwort leer lassen, Login klicken.  
Erwartet: "Passwort ist erforderlich"

TC-E03: Beide Felder leer  
Schritte: Beide Felder leer lassen, Login klicken.  
Erwartet: "Benutzername ist erforderlich"

TC-E04: Gesperrter Benutzer  
Schritte: locked_out_user / secret_sauce eingeben, Login klicken.  
Erwartet: "Dieser Benutzer wurde gesperrt"
