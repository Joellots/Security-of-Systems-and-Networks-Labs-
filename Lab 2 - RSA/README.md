# Lab 2 - RSA

## Objective:
The purpose of this lab was to demonstrate how to generate an RSA key pair using OpenSSL, encrypt a file with the private key, and extract the public modulus and exponent from the public key. The lab also covered the concepts of key probability in RSA key generation and the importance of using a good RNG for RSA security.

## Tasks Covered:
1. **Generate a 2048-bit RSA Key Pair**: Using OpenSSL's `genpkey` command.
2. **Encrypt Text File**: Encrypt a file containing your name with the private key.
3. **Extract Public Key Information**: Extract the public modulus and exponent from the public key.
4. **Publish Encrypted Text in Base64 Format**: Show the encrypted file's base64 representation.
5. **Probability Calculation**: Calculate the probability of selecting the same prime twice when generating a 1024-bit RSA key.
6. **Importance of RNG**: Explanation of why using a good RNG is crucial for RSA security and a real-world example where a poor RNG led to a vulnerability.

## Key Learnings:
- The RSA encryption process involves generating a private-public key pair, encrypting data with the private key, and verifying it with the public key.
- The probability of selecting the same prime factor in a 1024-bit RSA key is astronomically low.
- A poor RNG can severely compromise RSA security, as demonstrated in the Debian OpenSSL vulnerability (CVE-2008-0166).
