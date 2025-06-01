🔐 RSA Encryption – Java Implementation

This project provides a basic implementation of the RSA encryption algorithm using core Java functionality. It allows users to input two prime numbers, generate public and private keys, encrypt a numeric message, and then decrypt it — all within a single execution.
📖 Overview

    Accepts two prime numbers as input

    Computes n, φ(n), and finds a public key e

    Calculates the private key d using the formula:
    d = (1 + k × φ(n)) / e

    Encrypts and decrypts a numeric message using modular exponentiation

⚙️ Features

    Demonstrates RSA key generation and message encryption/decryption

    Uses only basic Java libraries

    Command-line interaction for user input

🛠️ Requirements

    Java Development Kit (JDK 8 or higher)

🚀 How to Run

    Compile the Java file using:

        javac rsa.java

    Run the compiled class:

        java rsa

    Follow the prompts to enter:

        Two prime numbers

        A number to encrypt and decrypt

📌 Notes

    This implementation uses double for numeric operations, which may cause inaccuracies with large values.

    Intended only for educational purposes and small test values.

    Not suitable for production use or secure applications.

⚠️ Disclaimer

    This RSA implementation is simplified for learning.
    For secure encryption, always use tested libraries and appropriate key sizes with integer-based cryptographic operations.
