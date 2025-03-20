# 🔐 Network Security  

## 📌 Overview  
As part of a **network security course at the University of Maryland**, I explored **multi-factor authentication (MFA) vulnerabilities**, analyzed **cryptographic algorithms**, and implemented **encryption and hashing techniques** using Python. The project focused on **evaluating security weaknesses in MFA systems** and **understanding cryptographic methods used in TCP/IP protocols**.  

---

## 🛠 Key Contributions  

- 🎤 **Presented a 15-minute talk on "Current MFA Methods and Vulnerabilities"**, highlighting weaknesses in **network security practices** related to authentication.  
- 🔐 **Implemented and compared cryptographic algorithms** used in **TCP/IP protocols**, including **AES (ECB mode), DES, Triple DES, and RC4**.  
- 🔄 **Developed Python scripts** for **encryption and decryption** of data using various cryptographic techniques.  
- 🔎 **Implemented and analyzed various hashing algorithms**, comparing their **security and performance** in cryptographic applications.  
- 🛡 **Explored best practices for secure authentication mechanisms**, proposing **alternative solutions to improve MFA security**.  

---

## 🛠 Tools & Technologies Used  

| Category                     | Tools & Technologies |
|------------------------------|----------------------|
| 🔐 Cryptographic Algorithms  | AES, DES, Triple DES, RC4 |
| 🔑 Hashing Algorithms        | SHA-256, MD5, SHA-512 |
| 🏴‍☠️ Network Security Analysis | MFA Research, Protocol Security |
| ⚡ Programming Language      | Python |
| 📜 Security Best Practices   | MFA Security Standards, NIST Guidelines |

---

## ⚙️ Sample Implementations  

### 🔐 AES Encryption in Python (ECB Mode)  
```python
from Crypto.Cipher import AES
import base64

key = b'Sixteen byte key'
cipher = AES.new(key, AES.MODE_ECB)

plaintext = b'NetworkSecurity'
ciphertext = cipher.encrypt(plaintext.ljust(16))

print("Encrypted:", base64.b64encode(ciphertext))
```
🔄 Implementing RC4 Encryption in Python
```python
from Crypto.Cipher import ARC4

key = b'securekey'
cipher = ARC4.new(key)
plaintext = b'Hello Network Security'
ciphertext = cipher.encrypt(plaintext)

print("Encrypted:", ciphertext.hex())
```
🔑 Hashing with SHA-256 in Python
```python
import hashlib

data = "SecureNetwork"
hashed = hashlib.sha256(data.encode()).hexdigest()

print("SHA-256 Hash:", hashed)
```

⸻

📋 Final Report & Evaluation

The project concluded with:

✅ An in-depth analysis of MFA vulnerabilities, identifying weaknesses in OTP, SMS-based MFA, and biometric authentication.
✅ Comparison of cryptographic algorithms, analyzing their efficiency and security in network communication protocols.
✅ Implementation of encryption and decryption methods, ensuring secure data transmission over TCP/IP networks.
✅ Presentation on MFA security flaws, proposing enhanced authentication techniques for better network security.
✅ Final submission & documentation, highlighting best practices in cryptography and authentication security.

⸻

🎤 Presentation & Impact

I compiled the findings on MFA security issues and cryptographic algorithm comparisons into a technical presentation, demonstrating real-world network security concerns and possible mitigations.

⸻

💬 Have Questions?

Feel free to reach out or open an issue! 🚀🔐
