# Scratch-password-validation-exercise
# Password Validation — Scratch Project

## 1. Project Overview

This Scratch project is a simple **password validation exercise**. It asks the user to enter a password and checks two requirements:

1. The **first character** is a lowercase letter (`a–z`).
2. The **last character** is one of these symbols: `! @ # $ % & *`

The program then displays whether each requirement is satisfied.

### Example

For:

```text
apple!
```

The program identifies:

* `a` → lowercase letter ✅
* `!` → valid symbol ✅

---

## 2. Project Goal

The goal is to practice **string and character validation** in Scratch.

The project demonstrates:

* User input
* Variables
* Strings and individual characters
* Conditions (`if / else`)
* Comparisons (`<`, `>`)
* Logical operators (`OR`)
* Lists
* String length
* List membership checking

> **Note:** This is an educational exercise, not a complete or secure password-validation system.

---

## 3. How It Works

When the **Green Flag** is clicked:

1. The program asks the user to enter a password.
2. The first character is checked to see if it is between `a` and `z`.
3. A list called `symbols` is created containing:
   `! @ # $ % & *`
4. The program finds the last character using the password's length.
5. It checks whether the last character exists in the `symbols` list.
6. The results are displayed to the user.

### Simplified Logic

```text
Ask for password
↓
Store answer in userPassWord
↓
Check first character (a–z)
↓
Create symbols list
↓
Check last character
↓
Display results
```

---

## 4. Variables and List

### Variable

| Name           | Purpose                                 |
| -------------- | --------------------------------------- |
| `userPassWord` | Stores the password entered by the user |

### List

| Name      | Contents        |
| --------- | --------------- |
| `symbols` | `! @ # $ % & *` |

---

## 5. Main Validation Rules

### First Character

The program checks whether the first character is a lowercase letter:

```text
a–z
```

Examples:

```text
apple → valid
banana → valid
@hello → invalid
123abc → invalid
```

Uppercase letters (`A–Z`) are **not** accepted by this check.

### Last Character

The program checks whether the last character is one of:

```text
! @ # $ % & *
```

Examples:

```text
hello! → valid
password@ → valid
hello1 → invalid
password → invalid
```

---

## 6. Controls

| Action        | Result                      |
| ------------- | --------------------------- |
| 🟢 Green Flag | Starts the program          |
| User Input    | Enter a password when asked |

There are no movement, levels, or game controls.

---

## 7. Project Contents

The `.sb3` file contains:

* 1 Stage
* 1 Sprite (`الكائن 1`)
* 1 Variable
* 1 List
* 2 Costumes
* 2 Sounds
* 3 SVG assets
* 26 Scratch blocks
* No extensions
* No custom blocks
* No broadcasts

The costumes and sounds are stored in the project but are not required for the main password-validation logic.

---

## 8. Limitations

The project only checks the first and last characters. It does **not** check:

* Minimum password length
* Uppercase letters
* Numbers
* Overall password strength
* Common or weak passwords
* Complete password security

Therefore, it should be considered a **basic programming exercise** rather than a real security system.

---

## 9. How to Run

1. Open the `.sb3` file in Scratch.
2. Click the **Green Flag**.
3. Enter a password when prompted.
4. The program will display the results of the two checks.

---

## 10. Technical Summary

| Feature         | Details |
| --------------- | ------- |
| Platform        | Scratch |
| Format          | `.sb3`  |
| Scratch Version | 3.29.1  |
| Stages          | 1       |
| Sprites         | 1       |
| Variables       | 1       |
| Lists           | 1       |
| Costumes        | 2       |
| Sounds          | 2       |
| Blocks          | 26      |
| Extensions      | None    |
| Custom Blocks   | None    |
| Broadcasts      | None    |

## Conclusion

This project demonstrates basic **text processing and input validation** in Scratch by checking whether a password starts with a lowercase letter and ends with a predefined symbol.
