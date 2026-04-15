# DecodeLabs-Internship
repsoitory for task 1
#  Password Strength Checker

A Python-based tool that evaluates password security based on multiple criteria and provides actionable feedback to help users create stronger passwords.

## Features

-  Checks password against common security requirements:
  - Minimum 8 characters
  - At least 1 number
  - At least 1 uppercase letter
  - At least 1 lowercase letter
  - At least 1 special character (!@#$% etc.)
-  Detects commonly used weak passwords (e.g., `password123`, `qwerty`)
   Classifies passwords as **STRONG**, **MEDIUM**, or **WEAK**
-  Provides detailed improvement tips for weak/medium passwords
-  Highlights what the user did well (even for weak passwords)
-  Interactive loop to check multiple passwords
-  Option to exit anytime by typing `quit`

 How It Works

1. User enters a password.
2. The program checks:
   - Length
   - Presence of numbers, uppercase, lowercase, and special characters
   - Whether the password is on a list of common weak passwords
3. Based on the criteria, it assigns a strength level and gives specific feedback.

 - screenshot
<img width="558" height="504" alt="WhatsApp Image 2026-04-05 at 3 41 47 PM" src="https://github.com/user-attachments/assets/51d03968-0968-480d-b4bc-12b2a6277f97" />
