# DVWA CSRF Attack Lab

## Overview
This project demonstrates a **Cross-Site Request Forgery (CSRF)** attack using DVWA.  
- **Victim Machine (Ubuntu):** Hosts DVWA application.  
- **Attacker Machine (Kali Linux):** Used to craft and deliver CSRF exploit.  

The goal is to understand how CSRF works, reproduce it in a controlled environment, and discuss mitigation strategies.

---

## Project Structure

DVWA-CSRF-Attack-Lab/
│── README.md # Main overview
│── attacker/ # Attacker setup & screenshots
│── victim/ # Victim setup & screenshots

---

## Setup Guides
- [Attacker Machine Setup (Kali Linux)](Attacker-Machine/README.md)  
- [Victim Machine Setup (Ubuntu DVWA)](Victim-Machine/README.md)  

---

## Attack Description
CSRF allows attackers to trick authenticated users into unknowingly performing malicious actions.  
In this lab:  
- The **victim** is logged into DVWA.  
- The **attacker** crafts a malicious request.  
- When the victim interacts with it, unauthorized actions are executed in DVWA.  

[Read more about CSRF](https://owasp.org/www-community/attacks/csrf).

---

## Results
- DVWA successfully configured on both machines.  
- CSRF attack demonstrated with password change scenario.  
- Screenshots of every step included.  

---

## Mitigation
- Implement **CSRF tokens** in forms.  
- Use **SameSite cookies**.  
- Re-authenticate users for sensitive actions.  

---

## Author
👤 **Aditya Srichandan**  
- 💼 Aspiring SOC Analyst | Cybersecurity Enthusiast  
- 🌐 [LinkedIn](https://www.linkedin.com/in/aditya-srichandan/)  
- 📂 [GitHub](https://github.com/Adi-CUTM/)  

---

## Disclaimer
This project is for **educational and research purposes only**.  
Do not attempt these attacks outside a controlled lab environment.
