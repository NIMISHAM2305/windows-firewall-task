Cybersecurity Internship: Task 4 Setup and Use a Firewall on Windows/Linux

# 🔒 Windows Firewall Configuration Task

## 🎯 Objective

Configure and test basic firewall rules to allow or block traffic using **Windows Firewall**.

---

## 🛠 Tools Used

- Windows Defender Firewall with Advanced Security (`wf.msc`)
- Command Prompt
- Telnet Client (for testing)

---

## ✅ Steps Performed

### 1. Opened Windows Firewall

- Used `wf.msc` to open the Windows Firewall GUI.

### 2. Listed Current Inbound Rules

- Viewed and captured existing rules under **Inbound Rules**.

📸 Screenshot:  
![Current Rules](screenshots/step2-current-rules.png)

---

### 3. Blocked Inbound Traffic on Port 23 (Telnet)

- Created a new inbound rule to **block TCP port 23**.
- Selected: Block the connection → All profiles → Named it `Block Telnet (Port 23)`.

📸 Screenshot:  
![Blocked Rule](screenshots/step3-block-port-23.png)

---

### 4. Tested the Block Rule

- Tried connecting via:

