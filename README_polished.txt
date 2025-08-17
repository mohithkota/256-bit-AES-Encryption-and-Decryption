# 🔒 Hardware-Efficient 256-bit AES Encryption and Decryption

This repository contains a **Verilog implementation** of a hardware-efficient **256-bit Advanced Encryption Standard (AES)** encryption and decryption algorithm.  

AES is one of the most widely used cryptographic standards for securing sensitive information in applications such as financial transactions, secure communications, and authentication protocols.  

In this project, the AES implementation is optimized for **hardware efficiency** while maintaining strong security against replay attacks.  

---

## ✨ Features
- ✅ **256-bit AES** encryption and decryption support  
- ✅ Designed for **hardware efficiency**  
- ✅ Resistant to replay attacks  
- ✅ Includes **STA (Static Timing Analysis)** results  
- ✅ Layout and transistor-level views provided  

---

## 📖 Background: Cryptographic Techniques

### 🔑 Symmetric-Key Cryptography
- Both sender and receiver share a **single key**.  
- The sender uses this key to encrypt plaintext.  
- The receiver uses the same key to decrypt the ciphertext and recover the plaintext.  
- **AES** is the most celebrated example of this category.  

![Symmetric Key](https://github.com/vendraDp/AES_Vendra_Durgaprasad-/assets/107578770/599d202f-4d52-44ff-9a80-fb58f4da752c)

---

### 🔐 Public-Key Cryptography
- Two related keys (**public** and **private**) are used.  
- Public keys may be freely distributed, while private keys remain secret.  
- The **public key** is used for encryption, and the **private key** for decryption.  
- **RSA** is a well-known example of this category.  

---

## 📊 STA Report

Static Timing Analysis (STA) summary for the top-level module:  

- **Time period**: 10 ns  
- **Setup slack**: 3.972 ns  
- **Hold slack**: 0.397 ns  

![STA Report](https://github.com/vendraDp/AES_Vendra_Durgaprasad-/assets/107578770/857a4f35-68e0-4192-9a39-addedaeb419d)

---

## 🏗️ Layout

### Cell View
![Cell Layout](https://github.com/vendraDp/AES_Vendra_Durgaprasad-/assets/107578770/9b794c14-7df3-4b7f-a1e4-921f91220b04)

### Transistor-Level View
![Transistor Layout](https://github.com/vendraDp/AES_Vendra_Durgaprasad-/assets/107578770/c4ea8e39-ac82-44cd-b24f-1f4ccf09a8ad)

---

## 📂 Repository Structure
```
├── src/               # Verilog source code
├── testbench/         # Testbench files for simulation
├── reports/           # STA reports and synthesis results
├── layout/            # Layout and transistor-level design
└── README.md          # Project documentation
```

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone git@github.com:mohithkota/256-bit-AES-Encryption-and-Decryption.git
   ```
2. Open the project in your preferred **EDA tool** (e.g., Cadence Virtuoso, Synopsys).  
3. Run simulations using the provided testbenches.  
4. View synthesis and STA reports for performance analysis.  

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).  

---

## 🙌 Acknowledgments
- Developed as part of a hardware-efficient cryptographic design study.  
- Based on **AES cryptographic standards** and optimized for **VLSI implementation**.  
