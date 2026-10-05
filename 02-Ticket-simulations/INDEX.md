<div align="center">

# 🗂️ Customer Tech Support Portfolio — Visual Index

**One map of the portfolio · 5 topics · 5 scripts · 5 tickets**

Each support topic appears twice: first as a short read-aloud video script, then as a full ticket simulation with screenshots.

![Scripts](https://img.shields.io/badge/Video_Scripts-5-005EB8?style=for-the-badge)
![Tickets](https://img.shields.io/badge/Ticket_Simulations-5-6f42c1?style=for-the-badge)
![Screenshots](https://img.shields.io/badge/Screenshots-120-117864?style=for-the-badge)
![Status](https://img.shields.io/badge/Folders_01_%26_02-Complete-brightgreen?style=for-the-badge)

</div>

---

## 📑 Table of Contents

1. [At a Glance](#at-a-glance)
2. [Portfolio Map](#portfolio-map)
3. [Topic Map — Script to Ticket](#topic-map)
4. [How to Read This Portfolio](#how-to-read)
5. [Evidence Volume](#evidence)
6. [Full Index Table](#index-table)
7. [Folder Links](#folder-links)

---

<a id="at-a-glance"></a>
## 📊 At a Glance

| 🎥 Video Scripts | 🎫 Tickets | 🖼️ Script Screenshots | 🖼️ Ticket Screenshots | 🖼️ Total |
|:---:|:---:|:---:|:---:|:---:|
| **5** | **5** | **41** | **79** | **120** |

---

<a id="portfolio-map"></a>
## 🧭 Portfolio Map

```mermaid
flowchart TD
    Root(["📁 Customer-Tech-Support-Portfolio"]):::root

    Root --> F1["01 Video Knowledge Base<br>5 read-aloud scripts<br>41 screenshots"]:::f1
    Root --> F2["02 Ticket Simulations<br>5 tickets<br>79 screenshots"]:::f2
    Root --> F3["03 Troubleshooting Flowcharts"]:::f3
    Root --> F4["04 Solution Guides"]:::f4
    Root --> F5["05 Escalation Scripts"]:::f5

    F1 --> S1["01.1 DNS"]:::s
    F1 --> S2["01.2 Email"]:::s
    F1 --> S3["01.3 VPN"]:::s
    F1 --> S4["01.4 Printer"]:::s
    F1 --> S5["01.5 WiFi"]:::s

    F2 --> T1["02.1 DNS"]:::t
    F2 --> T2["02.2 Email"]:::t
    F2 --> T3["02.3 VPN"]:::t
    F2 --> T4["02.4 Printer"]:::t
    F2 --> T5["02.5 WiFi"]:::t

    classDef root fill:#2C3E70,stroke:#131B3A,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef f1 fill:#1A5276,stroke:#0B2E43,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef f2 fill:#76448A,stroke:#432752,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef f3 fill:#707B7C,stroke:#3B4142,stroke-width:2px,color:#FFFFFF
    classDef f4 fill:#707B7C,stroke:#3B4142,stroke-width:2px,color:#FFFFFF
    classDef f5 fill:#707B7C,stroke:#3B4142,stroke-width:2px,color:#FFFFFF
    classDef s fill:#e8f1fb,stroke:#005EB8,stroke-width:2px,color:#000
    classDef t fill:#f0eaf8,stroke:#6f42c1,stroke-width:2px,color:#000
```

> Folders 01 and 02 are detailed here. Folders 03, 04 and 05 are shown by name only. Open them for their own contents.

---

<a id="topic-map"></a>
## 🔀 Topic Map — Script to Ticket

Each topic has a short script first and a full ticket second. The ticket uses a different cause from the script.

```mermaid
flowchart LR
    subgraph DNS["🌐 DNS"]
        direction LR
        D1["01.1 Script<br>wrong DNS servers<br>on one PC"]:::s --> D2["02.1 Ticket · P1<br>DNS service stopped<br>on a server"]:::t
    end
    subgraph EML["✉️ Email"]
        direction LR
        E1["01.2 Script<br>cannot send<br>port 25, no auth"]:::s --> E2["02.2 Ticket · P2<br>cannot receive<br>wrong incoming name"]:::t
    end
    subgraph VPN["🔒 VPN"]
        direction LR
        V1["01.3 Script<br>authentication failed<br>locked account"]:::s --> V2["02.3 Ticket · P2<br>stuck on Connecting<br>wrong laptop date"]:::t
    end
    subgraph PRN["🖨️ Printer"]
        direction LR
        P1["01.4 Script<br>printer shows Error<br>port to a dead address"]:::s --> P2["02.4 Ticket · P2<br>port 9100 not reachable<br>listener stopped"]:::t
    end
    subgraph WIF["📶 WiFi"]
        direction LR
        W1["01.5 Script<br>169.254.x.x address<br>set by hand"]:::s --> W2["02.5 Ticket · P2<br>manual address,<br>wrong gateway"]:::t
    end
    DNS ~~~ EML
    EML ~~~ VPN
    VPN ~~~ PRN
    PRN ~~~ WIF

    classDef s fill:#e8f1fb,stroke:#005EB8,stroke-width:2px,color:#000
    classDef t fill:#f0eaf8,stroke:#6f42c1,stroke-width:2px,color:#000
```

---

<a id="how-to-read"></a>
## 🧭 How to Read This Portfolio

```mermaid
flowchart LR
    A["1️⃣ Pick a topic<br>DNS, Email, VPN,<br>Printer or WiFi"]:::a --> B["2️⃣ Read the script<br>short, read-aloud,<br>one fix"]:::b --> C["3️⃣ Open the ticket<br>baseline, fault,<br>evidence, messages"]:::c --> D["4️⃣ Check the limits<br>Scope and Limitations<br>in each file"]:::d

    classDef a fill:#1A5276,stroke:#0B2E43,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef b fill:#B9770E,stroke:#6E4409,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef c fill:#76448A,stroke:#432752,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef d fill:#117864,stroke:#083D33,stroke-width:3px,color:#FFFFFF,font-weight:bold
```

- **Scripts** are short and made to be read aloud during a screen recording.
- **Tickets** are full cases with a ticket record, triage, diagnostics, root cause, fix, verification and three customer messages.
- Every file lists what was tested and what is "described, not tested". Failed attempts and open questions are written down, not hidden.

---

<a id="evidence"></a>
## 🖼️ Evidence Volume

```mermaid
pie showData
    title Screenshots per topic (script + ticket, 120 total)
    "DNS (5 + 14)" : 19
    "Email (16 + 13)" : 29
    "VPN (9 + 20)" : 29
    "Printer (5 + 14)" : 19
    "WiFi (6 + 18)" : 24
```

---

<a id="index-table"></a>
## 📂 Full Index Table

| Topic | Script | Shots | Ticket | Priority | Shots | Checks |
|---|---|:---:|---|:---:|:---:|:---:|
| 🌐 DNS | [01.1 DNS Resolution Issue](./01-Video-knowledge-base/01.1-DNS-Resolution-Issue.md) | 5 | [02.1 TKT-2026-001](./02-Ticket-simulations/02.1-DNS-Ticket.md) | P1 | 14 | 8 |
| ✉️ Email | [01.2 Email Sending Failure](./01-Video-knowledge-base/01.2-Email-Sending-Failure.md) | 16 | [02.2 TKT-2026-002](./02-Ticket-simulations/02.2-Email-Ticket.md) | P2 | 13 | 8 |
| 🔒 VPN | [01.3 VPN Connection Failed](./01-Video-knowledge-base/01.3-VPN-Connection-Failed.md) | 9 | [02.3 TKT-2026-003](./02-Ticket-simulations/02.3-VPN-Ticket.md) | P2 | 20 | 8 |
| 🖨️ Printer | [01.4 Printer Offline](./01-Video-knowledge-base/01.4-Printer-Offline.md) | 5 | [02.4 TKT-2026-004](./02-Ticket-simulations/02.4-Printer-Ticket.md) | P2 | 14 | 6 |
| 📶 WiFi | [01.5 WiFi Connectivity](./01-Video-knowledge-base/01.5-WiFi-Connectivity.md) | 6 | [02.5 TKT-2026-005](./02-Ticket-simulations/02.5-WiFi-Ticket.md) | P2 | 18 | 8 |
| **Total** | **5 scripts** | **41** | **5 tickets** | | **79** | **38** |

---

<a id="folder-links"></a>
## 📁 Folder Links

| Folder | Link |
|---|---|
| 01 Video Knowledge Base | [📂 Open](./01-Video-knowledge-base/README.md) |
| 02 Ticket Simulations | [📂 Open](./02-Ticket-simulations/README.md) |
| 03 Troubleshooting Flowcharts | [📂 Open](./03-Troubleshooting-flowcharts/) |
| 04 Solution Guides | [📂 Open](./04-Solution-guides/) |
| 05 Escalation Scripts | [📂 Open](./05-Escalation-scripts/) |

<div align="center">

🪟 **[Windows Commands](https://learn.microsoft.com/windows-server/administration/windows-commands/windows-commands)** · ☁️ **[DNS Basics](https://www.cloudflare.com/learning/dns/what-is-dns/)**

[⬅️ Back to Portfolio Root](./README.md)

</div>
