# Intentionally-Vulnerable-Python-Application
This repository contains a deliberately vulnerable Python web application designed for testing purposes. The application includes several security flaws that can be detected by security tools such as Software Composition Analysis (SCA), Static Application Security Testing (SAST), and Dynamic Application Security Testing (DAST).


Key Vulnerabilities:
Command Injection: User input is passed directly to a system command without validation.
Hardcoded Credentials: Insecure storage of credentials within the source code.
Insecure Deserialization: Use of Python's pickle module, which can lead to arbitrary code execution.
Outdated Libraries: The application relies on an outdated version of the requests library, which may have known vulnerabilities.
SQL Injection: User input is used to build SQL queries without proper sanitization.
Purpose:
This repository is intended for use in security training, vulnerability scanning, and testing tools like DefectDojo. It provides a safe environment to understand how different security vulnerabilities can be identified and exploited.


