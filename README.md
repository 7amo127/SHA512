# 🔐 SHA-512 Hash Function in C++

This project is a complete, from-scratch implementation of the **SHA-512** cryptographic hash function written in **C++**. It processes a plain input string and returns a secure 512-bit (64-byte) hexadecimal digest, just like standard libraries — but done manually for educational and demonstrative purposes.

---

## 📌 Overview

The SHA-512 algorithm is part of the SHA-2 family designed by the NSA and published by NIST. It is widely used in digital signatures, password storage, TLS/SSL encryption, and more. This project demonstrates how the algorithm operates internally — including message preprocessing, chunk expansion, and the compression loop — all written in modern C++ without external libraries.

---

## 🧠 Features

✅ Full SHA-512 implementation  
✅ Uses 64-bit word operations, shifts, rotates, and bitwise logic  
✅ Padding, chunking, and binary processing  
✅ Standard constants as per FIPS 180-4  
✅ Clean and readable code structure  
✅ Hexadecimal hash output  
✅ No external dependencies — runs on pure C++

---

## 📂 File Structure

```bash
.
├── SHA512.cpp     # Full implementation of the SHA-512 algorithm
├── README.md      # This file
