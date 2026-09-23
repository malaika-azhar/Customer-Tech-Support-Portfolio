<a id="top"></a>
<div align="center">

# 🎥 Video Knowledge Base — Index
### IT Support Screen-Recording Scripts
**5 Read-Aloud Scripts — IT Support Portfolio**

![DNS](https://img.shields.io/badge/DNS-Resolution-005EB8?style=for-the-badge)
![Email](https://img.shields.io/badge/Email-SMTP-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white)
![VPN](https://img.shields.io/badge/VPN-Authentication-6f42c1?style=for-the-badge)
![Printer](https://img.shields.io/badge/Printer-Offline-E95420?style=for-the-badge)
![WiFi](https://img.shields.io/badge/WiFi-Connectivity-117864?style=for-the-badge)
![Windows](https://img.shields.io/badge/Endpoint-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Principle](https://img.shields.io/badge/Principle-One_Symptom_One_Script-F39C12?style=for-the-badge)
![Cost](https://img.shields.io/badge/Cost-Free_%26_Built--In_Tools-2ea44f?style=for-the-badge)
![Status](https://img.shields.io/badge/Scripts-5_of_5-brightgreen?style=for-the-badge)

**Quick guide to every script in this folder.**

### [📖 Open the full README](README.md)

</div>

---

<div align="center">

| 📄 Scripts | 🧭 Decision Diagrams | 🧱 Sections per Script | 👤 Customer Scenarios |
|:---:|:---:|:---:|:---:|
| **5** | **5** | **10** | **5** |

</div>

<p align="center">🧩 <b>Format:</b> symptom ➜ read-aloud script ➜ screen recording ➜ related lab folder for evidence</p>

---

## 📑 Step Index

All 5 scripts in this folder, with the file that holds each one.

| # | Script | Layer | Scenario Result (as scripted) | Evidence |
|:---:|---|:---:|---|:---:|
| 1 | DNS Resolution Issue | 🔵 Network | A raw IP ping works but a name ping fails, so the fault is DNS | [01.1 Script](./01.1-DNS-Resolution-Issue.md) |
| 2 | Email Sending Failure | 🟣 Services & Access | Inbound works, outbound is stuck, so the fault is outgoing (SMTP) settings | [01.2 Script](./01.2-Email-Sending-Failure.md) |
| 3 | VPN Connection Failed | 🟣 Services & Access | Password is fine, the account is locked after 5 failures in 15 minutes | [01.3 Script](./01.3-VPN-Connection-Failed.md) |
| 4 | Printer Offline | 🟣 Services & Access | Power and cable are fine, so the fault is software (spooler or driver) | [01.4 Script](./01.4-Printer-Offline.md) |
| 5 | WiFi Connectivity | 🔵 Network | A `169.254.x.x` address shows the laptop got no DHCP answer | [01.5 Script](./01.5-WiFi-Connectivity.md) |

---

## 🔵 Module 1 — Symptom-to-Script Map

<div align="center">
<table>
<tr>
<td align="center" valign="top" width="20%">

**❓ Why won't<br>websites load?**<br>
<sub><code>01.1-DNS-Resolution-Issue</code></sub>

</td>
<td align="center" valign="top" width="20%">

**❓ Why can't I<br>send email?**<br>
<sub><code>01.2-Email-Sending-Failure</code></sub>

</td>
<td align="center" valign="top" width="20%">

**❓ Why does the VPN<br>reject my login?**<br>
<sub><code>01.3-VPN-Connection-Failed</code></sub>

</td>
<td align="center" valign="top" width="20%">

**❓ Why is the printer<br>offline?**<br>
<sub><code>01.4-Printer-Offline</code></sub>

</td>
<td align="center" valign="top" width="20%">

**❓ Why is there no internet<br>on WiFi?**<br>
<sub><code>01.5-WiFi-Connectivity</code></sub>

</td>
</tr>
</table>
</div>

---

## 🟢 Module 2 — Script Structure

Every script uses the same 10 sections, so each one can be read aloud in the same order.

| # | Section | What It Holds |
|:---:|---|---|
| 1 | 📋 Video Title | The customer-facing name of the video |
| 2 | 🎯 Introduction | A short opening line |
| 3 | 🔍 Issue Identification | The first checks and what they show |
| 4 | 🧭 Visual Decision Path | A flowchart of the fix |
| 5 | 🛠 Troubleshooting Steps | The actions and why each one is done |
| 6 | ✅ Verification | How the fix is checked |
| 7 | 👤 Customer Interaction | The customer's request and the agent's reply |
| 8 | 🛠 Tools Used | The commands and settings involved |
| 9 | 📚 Lessons Learned | What to remember for next time |
| 10 | 🔗 Related Lab | The lab folder that holds the evidence |

---

## 🎯 Key Findings Summary

| Script | Key Reading | Verification in Script | Related Lab |
|---|---|---|---|
| 01.1 DNS | Raw IP ping works, name ping fails | `nslookup` resolves and the site loads | `DNS-Troubleshooting-Resolution` |
| 01.2 Email | Inbound works, outbound stuck | Test email delivered | `Email-Troubleshooting` |
| 01.3 VPN | Account locked, password is fine | VPN connects and internal resources open | `Remote-Desktop-VPN-Troubleshooting` |
| 01.4 Printer | Hardware fine, software-level fault | Test print works and printer shows Ready | `Printer-Network-Print-Troubleshooting` |
| 01.5 WiFi | Self-assigned `169.254.x.x` address | Valid IP address and a website loads | `LAN-WiFi-Connectivity-Diagnostics` |

> [!NOTE]
> These are simulated scenarios. The customer quotes are role-played. Screenshots and recordings live in each script's related lab folder, not in this folder.

---

<div align="center">

[⬆️ Back to top](#top) &nbsp;·&nbsp; [📖 Full README](README.md) &nbsp;·&nbsp; [⬅️ Back to Portfolio Root](../README.md)

🎥 **[DNS Basics](https://www.cloudflare.com/learning/dns/what-is-dns/)** · 📶 **[What is DHCP](https://www.cloudflare.com/learning/network-layer/what-is-dhcp/)** · ✉️ **[What is SMTP](https://www.cloudflare.com/learning/email-security/what-is-smtp/)** · 🧭 **[Support Method Pipeline](README.md#pipeline)**

</div>
