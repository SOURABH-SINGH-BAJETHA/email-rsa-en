# 🔐 RSA Email Encryption System

A secure web-based RSA encryption and decryption system built using **Flask** and **Python**. This project allows users to **encrypt messages using RSA**, send them via email, and securely **decrypt** them using their uploaded private key from **any device**.

---

## 🚀 Features

- 🔑 RSA Key Generation (2048-bit)
- ✉️ Send Encrypted Messages via Gmail
- 🔐 Password-Protected Private Key Storage
- 🧩 Base64 Encoded Output for Easy Sharing
- 🌐 Clean Flask Web Interface (Bootstrap Styled)
- 💻 Cross-Device Decryption Support

---

## 📂 Project Structure

rsa_email_project/
│
├── app.py # Flask app: routes for encrypt/decrypt/email
├── generate_keys.py # Generates RSA public/private key pair
├── key_utils.py # Handles private key encryption/decryption with password
├── templates/ # HTML templates for frontend (Bootstrap styled)
│ ├── index.html
│ ├── encrypt.html
│ ├── decrypt.html
│ ├── upload_key.html
│ └── login.html (if using auth)
├── static/
│ └── style.css # Custom classical styles
├── keys/ # Stores public.pem and private.pem (locally)
│ ├── public.pem
│ └── private.pem
├── models.py # SQLAlchemy User model
└── README.md # You're here!
