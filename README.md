# Password Strength Checker

A simple program that evaluates the strength of a password based on length and character variety.
It helps users understand whether their password is weak, medium, or strong — and gives suggestions for improving it.

---

## 🔍 Features

* Checks for uppercase, lowercase, digits, and special characters.
* Evaluates password length and diversity.
* Provides feedback on how to make passwords stronger.
* Simple and lightweight — ideal for learning basic programming and security awareness.

---

## 🧠 Learning Objectives

This project helps beginners:

* Practice string handling and logic building.
* Understand how password strength is evaluated.
* Learn basic input/output and conditional statements.
* Begin thinking about password security from a cybersecurity perspective.

---

## ⚙️ How to Run

### 🖥️ For C Version

1. Save your code as `password_checker.c`.
2. Compile and run:

   ```bash
   gcc password_checker.c -o password_checker
   ./password_checker
   ```
3. Enter a password when prompted to see the strength evaluation.

### 🐍 For Python Version

1. Save your code as `password_checker.py`.
2. Run using:

   ```bash
   python3 password_checker.py
   ```
3. Type a password to get the analysis result.

---

## 🧩 Example Output

```
Enter password: P@ssw0rd123
Length: 11
Character types: 4/4
Password strength: STRONG
Suggestion: Good job! Your password looks secure.
```

---

## 🚀 Future Improvements

* Add a scoring system (0–100 scale).
* Check for common weak passwords using a wordlist.
* Implement SHA hashing to show how passwords should be stored securely.

---

## 🛡️ Ethical Note

This tool is for **educational purposes only**.
It does not store or transmit passwords — always test with sample passwords, not your real ones.

---

## 📄 License

This project is open-source and free to use for learning and personal development.
