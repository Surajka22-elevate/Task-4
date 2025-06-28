
🔥 Task 4: Setup and Use a Firewall on Windows

🎯 Objective
Configure and test basic firewall rules to allow or block traffic on Windows using Windows Firewall. Understand how firewalls filter network traffic based on ports and rules.

🛠 Tools Used
- Windows Defender Firewall(built-in with Microsoft Windows)

🧪 Steps Performed (Windows)

1. Opened Windows Defender Firewall with Advanced Security**
   - Control Panel → System and Security → Windows Defender Firewall → Advanced Settings

2. Created Inbound Rule to Block Telnet (Port 23)**
   - Inbound Rules → New Rule
   - Selected **Port**
   - Chose **TCP** and specified **port 23**
   - Selected **Block the connection**
   - Applied to all profiles
   - Named the rule: `Block Telnet Port 23`

3. Created Inbound Rule to Allow SSH (Port 22)**
   - Repeated steps above
   - Chose **Allow the connection**
   - Port: 22
   - Named the rule: `Allow SSH Port 22`

4. Verified Firewall Rules**
   - Checked the list of inbound rules to confirm creation
   - Confirmed they were **enabled and active**

5. Removed Block Rule**
   - Right-clicked on `Block Telnet Port 23` rule
   - Selected **Delete** to restore the original state

## 🔐 Key Concepts

| Term               | Description |
|--------------------|-------------|
| Firewall           | A security tool that manages incoming and outgoing traffic. |
| Inbound Rule       | Filters traffic entering the computer. |
| Outbound Rule      | Filters traffic going out from the computer. |
| Port 23 (Telnet)   | Used for unencrypted communication, vulnerable to attacks. |
| Port 22 (SSH)      | Secure communication channel, used for encrypted access. |
| Stateful Firewall  | Monitors entire connection sessions. |
| Stateless Firewall | Inspects each packet individually. |
| NAT                | Network Address Translation – hides internal IPs from external networks. |


✅ Outcome
- Learned how to apply and manage firewall rules on Windows.
- Practiced blocking and allowing specific traffic based on port numbers.
- Understood the importance of secure protocols like SSH over Telnet.

