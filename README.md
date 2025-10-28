# Task 6 — Password Strength Evaluation  

---

## 1. Objective  
The goal of this task is to create passwords with different levels of complexity and evaluate their strength using an online password checker.  
This helps in understanding the factors that make a password strong or weak and how to improve password security in real-world situations.

---

## 2. Tools and Resources Used  
- **Tool:** [Password Meter](https://www.passwordmeter.com) – Online password strength checker  
- **System:** Personal Computer (Windows)  
- **Files:**  
  - `passwords.txt` – List of test passwords  
  - `screenshots/` – Screenshots of each password’s strength result  
  - `report.md` – Summary and conclusions  

---

## 3. Passwords Tested  

| No. | Password | Type | Observation |
|-----|-----------|------|--------------|
| 1 | `password` | Weak | Common dictionary word, very easy to guess. |
| 2 | `Password123` | Medium | Has uppercase and numbers but predictable pattern. |
| 3 | `P@ssw0rd!` | Strong | Mix of characters, symbols, and numbers but slightly short. |
| 4 | `Rakshita2025` | Medium | Contains name and year; personal and predictable. |
| 5 | `R@k5h!ta` | Strong | Good complexity but still short (8 chars). |
| 6 | `MyDogNameIsRax!2025` | Very Strong | Long and includes random words and symbols. |

---

## 4. Analysis and Results  
1. Passwords containing **only lowercase letters or common words** (e.g., `password`) were rated *very weak* (score <20%).  
2. Adding **numbers and uppercase letters** (like `Password123`) improved strength slightly but remained *medium*.  
3. Using **symbols and substitutions** (`P@ssw0rd!`, `R@k5h!ta`) improved strength to *strong* but still vulnerable due to short length.  
4. The **longer passphrase-style passwords** like `MyDogNameIsRax!2025` were scored *very strong* (90–100%) because of length and complexity.  

---

## 5. Observations from the Password Meter  
- Password strength increases mainly with **length**.  
- Use of **mixed character types** (uppercase, lowercase, digits, special symbols) adds more entropy.  
- **Avoid personal information** (names, birth years, pets).  
- The best passwords are **long, unique, and unpredictable**.

---

## 6. Learning About Password Attacks  

| Attack Type | Description | Defense |
|--------------|--------------|----------|
| **Brute Force** | Tries every possible combination. | Use long, complex passwords and MFA. |
| **Dictionary Attack** | Uses common words or leaked passwords. | Avoid dictionary words; use random phrases. |
| **Credential Stuffing** | Reuses leaked credentials across sites. | Don’t reuse passwords. |
| **Rainbow Table** | Uses precomputed hashes to reverse weak passwords. | Use salted hashes and long passwords. |

---

## 7. Best Practices Learned  
1. **Use long passphrases** – 15+ characters or multiple random words.  
2. **Avoid personal info** (name, year, or simple substitutions).  
3. **Use a password manager** to store unique complex passwords.  
4. **Enable Multi-Factor Authentication (MFA)** for all accounts.  
5. **Update passwords regularly** and never reuse them across sites.  

---

## 8. Conclusion  
Longer passwords and passphrases are significantly stronger than short complex passwords.  
Adding numbers, symbols, and capital letters helps, but **length and unpredictability** are the most critical factors.  
Using a **password manager** and enabling **MFA** provides stronger protection against brute-force and dictionary attacks.  

---

## 9. Learning Outcome  
I learned how to analyze password strength, identify weak patterns, and understand what makes a password secure.  
This task helped me realize the importance of using strong, unique passphrases and MFA for better account protection.  

---

## 10. Files Included  
- `Password Strength Evaluation.doc` – List of test passwords with screenshots  
- `report.md` – This report  

---

**Submitted by:**  
**Name:** Rakshita B  
**Internship:** Elevate Labs – Cyber Security Intern  
**Date:** 28 October 2025   
