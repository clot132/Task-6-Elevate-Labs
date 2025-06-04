# Task-6-Elevate-Labs



---

# 🔐 Task 6: Create a Strong Password and Evaluate Its Strength

---

### 🎯 **Objective**

To understand the components of a strong password by creating multiple passwords of varying complexities, testing them using online password strength checkers, and analyzing their effectiveness against common attack methods.

---

### 🧰 **Tools Used**

* [https://www.passwordmeter.com/](https://passwordmeter.com/)
* [https://www.security.org/how-secure-is-my-password/](https://www.security.org/how-secure-is-my-password/) *(Optional)*

---

### 🧪 **Passwords Tested and Results**

| Password       | Length | Complexity Used                | Score (%) | Feedback from Tool                      |
| -------------- | ------ | ------------------------------ | --------- | --------------------------------------- |
| `password123`  | 11     | Lowercase + Numbers            | 25%       | Too common, lacks symbols and uppercase |
| `P@ss1234`     | 8      | Mixed case + Numbers + Symbol  | 58%       | Moderate security                       |
| `MyDog$Blue97` | 12     | Mixed case + Numbers + Symbol  | 85%       | Strong, but could be longer             |
| `Xy@7T!pQz#1k` | 12     | Fully random, mixed complexity | 100%      | Very strong                             |
| `123456`       | 6      | Only numbers                   | 5%        | Extremely weak, easily guessable        |

---

### 📌 **Best Practices Learned**

1. Use at least **12 characters** for better entropy.
2. Include a mix of:

   * **Uppercase letters**
   * **Lowercase letters**
   * **Numbers**
   * **Symbols**
3. Avoid using:

   * Personal info (e.g., birthdate, pet names)
   * Common sequences (`123456`, `qwerty`)
   * Dictionary words or keyboard patterns
4. Use **passphrases** when possible (e.g., `Sun$etInTokyo2025!`).

---

### 🛡️ **Common Password Attacks (Researched)**

| Attack Type     | Description                                                            |
| --------------- | ---------------------------------------------------------------------- |
| **Brute Force** | Tries every possible combination until it finds the password.          |
| **Dictionary**  | Uses a list of commonly used words or passwords to guess.              |
| **Phishing**    | Tricks users into revealing passwords through fake websites or emails. |
| **Keylogging**  | Malicious software records keystrokes to steal passwords.              |

---

### 🔐 **Password Complexity vs. Security**

* The more complex and longer the password, the **harder it becomes to crack**, even with automated tools.
* A weak password (like `password123`) can be guessed in **seconds**, while a strong password (like `Xy@7T!pQz#1k`) may take **trillions of years** to brute-force.
* **Entropy** (randomness + length) is the key to resisting brute-force and dictionary attacks.

---


