
# 🔐 Password Strength Evaluation Report

This report evaluates multiple passwords with varying complexity using a password strength checker tool (like PasswordMeter). It explores scoring patterns, tips, and real-world security implications.

---

## 📋 Password Strength Table

| # | Password         | Length | Score (%) | Strength   | Notes                                           |
|---|------------------|--------|-----------|------------|-------------------------------------------------|
| 1 | 123456           | 6      | 4%        | Very Weak  | Common and predictable                          |
| 2 | password         | 8      | 12%       | Weak       | Dictionary word, all lowercase                  |
| 3 | P@ssw0rd         | 8      | 47%       | Moderate   | Some complexity (symbols, numbers, caps)        |
| 4 | P@ssw0rd2024     | 12     | 65%       | Good       | Added numbers and length                        |
| 5 | N1kH!L_2025*     | 12     | 91%       | Strong     | Unpredictable, mixed case, symbol               |
| 6 | Tr0ub4dor&3      | 12     | 100%      | Excellent  | Passphrase-style, strong entropy                |
| 7 | hello@world      | 11     | 53%       | Moderate   | Symbol present but predictable                  |
| 8 | Admin123         | 8      | 28%       | Weak       | Common pattern, dictionary prefix               |
| 9 | Jk!89sL@#fQ      | 11     | 95%       | Strong     | High entropy and randomness                     |
|10 | Summer2025!      | 11     | 60%       | Good       | Still guessable due to dictionary + year combo  |

---

## 🧠 Observations

- Longer passwords with a mix of uppercase, lowercase, symbols, and numbers perform the best.
- Dictionary-based or sequential patterns score low.
- Replacing letters with similar symbols (like `@` for `a`) helps but is not foolproof.
- Passphrases like "Tr0ub4dor&3" perform extremely well.

---

## ✅ Tips for Creating Strong Passwords

- Use **12+ characters** whenever possible.
- Combine **uppercase, lowercase, numbers, and special characters**.
- Avoid **names, seasons, and years** (e.g., `Summer2025`).
- Consider using **passphrases** (e.g., `Horse!Battery_Staple88`).
- Never reuse passwords across different services.

---

## 🔓 Common Password Attacks

| Attack Type   | Description |
|---------------|-------------|
| **Brute Force** | Tries every possible combination until success. |
| **Dictionary Attack** | Uses a list of common words and variations. |
| **Credential Stuffing** | Tries known passwords from past data breaches. |
| **Phishing** | Tricks users into revealing passwords. |

---

## 🔐 Impact of Complexity on Security

- Simple passwords (like `123456`) can be cracked in **milliseconds**.
- Passwords with 12+ mixed characters can take **years or centuries** to brute force.
- Even slight complexity increases (e.g., adding a single symbol or uppercase letter) exponentially raise cracking difficulty.

---

## 📌 Conclusion

Strong password hygiene is critical. Using long, complex, and unique passwords for every account — possibly with a **password manager** — provides the best defense against common cyber attacks.

