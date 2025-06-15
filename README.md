# 🔐 Diffie-Hellman Key Exchange Simulator

This is an interactive web demo that simulates the Diffie-Hellman (DH) key exchange process. Users can:

- Generate public/private keys
- Compute the shared secret
- Simulate a brute-force attacker
- Encrypt/decrypt messages using AES with the shared key

> Built for educational use and cybersecurity portfolios.

## 🚀 How It Works

- Users input or generate `p`, `g`, private keys `a`, `b`
- The app computes public keys `A = g^a mod p`, `B = g^b mod p`
- Shared key is derived: `s = B^a mod p = A^b mod p`
- AES encryption uses `s` to encrypt plaintext messages

## 🔧 Tech Stack

- HTML/CSS/JS (frontend)
- Python (Flask backend - optional)
- Crypto: JavaScript BigInt + WebCrypto API or Python `cryptography`

## 📸 Screenshots

[Insert image of simulation + encryption]

## 📚 Learn More

- [How Diffie-Hellman Works](https://en.wikipedia.org/wiki/Diffie–Hellman_key_exchange)
- [Discrete Logarithm Problem](https://crypto.stackexchange.com/questions/1846/why-is-discrete-logarithm-hard)
