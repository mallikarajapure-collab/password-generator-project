<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:064E3B,50:059669,100:34D399&height=210&section=header&text=PASSWORD%20GENERATOR&fontSize=40&fontColor=FFFFFF&fontAlignY=38&desc=Random%20Character-Based%20Passwords&descAlignY=60&descSize=14" width="100%" alt="Emerald green header" />

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Random%20%2B%20String-059669?style=for-the-badge" alt="Python standard library" />

</div>

---

## 🔑 Overview

A beginner-friendly Python CLI script that creates a password from a pool of uppercase letters, lowercase letters, digits, and punctuation characters.

## ✨ Features

- Prompts for a desired password length.
- Builds a character pool with Python's `string` module.
- Selects characters with `random.choice()`.
- Prints the generated password.

## 🧰 Tech Stack

- Python
- Built-in `random` and `string` modules

## 🚀 Run Locally

The source file is named `password generator,py.py` (including the comma).

```bash
python "password generator,py.py"
```

Enter a positive length when prompted.

## 🔄 How It Works

1. Read the requested length.
2. Combine letters, digits, and punctuation into one character pool.
3. Select one random character per position.
4. Print the generated string.

## ⚠️ Security Note

This is a learning project and uses Python's non-cryptographic `random` module. For passwords protecting real accounts, prefer a trusted password manager or a cryptographically secure generator such as Python's `secrets` module. Do not commit generated passwords to GitHub.

---

<div align="center"><sub>Python fundamentals • Strings • Loops • Random selection</sub></div>