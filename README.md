# Password Strength Checker

A beginner Python project that checks how strong a password is — pure Python, no libraries.

## Features

- Password length
- Uppercase letters
- Lowercase letters
- Numbers
- Special characters

Classifies the password as:

- Very Weak
- Weak
- Medium
- Strong
- Very Strong

## File Structure

```
Password-Strength-Checker/
│
├── Password_Strength_Checker.ipynb
│
├── README.md
│
└── auto_push.bat
```

## How to Run

1. Open `Password_Strength_Checker.ipynb` in Jupyter Notebook or JupyterLab.
2. Run all cells (`Kernel` -> `Restart & Run All`).
3. Enter a password when prompted.
4. Read the analysis report.

> Tip: the last **"Try it with sample data"** cell runs several example passwords without typing anything.

## Example Output

```
========== PASSWORD ANALYZER ==========

Password Length       : 15
Uppercase Letters     : ✓
Lowercase Letters     : ✓
Numbers               : ✓
Special Characters    : ✓

Strength              : VERY STRONG

========================================
```

### Optional challenge — password score

Each rule earns points, summed into a score out of 11:

| Rule | Points |
|------|--------|
| Length >= 12 | 3 |
| Length >= 8 | 2 |
| Length >= 5 | 1 |
| Uppercase letters | 2 |
| Lowercase letters | 2 |
| Numbers | 2 |
| Special characters | 2 |

| Score | Strength |
|-------|----------|
| 0–2 | Very Weak |
| 3–4 | Weak |
| 5–6 | Medium |
| 7–8 | Strong |
| 9+ | Very Strong |

## What You Learn

```
input()
   ↓
strings
   ↓
for loops
   ↓
if / elif / else
   ↓
string methods (.isupper(), .islower(), .isdigit(), .isalnum())
   ↓
functions
   ↓
Boolean logic
```

Scoring introduces **rule-based classification** — a useful stepping stone before machine learning.