# Password Cracking with John the Ripper (JTR) & Networkwalks Tools

> **Lab Status:** Completed Successfully — Flag 1 Captured 
> 
> 
> **Program / Track:** Networkwalks Cybersecurity & Ethical Hacking 
> 
> 
> **Target File:** `My Locked PDF1.pdf`
> 
> 

---

## Overview

In this lab exercise, I practiced password recovery techniques on a password-protected PDF document  using two complementary workflows:

1. **John the Ripper (JTR) + Johnny GUI** on Windows (extracting the PDF hash  and running password cracking through Johnny).


2. **Networkwalks Browser Tools** (**Hash Calculator**  and **Password Cracker** for dictionary-based matching).



Both workflows successfully recovered the document password  and unlocked the protected file  to capture the first flag.

---

## Workflow 1: Password Cracking with JTR & Johnny GUI

### 1. Environment & Tool Setup

* Downloaded **John the Ripper** 


* Installed and launched **Johnny** (the GUI frontend for John the Ripper).



### 2. Hash Extraction 


### 3. Cracking & Flag Capture



Key Takeaways & Security NotesEncryption vs. Hashing:
Encryption is reversible with the proper key, whereas hashing is a one-way function used to verify/store values. Password-protected files rely on cryptographic key derivation/hashing mechanisms that can be targeted offline once the hash is extracted. 

Password Strength: Simple or commonly used passwords (such as password1) are rapidly recovered via dictionary attacks. Using longer, complex passphrases with mixed character sets significantly increases cracking time and resistance.  

Responsible Use: All testing was performed strictly in an authorized lab environment (Networkwalks Week 3 Project Modules) for educational and ethical hacking training purposes.   
