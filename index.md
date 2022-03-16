## 1. Broken Access Control

Access control enforces policy such that users cannot act outside of their intended permissions. Failures typically lead to unauthorized information disclosure, modification, or destruction of all data or performing a business function outside the user's limits.

### Broken Access Control

### Directory Traversal

### CSRF

## 2. Cryptographic Failures

Many web applications and APIs do not properly protect sensitive data with strong encryption. Attackers may steal or modify such weakly protected data to conduct credit card fraud, identity theft, or other crimes. Sensitive data must be encryption at rest and in transit, using a modern (and correctly configured) encryption algorithm.

### Unencrypted Communication

## 3. Injection

Injection flaws, such as SQL, NoSQL, OS, and LDAP injection, occur when untrusted data is sent to an interpreter as part of a command or query. The attacker’s hostile data can trick the interpreter into executing unintended commands or accessing data without proper authorization.

### SQL Injection

### Command Execution

## 4. Insecure Design

Pre-coding activities are critical for the design of secure software. The design phase of you development lifecycle should gather security requirements and model threats, and development time should be budgeted to allow for these requirements to be met. As software changes, your team should test assumptions and conditions for expected and failure flows, ensuring they are still accurate and desirable. Failure to do so will let slip critical information to attackers, and fail to anticipate novel attack vectors.

### Insecure Design

### Information Leakage

### File Upload
