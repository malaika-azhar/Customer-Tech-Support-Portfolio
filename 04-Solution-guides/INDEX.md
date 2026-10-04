# 📑 Index — 04 Solution Guides

Customer-friendly, step-by-step guides for the five most common support problems. Each guide has a decision flowchart, numbered self-help steps, a quick reference, and what to do if nothing works.

---

## 🗺️ Folder Map

```mermaid
flowchart LR
    R(["📘 04 Solution Guides"]):::root --> G1["📶 04.1 WiFi"]:::g1
    R --> G2["📧 04.2 Email"]:::g2
    R --> G3["🔐 04.3 VPN"]:::g3
    R --> G4["🖨 04.4 Printer"]:::g4
    R --> G5["🔑 04.5 Password"]:::g5
    G1 --> S1["Connected, no internet"]:::sym
    G2 --> S2["Cannot send email"]:::sym
    G3 --> S3["Authentication failed"]:::sym
    G4 --> S4["Printer offline"]:::sym
    G5 --> S5["Locked out"]:::sym

    classDef root fill:#943126,stroke:#571C16,stroke-width:2px,color:#FFFFFF,font-weight:bold
    classDef g1 fill:#1A5276,stroke:#0B2E43,stroke-width:2px,color:#FFFFFF,font-weight:bold
    classDef g2 fill:#B9770E,stroke:#6E4409,stroke-width:2px,color:#FFFFFF,font-weight:bold
    classDef g3 fill:#117864,stroke:#083D33,stroke-width:2px,color:#FFFFFF,font-weight:bold
    classDef g4 fill:#2C3E70,stroke:#131B3A,stroke-width:2px,color:#FFFFFF,font-weight:bold
    classDef g5 fill:#76448A,stroke:#432752,stroke-width:2px,color:#FFFFFF,font-weight:bold
    classDef sym fill:#707B7C,stroke:#424949,stroke-width:2px,color:#FFFFFF
```

---

## 📚 Guides

| No. | Guide | Topic | Time | Level | What it fixes |
|:---:|---|:---:|:---:|:---:|---|
| 04.1 | [WiFi Connected but No Internet](04.1-WiFi-Guide.md) | WiFi | 10 min | Easy | Your device says it is **connected** to WiFi, but websites and apps will not load. |
| 04.2 | [Email Not Sending](04.2-Email-Guide.md) | Email | 15 min | Easy to medium | You can **receive** email but cannot **send** it, or your emails are stuck in the **Outbox**. |
| 04.3 | [VPN "Authentication Failed"](04.3-VPN-Guide.md) | VPN | 15 to 20 min | Easy | The VPN says **"Authentication failed"** even though your password seems right. |
| 04.4 | [Printer Offline](04.4-Printer-Guide.md) | Printer | 10 to 15 min | Easy | Your printer shows **"Offline"** or will not print although it is switched on. |
| 04.5 | [Password Reset and Account Lockout](04.5-Password-Reset-Guide.md) | Account | 15 min | Easy | You are **locked out** after typing your password wrong a few times, or you forgot it. |

---

## 🔎 Find a Guide by Symptom

| If you see this | Open |
|---|---|
| WiFi shows connected but websites will not load | [04.1 WiFi](04.1-WiFi-Guide.md) |
| Emails stay in the Outbox or cannot be sent | [04.2 Email](04.2-Email-Guide.md) |
| VPN says authentication failed | [04.3 VPN](04.3-VPN-Guide.md) |
| Printer shows Offline | [04.4 Printer](04.4-Printer-Guide.md) |
| Locked out or forgot your password | [04.5 Password Reset](04.5-Password-Reset-Guide.md) |

---

## 🔗 Related Folders

| Folder | Use it for |
|---|---|
| [01-Video-knowledge-base](../01-Video-knowledge-base/) | Video scripts for each problem |
| [02-Ticket-simulations](../02-Ticket-simulations/) | Practice tickets |
| [03-Troubleshooting-flowcharts](../03-Troubleshooting-flowcharts/) | Agent-side flowcharts |
| [05-Escalation-scripts](../05-Escalation-scripts/) | What to send when escalating |

---

## 📁 Folder Structure

```text
04-Solution-guides/
|-- INDEX.md
|-- 04.1-WiFi-Guide.md
|-- 04.2-Email-Guide.md
|-- 04.3-VPN-Guide.md
|-- 04.4-Printer-Guide.md
|-- 04.5-Password-Reset-Guide.md
`-- README.md
```
