# NetworkWalks-B082-Week3

# Week 3 – Password Cracking Labs

## NetworkWalks Cybersecurity & Ethical Hacking Internship

**Intern:** Antoinette Thompson  
**Batch:** B082  
**Week:** 3

---

## Overview

Week 3 focused on password cracking techniques using a controlled,
authorized training PDF supplied as part of the NetworkWalks
Cybersecurity & Ethical Hacking internship.

The exercises demonstrated how a password-protected PDF can be
processed to extract its password hash and how password-cracking
tools can be used to recover a weak password in a controlled
laboratory environment.

Two approaches were completed:

1. Password Cracking with John the Ripper (JTR)
2. Password Cracking with NetworkWalks Tools

---

## Learning Objectives

- Understand the relationship between password protection and hashing.
- Extract a password hash from a protected PDF.
- Use John the Ripper and Johnny for password recovery.
- Use NetworkWalks Hash Calculator to extract a PDF hash.
- Use the NetworkWalks Password Cracker to perform a dictionary attack.
- Verify that the recovered password successfully unlocks the PDF.
- Understand the security risks associated with weak passwords.

---

# Project Module 1 – Password Cracking with JTR

## Objective

Recover the password of the provided `My Locked PDF1.pdf` using
John the Ripper (JTR) and the Johnny graphical interface.

## Tools Used

- John the Ripper
- Johnny GUI
- PDF Hash Extractor
- Protected training PDF
- Windows environment

## Methodology

1. Obtained the authorized training PDF.
2. Extracted the PDF password hash.
3. Saved the extracted hash in a text file named `hash1.txt`.
4. Loaded the hash file into Johnny.
5. Started the password-cracking attack.
6. Retrieved the recovered password.
7. Used the recovered password to open the protected PDF.
8. Verified successful access to the lab flag.

## Evidence

Screenshots documenting the process are available in:

`W3-PM1-JTR/screenshots/`

### Result

The password was successfully recovered using the JTR/Johnny
workflow, and the protected PDF was successfully opened.

---

# Project Module 2 – Password Cracking with NetworkWalks Tools

## Objective

Recover the password of the provided `My Locked PDF1.pdf` using the
NetworkWalks Hash Calculator and Password Cracker.

## Tools Used

- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Web browser
- Protected training PDF

## Methodology

1. Accessed the NetworkWalks password-cracking laboratory.
2. Uploaded the authorized training PDF to the Hash Calculator.
3. Extracted the PDF password hash.
4. Submitted the hash to the NetworkWalks Password Cracker.
5. Started the dictionary-based password attack.
6. Waited for the tool to identify a matching password.
7. Used the recovered password to open the protected PDF.
8. Verified successful completion of the lab.

## Evidence

Screenshots documenting the process are available in:

`W3-PM2-NetworkWalks/screenshots/`

### Result

The password was successfully recovered using the NetworkWalks
Password Cracker, and the protected PDF was successfully opened.

---

# Security Observations

The exercises demonstrated that weak and commonly used passwords
can be recovered through dictionary-based password attacks.

The labs also demonstrated the importance of protecting passwords
hashes and using strong, unique passwords.

A password should not be considered secure simply because a file is
password protected. The strength and complexity of the password are
important factors in determining resistance to password-cracking
attempts.

---

# Ethical Considerations

These exercises were performed strictly within the authorized
NetworkWalks training environment using the provided laboratory
file.

Password-cracking techniques should only be performed against
systems, files, accounts, or data for which explicit authorization
has been granted.

---

# Key Takeaways

- Password hashes can be extracted from certain protected files.
- Dictionary attacks can quickly identify weak/common passwords.
- John the Ripper provides a powerful password-auditing framework.
- Johnny provides a graphical interface for John the Ripper.
- Browser-based tools can simplify the password-cracking workflow.
- Strong, unique passwords significantly improve resistance to
  dictionary attacks.
- Authorization and ethical boundaries are essential when performing
  security testing.

---

## Disclaimer

This repository contains cybersecurity training exercises completed
for educational and authorized ethical-hacking purposes.

All activities documented here were performed in a controlled lab
environment using intentionally provided training materials.

No unauthorized systems, accounts, files, or networks were targeted.

---

## Author

**Antoinette Thompson**

Cybersecurity Student | NetworkWalks Cybersecurity & Ethical Hacking
Internship – Batch B082
