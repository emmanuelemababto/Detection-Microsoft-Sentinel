## 🛡️ Project: Microsoft Sentinel Mini SOC Lab

### 1. Objective  
Set up a basic security monitoring system using Microsoft Sentinel to detect failed login attacks.

### 2. Tools Used  
- Microsoft Azure  
- Microsoft Sentinel  
- Log Analytics Workspace
- Azure data collection rule
- Geoip mapping
- Two Windows 10 VMs (Attacker & Victim)

### 3. Steps  
- Create a Log Analytics Workspace in Azure.  
- Add Microsoft Sentinel to the workspace.  
- Set up two Windows VMs: one as Victim, one as Attacker.  
- Connect the Victim VM to Sentinel using the Log Analytics agent.  
- Simulate failed login attempts from the Attacker VM.  
- Create a detection rule in Sentinel for multiple failed logins.  
-  Observe alerts and incidents triggered by the attack.

### 4. Result  
Sentinel successfully detected the failed login attempts and generated alerts, demonstrating how a SOC can identify and respond to threats.Within an hour of seeting this honeypot minutes i got  over 1000 failed logins.

### 5. Conclusion  
This lab shows how Microsoft Sentinel can collect logs, monitor systems, and automatically detect suspicious activity.

# Screenshots of my results of my failed logins 
100 failed logins <img width="716" height="401" alt="Image" src="https://github.com/user-attachments/assets/494c1674-6d82-4464-adf8-115158d0ab65" />
using QKL query to find failed logins <img width="890" height="344" alt="Image" src="https://github.com/user-attachments/assets/d4ea6c1f-ba79-49ff-a004-d571f6dcf426" />
 <img width="634" height="330" alt="Image" src="https://github.com/user-attachments/assets/90435c3c-45e9-419a-889e-f924114ad0e0" />
<img width="652" height="330" alt="Image" src="https://github.com/user-attachments/assets/05d31a5c-b051-42db-b70a-e4a185187131" />
<img width="851" height="418" alt="Image" src="https://github.com/user-attachments/assets/07e88886-240f-4df7-a669-b29f9dbb681f" />
<img width="677" height="402" alt="Image" src="https://github.com/user-attachments/assets/cfb13377-fc94-4afd-a926-42da0d2930dc" />
linking log analystic workspace with Microsoft Sentinel <img width="455" height="451" alt="Image" src="https://github.com/user-attachments/assets/f7b21fe7-7ea6-44ef-8a01-fd3827cbb6e2" />
RDP to my VM  <img width="549" height="353" alt="Image" src="https://github.com/user-attachments/assets/276059b3-361d-4164-9666-5026dd859f06" />
deleting my defualt firewall rule for my VM <img width="917" height="350" alt="Image" src="https://github.com/user-attachments/assets/aba1a85b-ead2-46a0-9a2f-fa046c533991" />




