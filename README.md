# NETWORKWALKS-MANDISA-DLAMINI-B083-WK3-pdf-password-cracking

## PDF Password Cracking & Hash Analysis Lab
This repository documents a hands-on cybersecurity lab focusing on password recovery and hash cracking techniques against encrypted PDF files using Kali Linux and John the Ripper.   
## 🛠️  Tools & Techniques Used
* Operating System: Kali Linux running on VirtualBox.  
* Cracking Tool: John the Ripper (JTR) version 1.9.0-jumbo.   
* Hash Extractors: Utility tools including pdf2john.   
* Wordlist: Standard dictionary wordlist rockyou.txt.   

## 📋 Step-by-Step Methodology
* Step 1: Hash Extraction: Prepared locked PDF documents and extracted their respective hashes into a format compatible with John the Ripper using pdf2john.
<img width="959" height="539" alt="password1" src="https://github.com/user-attachments/assets/3d4140ae-aee7-404a-9047-0102fc66e845" />

* Step 2: Dictionary Attack: Executed a dictionary-based brute-force attack against the extracted target hash utilizing the rockyou.txt wordlist.
<img width="959" height="539" alt="pdf2and3-passwords" src="https://github.com/user-attachments/assets/d95c5361-e2ca-444e-94b9-55bba5a4e8c0" />

* Step 3: Verification: Displayed the successfully cracked credentials and retrieved the plain-text passwords to unlock the source documents.
<img width="959" height="530" alt="password cracked using JTR" src="https://github.com/user-attachments/assets/a70d587e-4ab7-4726-b181-59d081304423" />


## 🎯 Results
* Successfully recovered plain-text passwords for the locked PDF documents.
<img width="959" height="539" alt="password cracking for pdf1" src="https://github.com/user-attachments/assets/dde38dfd-dada-416e-99b0-a29d68cf0f8c" />
   
* Captured validation flags
<img width="370" height="353" alt="Screenshot 2026-09-23 144157" src="https://github.com/user-attachments/assets/612d39ab-e6f3-4c54-a121-399fbf50ebb1" />
   
