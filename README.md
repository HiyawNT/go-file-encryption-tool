# File Encryption and Decryption Utility in Go

This is a lightweight command-line utility written in Go for encrypting and decrypting files. It provides a simple interface for securing sensitive data by converting files into an encrypted format and restoring them to their original state when needed.

---

## Features

- **Encryption:** Securely encrypts any file, protecting its content from unauthorized access.
- **Decryption:** Restores encrypted files back to their original state with ease.
- **Simple CLI Usage:** Intuitive commands for quick and efficient file encryption and decryption.

---

## Requirements

- [Go](https://golang.org/dl/) (version 1.18 or later)

---

## Usage

### Encryption

To encrypt a file, use the following command:

```bash
go run . encrypt <file_name>
```

create a password for the encryption Note: remember the password the file is lost without it

### Decryption

To decrypt an encrypted file, use the following command:

```bash
go run . decrypt <file_name>
```

enter the file encryption password

### Sample Files Included

To test the encryption/decryption there are image file "image_encryption_test.webp" and audio file "audio_quality_test.wav" this are made for even a single quality loss will distort the files making them a perfect way of testing the GFE(Go File Encryption)
