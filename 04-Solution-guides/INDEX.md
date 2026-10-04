# 📑 Index — 04 Solution Guides

Customer-friendly, step-by-step guides for the five most common support problems. Each guide has a decision flowchart, numbered self-help steps, a quick reference, and what to do if nothing works.

---

## 🗺️ Folder Map

```mermaid
%%{init: {'flowchart': {'curve': 'step', 'nodeSpacing': 30, 'rankSpacing': 60, 'padding': 12}}}%%
flowchart LR
    R["<b>Solution Guides</b>"]

    G1["<b>04.1</b> &nbsp;|&nbsp; WiFi"]
    G2["<b>04.2</b> &nbsp;|&nbsp; Email"]
    G3["<b>04.3</b> &nbsp;|&nbsp; VPN"]
    G4["<b>04.4</b> &nbsp;|&nbsp; Printer"]
    G5["<b>04.5</b> &nbsp;|&nbsp; Password Reset"]

    R --> G1
    R --> G2
    R --> G3
    R --> G4
    R --> G5

    classDef root fill:#1E1B4B,stroke:#818CF8,stroke-width:4px,color:#ffffff
    classDef g1 fill:#FFFFFF,stroke:#1A5276,stroke-width:4px,color:#1E1B4B
    classDef g2 fill:#FFFFFF,stroke:#B9770E,stroke-width:4px,color:#1E1B4B
    classDef g3 fill:#FFFFFF,stroke:#117864,stroke-width:4px,color:#1E1B4B
    classDef g4 fill:#FFFFFF,stroke:#2C3E70,stroke-width:4px,color:#1E1B4B
    classDef g5 fill:#FFFFFF,stroke:#76448A,stroke-width:4px,color:#1E1B4B

    class R root
    class G1 g1
    class G2 g2
    class G3 g3
    class G4 g4
    class G5 g5
    linkStyle 0,1,2,3,4 stroke:#64748B,stroke-width:2px
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
