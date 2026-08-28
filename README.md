# NetworkWalks-B082-Week3

## Week 3 – Password Cracking Labs

This repository documents my Week 3 practical cybersecurity work for the **NetworkWalks Cybersecurity & Ethical Hacking Internship – Batch B082**.

The week focused on password auditing and recovery in a controlled training environment using a password-protected PDF supplied for the lab.

## Project Modules

### W3-PM1 – Password Cracking with JTR

Used **John the Ripper (JTR)** and the **Johnny GUI** to extract/process the PDF password hash, perform the password-cracking task, recover the training password, and verify the result by opening the protected PDF.

Evidence: `W3-PM1-JTR/screenshots/`

### W3-PM2 – Password Cracking with NetworkWalks Tools

Used the **NetworkWalks Hash Calculator** to obtain the PDF hash and the **NetworkWalks Password Cracker** to perform a dictionary-based password attack. The recovered password was then used to open the protected PDF and verify successful completion.

Evidence: `W3-PM2-NetworkWalks/screenshots/`

## Learning Objectives

- Understand the relationship between password protection and hashing.
- Extract a password hash from a protected PDF in an authorized lab.
- Use John the Ripper and Johnny for password auditing.
- Use browser-based password-auditing tools.
- Understand dictionary-based password attacks.
- Verify recovered credentials by opening the authorized training file.
- Recognize why weak/common passwords present a security risk.

## Key Takeaways

- Password-protected files may contain password-derived hash data that can be analyzed during authorized security testing.
- Dictionary attacks can be effective against weak or commonly used passwords.
- Strong, unique passwords improve resistance to password-cracking attempts.
- Security testing must always be performed with explicit authorization and within a controlled environment.

## Security & Privacy Notice

This repository contains **sanitized evidence for portfolio and assessment sharing**.

Sensitive hash values and recovered password values visible in the original screenshots have been intentionally redacted from the public evidence. The original unredacted evidence should be retained privately and provided only through an authorized submission channel when required.

No real user accounts, credentials, or unauthorized systems were targeted as part of this documented work.

## Ethical Use

All activities documented in this repository were performed using the authorized NetworkWalks training material and within the intended educational environment. Password-cracking techniques must not be applied to systems, accounts, files, or data without permission.

## Repository Structure

```text
NetworkWalks-B082-Week3/
│
├── W3-PM1-JTR/
│   ├── screenshots/
│   │   ├── PM1-01-Hash-Extraction-REDACTED.png
│   │   ├── PM1-02-Johnny-Password-File-REDACTED.png
│   │   ├── PM1-03-PDF-Password-Prompt.png
│   │   └── PM1-04-Lab-Flag.png
│   └── README.md
│
├── W3-PM2-NetworkWalks/
│   ├── screenshots/
│   │   ├── PM2-01-NetworkWalks-Lab.png
│   │   ├── PM2-02-Hash-Calculator.png
│   │   ├── PM2-03-PDF-Hash-REDACTED.png
│   │   ├── PM2-04-Password-Cracker.png
│   │   ├── PM2-05-Password-Recovered-REDACTED.png
│   │   ├── PM2-06-PDF-Password-Prompt-REDACTED.png
│   │   └── PM2-07-Lab-Flag.png
│   └── README.md
│
├── .gitignore
└── README.md
```

## LinkedIn Project Update

LinkedIn post: **To be added after publication**

## Author

**Antoinette Thompson**  
Cybersecurity Student | NetworkWalks Cybersecurity & Ethical Hacking Internship – Batch B082

## Disclaimer

This repository is intended for educational, portfolio, and authorized cybersecurity training purposes only. The techniques demonstrated must only be used against systems and files for which permission has been granted.
