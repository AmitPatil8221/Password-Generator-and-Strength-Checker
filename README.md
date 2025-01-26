# Password-Generator-and-Strength-Checker

## Overview

This project provides a Java-based **Password Generator and Strength Checker**. The application enables users to:

1. **Generate Secure Passwords**: Generate passwords with customizable parameters (length, character types, etc.).
2. **Evaluate Password Strength**: Check the robustness of passwords based on length and character diversity.
3. **Access Useful Password Guidelines**: Learn best practices for creating secure passwords.

## Features

- **Password Generator**:
  - Supports uppercase letters, lowercase letters, numbers, and special characters.
  - Customizable length and character inclusion.
- **Password Strength Checker**:
  - Evaluates password strength using multiple criteria, such as length and character variety.
  - Provides feedback ranging from "very good" to "weak".
- **Useful Information**:
  - Guidelines on how to create strong passwords.
  - Tips for avoiding common password pitfalls.

## Usage

### Menu Options
- `Enter 1`: Password Generator
- `Enter 2`: Password Strength Check
- `Enter 3`: Useful Information
- `Enter 4`: Quit

### How to Run
1. Clone the repository.
2. Compile the Java files:
   ```bash
   javac PasswordGenerator/*.java
   ```
3. Run the main program:
   ```bash
   java PasswordGenerator.Main
   ```

### Example Interaction
- **Password Generation**: Users specify desired password length and types of characters to include.
- **Strength Check**: Enter any password to receive feedback on its strength.
- **Useful Tips**: Learn essential strategies for maintaining strong and secure passwords.

## Code Structure

- **`Alphabet.java`**: Defines character sets (uppercase, lowercase, numbers, symbols) used for password generation.
- **`Generator.java`**: Handles menu operations and implements the password generation and strength-checking logic.
- **`Main.java`**: Entry point of the application.
- **`Password.java`**: Provides logic for assessing password strength.

## Password Best Practices
- Use a minimum of **8 characters**.
- Include **uppercase letters**, **lowercase letters**, **numbers**, and **symbols**.
- Avoid using:
  - Repeated characters.
  - Common patterns or dictionary words.
  - Personal or easily guessable information.
- Ensure passwords are **unique** for every account or system.

---

Feel free to share any additional details you'd like included!
