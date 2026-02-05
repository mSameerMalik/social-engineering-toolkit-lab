# 🎭 Social Engineering Toolkit (SET) Lab  
> “Exploits are cool, but humans are the real vulnerability.” — `@mSameerMalik`  
This lab demonstrates the use of the Social Engineering Toolkit (SET) to create a realistic phishing attack scenario by cloning a legitimate website and harvesting credentials in a controlled environment.

## ⚙️ Objective  
- Clone a real-world login page (e.g., Gmail, Facebook)  
- Host it locally using Apache  
- Capture login credentials entered by a victim  
- Store and analyze the logs

## 🧪 Tools Used  
- Social Engineering Toolkit (SET)  
- Kali Linux  
- Apache Web Server

## 🚀 Attack Steps  
1. Run SET:  
   `sudo setoolkit`  
2. Navigate through the following options:  
   `1) Social-Engineering Attacks → 2) Website Attack Vectors → 3) Credential Harvester Attack Method → 2) Site Cloner`  
3. Enter the target site URL when prompted (e.g., https://accounts.google.com)  
4. SET clones the site and serves it from the attacker's IP  
5. Once the victim visits the cloned page and enters credentials, they are saved in `/var/www/html/`

## 📂 Lab Files  
- `SET Lab.docx` – Full lab write-up with screenshots, steps, and explanations

## ⚠️ Legal Disclaimer  
This lab was performed in a secure, isolated lab environment and is intended strictly for educational purposes. Do not replicate these techniques outside of an authorized test scope.

## 👨‍💻 Author  
**Sameer Malik** – Cybersecurity enthusiast and red teamer-in-progress  
GitHub: [mSameerMalik](https://github.com/mSameerMalik)  
LinkedIn: [linkedin.com/in/muhammad-sameer-malik-18b52634b](https://www.linkedin.com/in/muhammad-sameer-malik-18b52634b/)

## 🏷️ Tags  
#SocialEngineering #SET #Phishing #CredentialHarvesting #CyberSecurity #RedTeam #KaliLinux
