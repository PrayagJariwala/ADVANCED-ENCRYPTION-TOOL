$$ Encryption Tool $$
 
A Python-based AES-256 encryption and decryption tool with a clean, simple GUI. Designed for securing sensitive files with strong encryption and password-based access.

<p align="center">
  <img src="docs/demo.gif" alt="Encryption tool demo" width="600"/>
</p>

# Features

1) AES-256 Encryption/Decryption
2) Password-Based Key Derivation
3) Outputs `.enc` files for encrypted data
4) CLI-based interface
5) Cross-platform (Windows/Linux/Mac)

# Technologies Used

1) Python 3.x
2) cryptography

# How it Works

1. User enters file path and password.
2. Tool generates a secure AES-256 key using PBKDF2 and random salt.
3. File is encrypted using AES-256 in CFB mode.
4. Salt + IV + Encrypted data are saved in the `.enc` file.
5. During decryption, the tool uses the same password to rebuild the key and recover the original data.

# Installation & Usage 

bash
git clone https://github.com/yourusername/advanced_encryption_tool.git
cd advanced_encryption_tool
pip install cryptography
python encryptor.py

Follow the CLI menu:

Enter file path
Enter password
Choose Encrypt or Decrypt

# Future Enhancements 

1)GUI with file browser and password input
2)Password strength meter
3)Cloud sync integration (Google Drive, Dropbox)
4)Secure file shredding after encryption


Made with ❤️ by Prayag Jariwala
Connect on LinkedIn (www.linkedin.com/in/prayag-jariwala-4786b2263/)
Follow on GitHub (https://github.com/Prayag Jariwala)

