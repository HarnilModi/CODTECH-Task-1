**Name:** HARNIL MODI

**Company:** CODTECH IT SOLUTIONS

**ID:** CT08DAN

**Domain:** Cyber Security & Ethical Hacking

**Duration:** December to January 2025

**Mentor:** Neela Santhosh Kumar



## **Overview of the Project :-** 


### Project :- Password strength checker.

### Objective:-

The Password Strength Checker is a tool designed to help users assess the strength and security of their passwords. It evaluates the entered password based on various factors such as length, complexity, entropy, and whether the password has been exposed in previous data breaches. The tool provides actionable feedback to help users create strong and secure passwords.

## **Key Features :-**

1. Password Length Check: Ensures the password meets a minimum length requirement of 12 characters.

2. Common Password Detection: Identifies passwords that are commonly used or guessable (e.g., "123456", "password").

3. Character Complexity Analysis:
Checks for the presence of uppercase and lowercase letters, numbers, and special characters.
Provides feedback on missing character types.

4. Entropy Calculation:
Estimates the password's predictability using entropy calculations.
Categorizes entropy levels as weak, moderate, or strong.

5. Data Breach Check:
Uses the **Have I Been Pwned** API to determine if the password has appeared in known data breaches.
Returns the number of times the password has been breached, if applicable.

6. Feedback System:
Provides clear and actionable feedback based on the password's evaluation.
Rates the overall password strength as weak, moderate, or strong.

7. Score System: Assigns a score out of 10 based on the password's strength.

## **Technologies Used**

## Programming Language: Python

**Libraries:**

1. re: For regular expressions to validate character types.

2. hashlib: For SHA-1 hashing used in breach detection.

3. requests: For interacting with the Have I Been Pwned API.

**External Service:**

Have I Been Pwned API: To check if a password has been exposed in data breaches.

## How It Works

1. Input: The user enters a password.

2. Analysis: The tool evaluates the password based on:

-Length

-Use of uppercase, lowercase, numbers, and special characters

-Common password patterns

-Entropy calculation

-Data breach status

3. Output: Feedback and a strength score are displayed to guide the user in improving their password security.9)

![image alt](https://github.com/user-attachments/assets/004669bf-63f8-4819-b71b-f219094777c5)

