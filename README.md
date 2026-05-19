# Mini-Encryption-Package
CryptoTools is a Python mini encryption package that demonstrates Caesar Cipher, Reverse Cipher, and Binary Encoding techniques. The project helps in understanding Python modules, packages, functions, and installable packages using pip. It allows users to encrypt, decrypt, encode, and decode text easily.
# 🔐 CryptoTools – Mini Encryption Package

## 🌟 Overview

CryptoTools is a Python-based mini encryption package developed to demonstrate basic cryptography and encoding techniques. This project helps in understanding Python modules, packages, functions, and installable packages using `pip install .`.

The package allows users to:

* 🔒 Encrypt text
* 🔓 Decrypt text
* 💻 Encode text into binary
* 📄 Decode binary back into text

---

# ✨ Features

✅ Caesar Cipher Encryption & Decryption
✅ Reverse Cipher Encryption & Decryption
✅ Binary Encoding & Decoding
✅ Beginner-Friendly Python Project
✅ Installable Package using `setup.py`
✅ Simple and Clean Code Structure

---

# 🛠️ Technologies Used

* 🐍 Python
* 📦 setuptools
* 🌐 Git & GitHub

---

# 📂 Modules Included

## 🔑 1. Caesar Cipher (`caesar.py`)

Encrypts text by shifting letters in the alphabet using a shift value.

### Example:

```text id="0n7z0k"
HELLO → KHOOR
```

---

## 🔄 2. Reverse Cipher (`reversecipher.py`)

Encrypts text by reversing the string.

### Example:

```text id="4y4ivd"
HELLO → OLLEH
```

---

## 💻 3. Binary Encoding (`binaryencode.py`)

Converts text into binary format and restores it back to readable text.

### Example:

```text id="c3d1zf"
HELLO → 01001000 01000101 01001100 01001100 01001111
```

---

# 📁 Project Structure

```text id="jz9mql"
cryptotools_project/
│
├── cryptotools/
│   ├── __init__.py
│   ├── caesar.py
│   ├── reversecipher.py
│   └── binaryencode.py
│
├── setup.py
├── README.md
└── test_package.py
```

---

# ⚙️ Installation

```bash id="ic6yqt"
pip install .
```

---

# 🚀 Example Usage

```python id="8n3cgf"
from cryptotools.caesar import encrypt

encrypted = encrypt("HELLO", 3)
print(encrypted)
```

### 📌 Output

```text id="h1g7rx"
KHOOR
```

---

# 🎯 Objective of the Project

This project was created to learn:

* 📦 Python Packages
* 🧩 Python Modules
* 🛠️ Function Implementation
* 📥 Package Installation using `setup.py`
* 🔗 Importing Modules in Python

---

# 📚 Learning Outcomes

✔️ Understanding package structure
✔️ Working with multiple Python modules
✔️ Creating reusable functions
✔️ Using GitHub for project hosting
✔️ Building installable Python packages

---

# 🏁 Conclusion

CryptoTools is a simple yet effective educational project that demonstrates basic encryption and encoding techniques using Python. It provides hands-on experience in developing modular and installable Python packages while improving programming and problem-solving skills. 🔐✨
