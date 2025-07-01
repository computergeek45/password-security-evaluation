# Task 6: Create a Strong Password and Evaluate Its Strength

## Task Overview

This task is part of the **Cyber Security Internship** program. The objective is to understand password security, explore what makes a password strong, and test password strength using online tools.

---

## Objective

- Create strong and weak passwords with varying complexity.
- Test them using online password strength checkers.
- Analyze the results and identify password best practices.
- Learn about common password attacks and how complexity helps prevent them.

---

## Password Tested

**Password:** `HeL!o_2025@Ai`  
**Length:** 13 characters  
**Components:**
- Uppercase letters ✅
- Lowercase letters ✅
- Numbers ✅
- Special symbols ✅

---

## Password Strength Test Results

| Tool                         | Result/Rating     | Estimated Time to Crack | Feedback                                                                 |
|------------------------------|-------------------|---------------------------|--------------------------------------------------------------------------|
| **PasswordMeter.com**        | 100% (Very Strong) | Not displayed             | Excellent use of uppercase, lowercase, numbers, symbols, and length.     |
| **HowSecureIsMyPassword.net**| Very Strong        | 2 million years           | Extremely difficult to brute-force.                                      |
| **Kaspersky Password Checker**| Strong             | Not shown                 | Safe and not leaked; flagged length as slightly short. Recommended 15+.  |

---

## Screenshots

All screenshots of the above test results are available in the `/screenshots` folder:
- `passwordmeter_result.png`
- `howsecure_result.png`
- `kaspersky_result.png`

---

## Tips & Best Practices for Creating Strong Passwords

- Use **12–16+ characters** minimum.
- Mix **uppercase**, **lowercase**, **numbers**, and **symbols**.
- Avoid common dictionary words and personal info.
- Use **passphrases** for both memorability and strength (e.g., `MyDog$eatsRice99!`).
- Don’t reuse passwords across platforms.
- Use **password managers** to store and generate secure passwords.

---

## Common Password Attacks

| Attack Type         | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Brute Force**     | Tries all possible character combinations until it cracks the password.     |
| **Dictionary Attack**| Uses a list of common words and combinations to guess passwords.           |
| **Credential Stuffing** | Tries leaked username-password pairs across websites.                    |

---

## 📁 Files in This Repository

Password-Security-Evaluation/
├── README.md
└── screenshots/
├── passwordmeter_result.png
├── howsecure_result.png
└── kaspersky_result.png
