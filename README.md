🔐 Password Generator
A sleek, high-security password generation tool made with a focus on privacy, customization, and a modern "Midnight Slate" aesthetic.

✨ Features
Dual Modes: Switch between high-entropy Random strings and memorable Passphrases.

Web Crypto API: Utilizes cryptographically strong pseudo-random number generation (window.crypto) for maximum security.

Precision Control: Fine-tune the exact count of uppercase letters, numbers, and symbols.

Visual Strength Meter: Real-time feedback on password entropy with a multi-segment indicator.

Session History: Keep track of your made passwords during your current session (stored locally, up to 50 items).

Matrix Reveal Effect: A unique animation style for generating and displaying new credentials.

🔒 Security First
Zero Server Side: This app does not send your passwords to any server. Everything is made and processed locally in your browser.

Entropy: Uses Uint32Array with crypto.getRandomValues() to ensure patterns are unpredictable and secure against brute-force attacks.
