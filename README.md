# 🔐 Password Generator

A sleek, high-security password tool **made** with a focus on privacy and a modern "Midnight Slate" aesthetic.

---

## ✨ Features

* **Dual Modes**: Generate high-entropy **Random** strings or memorable **Passphrases**.
* **Web Crypto API**: Uses cryptographically strong random generation for maximum security.
* **Precision Control**: Set exact counts for uppercase, lowercase, numbers, and symbols.
* **Strength Meter**: Real-time visual feedback on password entropy.
* **Session History**: Stores the last 50 **made** passwords locally in your browser.

## ⚙️ How It Works

* **Secure Entropy**: Uses `crypto.getRandomValues` to ensure non-deterministic, secure results.
* **Smart Validation**: Automatically adjusts character counts to fit your chosen length.
* **Passphrase Logic**: Maps secure random integers to a curated 50-word library.
* **Visual Reveal**: Cycles through random glyphs before settling on the final secure characters.

## 🔒 Security First

* **100% Client-Side**: No data is sent to any server; everything is **made** locally.
* **Brute-Force Protection**: High-entropy generation ensures patterns are unpredictable.

---
