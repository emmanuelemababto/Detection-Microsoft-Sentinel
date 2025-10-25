## 🛡️ Project: Microsoft Sentinel Mini SOC Lab

### 1. Objective  
Set up a basic security monitoring system using Microsoft Sentinel to detect failed login attacks.

### 2. Tools Used  
- Microsoft Azure  
- Microsoft Sentinel  
- Log Analytics Workspace  
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
Sentinel successfully detected the failed login attempts and generated alerts, demonstrating how a SOC can identify and respond to threats.

### 5. Conclusion  
This lab shows how Microsoft Sentinel can collect logs, monitor systems, and automatically detect suspicious activity.

# Screenshots of my results



