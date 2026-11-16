# Week 03 – Password Cracking & Hash Analysis

**Cybersecurity & Ethical Hacking Training | Networkwalks**

This repository documents my Week 3 practical work focused on password security, hash extraction, and dictionary-based password auditing.

The exercises provided hands-on experience with industry-used password auditing tools and demonstrated how weak passwords can be recovered through dictionary-based attacks.

## 🎯 Learning Objectives

- Understand password hashing and its role in authentication.
- Learn the difference between encryption and hashing.
- Extract password hashes from protected PDF documents.
- Perform dictionary-based password auditing.
- Understand the functionality of John the Ripper and Johnny GUI.
- Explore browser-based password auditing tools.
- Understand the importance of strong password policies.

## 🧪 Practical Modules

### Module 1: Password Cracking with John the Ripper (JTR)

**Tools Used:**
- John the Ripper (Jumbo)
- Johnny GUI
- PDF Hash Extractor

**Implementation:**

1. Installed John the Ripper and Johnny GUI on Windows.
2. Configured Johnny to use the John the Ripper executable.
3. Extracted the password hash from a protected PDF.
4. Saved the extracted hash in a text file.
5. Imported the hash into Johnny.
6. Initiated a password auditing attack.
7. Verified the recovered password by opening the protected PDF.

**Key Learning:**

Understood how John the Ripper performs password auditing and how Johnny provides a graphical interface for interacting with the underlying engine.

### Module 2: Password Cracking with Networkwalks Tools

**Tools Used:**
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Web Browser

**Implementation:**

1. Uploaded the protected PDF to the Networkwalks Hash Calculator.
2. Extracted the PDF password hash.
3. Copied the complete hash value.
4. Opened the Networkwalks Password Cracker.
5. Submitted the extracted hash.
6. Executed the dictionary-based password attack.
7. Observed the recovered password.
8. Verified the result by opening the protected PDF.

**Key Learning:**

Explored a browser-based approach to password auditing and understood the workflow from hash extraction to password recovery.

## 🔍 Technical Concepts

| Concept | Description |
|---|---|
| Hashing | One-way transformation of data into a fixed-format digest. |
| Password Hash | A stored representation used for password verification. |
| Dictionary Attack | Testing candidate passwords from a predefined wordlist. |
| John the Ripper | Password security auditing tool. |
| Johnny GUI | Graphical interface for John the Ripper. |
| PDF Hash Extraction | Extracting password hash data from protected PDF files. |

## 🏁 Results

Successfully completed both practical modules and captured the assigned completion flags.

The exercises demonstrated the importance of password complexity and the risks associated with predictable passwords.

## 📸 Practical Evidence

Screenshots documenting the following activities are maintained in the repository:

- John the Ripper configuration.
- Hash extraction process.
- Password auditing execution.
- Networkwalks Password Cracker.
- Successful completion confirmations.

## 🛠️ Environment

- Operating System: Windows 11
- Platform: Windows Desktop
- Tools: John the Ripper Jumbo, Johnny GUI, Networkwalks Web Tools
- Attack Method: Dictionary-based password auditing

## 🔐 Security & Ethical Considerations

All practical exercises were conducted using training-provided files and authorized lab environments.

Password auditing tools should only be used on files, systems, and password hashes for which explicit authorization has been granted.

## 📚 Training Credit

Networkwalks – Cybersecurity & Ethical Hacking Training

**Week 03 | Project Module 1 & Project Module 2**

---

*This repository is maintained for educational purposes and to document practical cybersecurity learning.*
