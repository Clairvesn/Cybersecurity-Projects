# 🛡️ Incident Report: Unauthorized Login Attempt

## 📅 Date of Incident:
September 3, 2025

## 🖥️ System:
Clairvens-Laptop (Windows 10)

## 👤 Account Affected:
clairvens.student

## 🔍 Summary:
Multiple failed login attempts were detected on the local system. The Windows Security Log confirms 3 failed attempts followed by a successful login within a 3-minute window.

Evidence:
- Event ID 4625 (Failed login):  
  - 3 events between 6:49:48 - 6:49:51
  - Logon Type: 2 (Interactive)  
  - Source: Logon Process: User32

- Event ID 4624 (Successful login):  
  - 6:49:56
  - Account: Clairvens


 Mitigation:
- Enable account lockout policy after 3 failed attempts  
- Set up alerting for repeated login failures  
- Implement MFA for interactive login (if supported)

Note:
This was a simulated event to demonstrate basic log triage and incident documentation for SOC-level analysis.
<img width="1908" height="1080" alt="fail" src="https://github.com/user-attachments/assets/a80069e8-a47a-452c-ae19-b58f6f44887d" />
<img width="1925" height="1080" alt="success" src="https://github.com/user-attachments/assets/e0a75692-26d5-400f-b195-b6d77881f374" />
