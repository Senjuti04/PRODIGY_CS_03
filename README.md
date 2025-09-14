# 🔐 Password Strength Checker

A simple yet effective tool to **evaluate the strength of passwords based on multiple criteria**.
This is perfect for security-focused projects or for personal use to encourage strong password habits.

---

## ✨ Features

- ✅ Checks password strength based on:

- 📏 Length ≥ 8 characters

- 🔡 Lowercase letters

- 🔠 Uppercase letters

- 🔢 Numbers

- 🔣 Special characters (@, $, !, %, *, ?, &, #)

- ✅ Provides feedback on:

- Overall strength rating: 🔴 Very Weak → 🟢 Very Strong

- Which specific criteria passed ✅ or failed ❌

---

## 🛠️ How It Works

The script evaluates each password against the above rules and prints:

Strength Level: Very Weak 🚫, Weak ❌, Moderate ⚠️, Strong ✅, Very Strong 💪

Detailed Breakdown: Pass/fail for each requirement

---

## 🚀 Usage

**Run the script in your terminal:**
```bash
python password_strength_checker.py
```

**💻 Example Output:**
```
Enter a password to check its strength: P@ssw0rd123

Password Strength: Strong ✅

Criteria:
 - 📏 Length >= 8: ✔
 - 🔡 Contains lowercase: ✔
 - 🔠 Contains uppercase: ✔
 - 🔢 Contains number: ✔
 - 🔣 Contains special character: ✔
```

---

## 📌 Notes

Use this to encourage strong passwords in any project.

Can be integrated with login/signup forms or used as a standalone CLI tool.
