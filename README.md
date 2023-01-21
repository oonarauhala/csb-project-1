# Vulnerable web app project
This is a course work project for Cyber Security Base Project I. The asignment is to create a web application with at least five different security flaws (from [the OWASP top ten list 2017 OR 2021](https://owasp.org/www-project-top-ten/]), document the flaws and instuctions on how to fix them. This app is written in the course recommended landuage Python and Django.

## Planned security flaws
Note: CSRF is missing from both lists as it is more rare nowadays due to the more secure frameworks. However, due to its fundamental nature it is allowed as a flaw.
- Boken access control
    - Access to resoucres without login by url parameters
- Cryptographic failures
    - Sending and storing plaintext passwords
- Injection
    - SQL injection possible
- Security misconfiguration
    - CSRF module disabled
- Identification and authentication failures
    - Brute force attacks possible
    - Permits weak passwords
- (Security logging and monitoring failures)
    - No logs of logins, failed logins