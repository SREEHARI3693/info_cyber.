# Encryption Techniques-

## Learning Objectives
- Understand cryptography basics
- Differentiate between symmeteric and asymmetric encryption
- Learn hasing and digital signature concepts

## Cryptography
Cryptography is a technique of securing  information and communications using codes to ensure confiden

## Symmetric Encryption

I

Uses one key for both encryption and decryption.

Fast, suitable for bulk data encryption.


## 🔹 Asymmetric Encryption
- Uses two keys: public key (for encryption) and private key (for decryption).  
- Used for secure key exchange and digital communication.  

---

## 🔑 Hashing
- Converts data into a fixed-length string.  
- Used for secure data integrity verification.
- - Used for secure key exchange and digital communication.

Hashing

Converts data into a fixed-length string.

One-way process - cannot be reversed.

- Used for password storage and integrity

Common Algorithms: SHA-256, MD5 (deprecated)

## Digital Signatures and Certificates

Ensure authenticity and non-repudiation.

A digital signature uses private key to sign data and public key to verify.

Certificates (X.509) are issued by Certificate Authorities (CAs) for trust verification (used in HTTPS)
When visiting https://bank.com
  - browser verifies certificates signed bu CA to ensure authencity.
