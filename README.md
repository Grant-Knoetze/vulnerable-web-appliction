# vulnerable-web-appliction
A vulnerable web app to practice web app penetration testing that can be used for technical interviews for penetration testers.
Included Vulnerabilities:
1.	SQL Injection (SQLi)
2.	Cross-Site Scripting (XSS)
3.	Broken Authentication
4.	Insecure Direct Object References (IDOR)
5.	Security Misconfiguration
How to Exploit the Vulnerabilities
1.	SQL Injection (SQLi)
o	Try entering admin' -- as the username and see if it bypasses authentication.
2.	Cross-Site Scripting (XSS)
o	Post a comment like <script>alert('Hacked!')</script> and see if it executes.
3.	Broken Authentication
o	Hardcoded credentials (admin / password) make it easy to guess.
4.	Insecure Direct Object References (IDOR)
o	If an admin panel exists at /admin, there’s no access control.
5.	Security Misconfiguration
o	Missing proper input validation and no security headers.

