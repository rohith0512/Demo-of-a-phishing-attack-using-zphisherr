# Demo-of-a-phishing-attack-using-zphisherr
this repo represents how a phishing attack is done to acquire the passwords of a target 
 Zphisher – Phishing Simulation Tool

 Introduction

**Zphisher** is a powerful open-source phishing tool. It provides pre-built phishing webpage templates for popular platforms such as **Facebook**, **Instagram**, **Google**, **Snapchat**, **GitHub**, **Yahoo**, and more. This tool can simulate phishing attacks and is typically used in **cybersecurity training** environments to demonstrate how credentials (like usernames and passwords) can be harvested through social engineering tactics This tool is for educational and ethical hacking purposes only. Unauthorized use of phishing tools is illegal and punishable under cybersecurity laws.

---

##  Prerequisites

Before installing Zphisher, ensure your system setup includes:

- **VirtualBox** (for Windows users)
- **Virtual Machine** with **Kali Linux** or any other Linux distro
- Recommended: Use **Visual Studio Code** or terminal emulator within the virtual machine

---

##  Installation Steps

###  Step 1: Navigate to the Desktop and Clone Zphisher

Open your terminal and execute:

```cd Desktop
git clone git://github.com/htr-tech/zphisher.git
cd zphisher
```

![Image](https://github.com/user-attachments/assets/44d60c11-2310-4219-974e-a5138db6c41e)

### step 2: Run the Zphisher script with:
```
bash zphisher.sh
```
![Image](https://github.com/user-attachments/assets/506cbfd9-2cc2-4658-bb33-0d6fd65471b3)

### Step 3: Select the Phishing Template
Once the tool launches, select a template platforms (e.g., Facebook, Instagram, Google, etc.). Use the number keys to choose your target platform.
![Image](https://github.com/user-attachments/assets/a9708738-8282-4745-85e2-5765ba3b3974)


### Step 4: Generate and Share the Phishing Link to the victim
After selecting the platform, Zphisher will generate a phishing link using services like instagram or Cloudflare Tunnels.

![Image](https://github.com/user-attachments/assets/11a30919-14d6-43ad-be1b-7a61a8cc8a87)

we can know the user interface
![Image](https://github.com/user-attachments/assets/1ec19366-5df3-49cb-b943-e998c3486d03)


Credential Capture
ZPhisher logs credentials in the terminal and saves them to logs/ directory.
![Image](https://github.com/user-attachments/assets/e21e8e38-3458-4cca-b705-aef516623ed3)


---
### Mitigation:
Avoid clicking on unexpected or attention-grabbing messages, especially those from unfamiliar senders or sources.

 User Awareness & Training
Conduct regular phishing awareness sessions and simulate phishing attempts using platforms like CISACybeReady.
Educate users to always verify the legitimacy of links and double-check email addresses or domains before clicking or entering information, as recommended by Microsoft Support.

---
### Result:
During the simulation using Zphisher, a phishing page was successfully deployed targeting a selected platform (e.g., instagram). A test user accessed the phishing link and submitted credentials, which were captured by the tool.

