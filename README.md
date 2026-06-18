# Web Security

A collection of hands-on web security projects focused on identifying, exploiting, and mitigating common web application vulnerabilities.

## Overview

This repository documents a series of practical security workshops covering offensive and defensive techniques used in modern web applications. Each workshop demonstrates how a vulnerability can be exploited, why it exists, how it can be fixed, and how the risk should be assessed from a security perspective.

The project focuses on both attack methodology and secure coding practices, emphasizing defense-in-depth rather than relying on a single security control.

## Topics Covered

### SQL Injection

Investigation of insecure database queries that allow attackers to manipulate SQL statements and gain unauthorized access to data.

**Key concepts:**
- Authentication bypass
- Data extraction
- Parameterized queries
- Input validation
- Principle of least privilege

### Cross-Site Scripting (XSS)

Analysis of client-side code injection attacks that allow malicious JavaScript to execute within a victim’s browser.

**Key concepts:**
- Reflected XSS
- Stored XSS
- Output encoding
- Content Security Policy (CSP)
- Input sanitization

### Path Traversal

Exploitation of file system access vulnerabilities that allow attackers to access resources outside intended directories.

**Key concepts:**
- Directory traversal
- Arbitrary file disclosure
- Path validation
- File access restrictions
- Secure file handling

### Man-in-the-Middle (MITM) & Monkey Patching

Examination of attacks that manipulate communication or application behavior by intercepting or altering trusted processes.

**Key concepts:**
- Traffic interception
- Trust boundaries
- Runtime manipulation
- Secure communication
- Certificate validation

## Methodology

Each workshop follows this workflow:

1. Identify the vulnerability  
2. Exploit the weakness in a controlled environment  
3. Analyze why the attack succeeds  
4. Implement defensive measures  
5. Verify mitigation  
6. Assess remaining risk using OWASP Risk Rating principles  

## Skills Demonstrated

- Web Application Security
- Secure Coding Practices
- OWASP Top 10
- Threat Modeling
- Risk Assessment
- Vulnerability Analysis
- Defensive Security
- Security Testing
- Attack Surface Analysis
