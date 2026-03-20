# 🔐 Password Generator
> A secure, client-side utility **made** to generate cryptographically strong credentials with total privacy.

---

## ⚡ Key Features

| Feature | Description |
| :--- | :--- |
| **Dual Modes** | Effortlessly switch between high-entropy **Random** strings and memorable **Passphrases**. |
| **Web Crypto API** | Built on cryptographically strong random number generation for maximum security. |
| **Precision Control** | Fine-tune your security with exact counts for uppercase, lowercase, numbers, and symbols. |
| **Visual Strength** | Real-time entropy feedback via a multi-segment, color-coded strength meter. |
| **Session History** | A localized list of the last 50 **made** passwords for quick reference during your session. |

---

## ⚙️ How It Works

### 🛡️ Secure Entropy
The application leverages the `Web Crypto API` (specifically `crypto.getRandomValues`) to generate 32-bit unsigned integers. These values are then mapped to your selected character pools to ensure the output is entirely non-deterministic.

### 🧠 Smart Logic
* **Validation**: The generator automatically validates that your specific character requirements fit within the total length selected.
* **Passphrase Engine**: Uses secure random indices to select from a curated library of 50 distinct words.
* **Animation**: Employs a `setInterval` loop to cycle through random glyphs before settling on the final secure character.

---

## 🔒 Security & Privacy

> [!IMPORTANT]
> **Privacy-First Design**: This application is 100% client-side.

* **Zero Server Latency**: No passwords or data are ever sent to a server; everything is **made** locally in your browser.
* **Volatile History**: Session history is stored only in active memory and is cleared upon refreshing the page.
* **Brute-Force Resistance**: High-entropy generation ensures that patterns are unpredictable and secure.

---
