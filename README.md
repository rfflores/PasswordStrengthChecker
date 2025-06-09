# PasswordStrengthEvaluator

This project is a simple and educational implementation of a password strength evaluation tool, based on the heuristic scoring model developed by the *University of Illinois at Chicago* in the [UIC Strong Password Test](https://www.uic.edu/apps/strong-password-test/).

## 📌 Description

The algorithm does not attempt to estimate how long it would take to crack a password. Instead, it evaluates password strength by applying **additions** and **deductions** based on common password composition rules and identifiable patterns.

### ✅ Scoring – Additions

The password gains points for:

- Total number of characters
- Use of uppercase and lowercase letters
- Inclusion of numbers and symbols
- Placement of numbers/symbols (middle of the password is more valuable)
- Meeting multiple complexity requirements (character diversity and length)

### ❌ Scoring – Deductions

The password loses points for:

- Using only letters or only numbers
- Repeating characters
- Having consecutive characters of the same type (e.g., multiple uppercase letters in a row)
- Containing common sequences (e.g., "abc", "123", or symbol patterns)

The intention is to discourage the use of predictable structures—even in long passwords—and promote strong password practices.

## 🔍 Purpose

This implementation is intended for academic, testing, and research purposes. It was created as part of a university project focused on password strength analysis.

## 🧠 Reference

Algorithm adapted from the *UIC Strong Password Test*, developed by the University of Illinois at Chicago.  
Link: [https://www.uic.edu/apps/strong-password-test/](https://www.uic.edu/apps/strong-password-test/)

## 🛠️ Technologies

- Python 3.x
- pandas
- matplotlib (for optional visualizations)

## 📄 License

This project is released for educational use only and is n
