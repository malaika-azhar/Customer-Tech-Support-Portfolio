<div align="center">

# 🎫 Ticket Simulations — IT Support Lab Tickets

**5 Tickets · All Complete · Real Faults, Real Evidence, Role-Played Customers**

Each ticket turns one support problem into a full case: ticket record, lab baseline, triage, diagnostics, root cause, fix, verification and customer messages. Every ticket has its own screenshots.

![DNS](https://img.shields.io/badge/02.1-DNS_Resolution-005EB8?style=for-the-badge)
![Email](https://img.shields.io/badge/02.2-Incoming_Email-6f42c1?style=for-the-badge)
![VPN](https://img.shields.io/badge/02.3-VPN-117864?style=for-the-badge)
![Printer](https://img.shields.io/badge/02.4-Printer-E67E22?style=for-the-badge)
![WiFi](https://img.shields.io/badge/02.5-WiFi-943126?style=for-the-badge)
![Status](https://img.shields.io/badge/Tickets-5_of_5-brightgreen?style=for-the-badge)

### [📂 Jump to the tickets](#tickets-index)

</div>

---

## 📑 Table of Contents

1. [At a Glance](#at-a-glance)
2. [About This Folder](#about)
3. [Ticket Method Pipeline](#pipeline)
4. [Which Ticket Do I Need?](#which-ticket)
5. [Tickets Index](#tickets-index)
6. [How Priority Was Set](#priority)
7. [Where Each Fault Sat](#fault-map)
8. [Ticket Flowcharts](#ticket-flows)
9. [Evidence Volume](#evidence)
10. [Ticket vs Video Script](#vs-scripts)
11. [What Was Real and What Was Simulated](#honesty)
12. [Scope & Limitations](#scope-limitations)
13. [Repo Structure](#repo-structure)

---

<a id="at-a-glance"></a>
## 📊 At a Glance

| 🎫 Tickets | ✅ Complete | 🖼️ Screenshots | 🔍 Diagnostic Checks | 💬 Customer Messages | 🧩 Modules per Ticket |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **5** | **5** | **79** | **38** | **15** | **5** |

---

<a id="about"></a>
## 📖 About This Folder

This folder holds five ticket simulations. Each one follows the same five modules: Lab Build, Triage & Scope, Diagnostics & Root Cause, Resolution & Verification and Customer Communication. The topics match the five video scripts in folder 01, but each ticket uses its own fault, its own evidence and a priority set from the impact.

> [!NOTE]
> These are simulated tickets. The faults were created on purpose in lab setups, and the customers and their quotes are role-played. Private data in screenshots is hidden with black boxes. Each ticket states what was tested and what is "described, not tested". Ticket 02.3 is marked resolved in the lab, but its cause is not proven.

---

<a id="pipeline"></a>
## 🧭 Ticket Method Pipeline

```mermaid
flowchart LR
    A["🔨 Lab Build<br>Baseline, then fault"]:::s1 --> B["🎫 Triage<br>Priority and scope"]:::s2 --> C["🔎 Diagnose<br>Prove the layer"]:::s3 --> D["🛠 Fix<br>Source, not symptom"]:::s4 --> E["✅ Verify<br>Real setup"]:::s5 --> F["💬 Close<br>Customer messages"]:::s6

    classDef s1 fill:#B9770E,stroke:#6E4409,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef s2 fill:#943126,stroke:#571C16,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef s3 fill:#76448A,stroke:#432752,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef s4 fill:#1A5276,stroke:#0B2E43,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef s5 fill:#117864,stroke:#083D33,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef s6 fill:#2C3E70,stroke:#131B3A,stroke-width:3px,color:#FFFFFF,font-weight:bold
```

---

<a id="which-ticket"></a>
## 🧩 Which Ticket Do I Need?

```mermaid
flowchart TD
    Start(["🎫 What is the customer reporting?"]):::start
    Start --> A["Websites unreachable,<br>whole team stuck"]:::q
    Start --> B["New email not<br>arriving in the client"]:::q
    Start --> C["VPN stuck on<br>Connecting"]:::q
    Start --> D["Shared printer<br>not printing"]:::q
    Start --> E["WiFi connected,<br>no internet"]:::q
    A --> T1(["02.1 DNS Resolution"]):::t
    B --> T2(["02.2 Incoming Email"]):::t
    C --> T3(["02.3 VPN"]):::t
    D --> T4(["02.4 Printer"]):::t
    E --> T5(["02.5 WiFi"]):::t

    classDef start fill:#943126,stroke:#571C16,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef q fill:#1A5276,stroke:#0B2E43,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef t fill:#1E8449,stroke:#0E4A28,stroke-width:3px,color:#FFFFFF,font-weight:bold
```

---

<a id="tickets-index"></a>
## 📂 Tickets Index

| # | Ticket | Customer (role-played) | Priority | Date | Screenshots | Checks | Messages | Status |
|:---:|---|---|:---:|:---:|:---:|:---:|:---:|:---:|
| 02.1 | [TKT-2026-001 — DNS Resolution Failure](./02.1-DNS-Ticket.md) | Sarah Khan, Sales, Karachi Office | P1 | 2026-10-03 | 14 | 8 | 3 | ✅ Resolved |
| 02.2 | [TKT-2026-002 — Incoming Email Not Arriving](./02.2-Email-Ticket.md) | Ayesha Malik, Accounts, Lahore Office | P2 | 2026-10-04 | 13 | 8 | 3 | ✅ Resolved |
| 02.3 | [TKT-2026-003 — VPN Stuck on Connecting](./02.3-VPN-Ticket.md) | Zainab Malik, Sales, working from home | P2 | 2026-10-04 | 20 | 8 | 3 | ✅ Resolved in lab (cause not proven) |
| 02.4 | [TKT-2026-004 — Printer Not Printing](./02.4-Printer-Ticket.md) | Finance team member | P2 | 2026-10-04 | 14 | 6 | 3 | ✅ Resolved |
| 02.5 | [TKT-2026-005 — WiFi Connected, No Internet](./02.5-WiFi-Ticket.md) | Hamza Ali, Marketing, Lahore Office | P2 | 2026-10-04 | 18 | 8 | 3 | ✅ Resolved in lab |

---

<a id="priority"></a>
## 🚦 How Priority Was Set

```mermaid
flowchart TD
    Start(["🎫 Read the reported impact"]):::start --> Q{"Who is affected?"}:::q
    Q -->|"Whole team cannot work,<br>CRM down"| P1["P1 Critical"]:::p1
    Q -->|"One user or one<br>shared device"| P2["P2 High"]:::p2
    P1 --> T1["02.1 DNS"]:::t
    P2 --> T2["02.2 Email<br>invoices waiting"]:::t
    P2 --> T3["02.3 VPN<br>client call soon"]:::t
    P2 --> T4["02.4 Printer<br>reports delayed,<br>business still running"]:::t
    P2 --> T5["02.5 WiFi<br>presentation in 30 min"]:::t

    classDef start fill:#2C3E70,stroke:#131B3A,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef q fill:#1A5276,stroke:#0B2E43,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef p1 fill:#C8102E,stroke:#7A0A1C,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef p2 fill:#E67E22,stroke:#8A4B0F,stroke-width:3px,color:#FFFFFF,font-weight:bold
    classDef t fill:#e8f1fb,stroke:#005EB8,stroke-width:2px,color:#000
```

- Only the DNS ticket is P1, because the customer says the whole sales team cannot work.
- The other four are P2: one user or one shared device, with a deadline or delayed work but no whole-team outage.

---

<a id="fault-map"></a>
## 🗺️ Where Each Fault Sat

```mermaid
flowchart LR
    subgraph PC["💻 On the user's PC"]
        direction TB
        F2["02.2 Email<br>wrong incoming server name"]
        F3["02.3 VPN<br>wrong date, stuck on Connecting"]
        F5["02.5 WiFi<br>wrong gateway address"]
    end
    subgraph PATH["🔌 Between PC and device"]
        F4["02.4 Printer<br>printer port 9100 not reachable"]
    end
    subgraph SRV["🖥 On the server"]
        F1["02.1 DNS<br>DNS service stopped"]
    end
    PC ~~~ PATH
    PATH ~~~ SRV

    classDef pc fill:#e8f1fb,stroke:#005EB8,stroke-width:2px,color:#000
    classDef path fill:#fff4e5,stroke:#e08a00,stroke-width:2px,color:#000
    classDef srv fill:#eef7ee,stroke:#2ea44f,stroke-width:2px,color:#000
    class F2,F3,F5 pc
    class F4 path
    class F1 srv
```

---

<a id="ticket-flows"></a>
## 🔀 Ticket Flowcharts

How each ticket went from fault to proof. Each chart uses only what the ticket's own screenshots show.

### 02.1 — DNS Resolution Failure

```mermaid
flowchart LR
    A["🔨 Baseline<br>client resolves via<br>172.16.0.4"]:::a --> B["💥 Fault<br>dnsmasq stopped<br>on the server"]:::b --> C["🔎 Ping IP works,<br>name fails"]:::c --> D["🔎 Server pings,<br>DNS query times out"]:::c --> E["🎯 Root cause<br>DNS service<br>inactive"]:::d --> F["🛠 Start the service"]:::e --> G["✅ Client resolves<br>google.com and<br>crm.lab.local"]:::f

    classDef a fill:#B9770E,stroke:#6E4409,stroke-width:2px,color:#FFFFFF
    classDef b fill:#943126,stroke:#571C16,stroke-width:2px,color:#FFFFFF
    classDef c fill:#76448A,stroke:#432752,stroke-width:2px,color:#FFFFFF
    classDef d fill:#C8102E,stroke:#7A0A1C,stroke-width:2px,color:#FFFFFF
    classDef e fill:#1A5276,stroke:#0B2E43,stroke-width:2px,color:#FFFFFF
    classDef f fill:#117864,stroke:#083D33,stroke-width:2px,color:#FFFFFF
```

### 02.2 — Incoming Email Not Arriving

```mermaid
flowchart LR
    A["🔨 Baseline<br>imap.gmail.com 993"]:::a --> B["💥 Fault<br>server name set to<br>imap.gmail.invalid"]:::b --> C["🔎 Gmail website has<br>the new email,<br>Thunderbird does not"]:::c --> D["🔎 nslookup fails for<br>the wrong name,<br>real name and port work"]:::c --> E["🎯 Root cause<br>server name does<br>not exist"]:::d --> F["🛠 Restore the name,<br>restart"]:::e --> G["✅ New mail<br>arrives"]:::f

    classDef a fill:#B9770E,stroke:#6E4409,stroke-width:2px,color:#FFFFFF
    classDef b fill:#943126,stroke:#571C16,stroke-width:2px,color:#FFFFFF
    classDef c fill:#76448A,stroke:#432752,stroke-width:2px,color:#FFFFFF
    classDef d fill:#C8102E,stroke:#7A0A1C,stroke-width:2px,color:#FFFFFF
    classDef e fill:#1A5276,stroke:#0B2E43,stroke-width:2px,color:#FFFFFF
    classDef f fill:#117864,stroke:#083D33,stroke-width:2px,color:#FFFFFF
```

### 02.3 — VPN Stuck on Connecting

```mermaid
flowchart LR
    A["🔨 Baseline<br>internet and VPN<br>both work"]:::a --> B["💥 Attempt A<br>firewall blocks<br>both VPN programs"]:::b --> C["❌ VPN connected<br>anyway, fault did<br>not work"]:::x --> D["💥 Attempt B<br>laptop date set<br>to 2024"]:::b --> E["🔎 VPN stuck on<br>CONNECTING.."]:::c --> F["🛠 Correct the date"]:::e --> G["✅ VPN connects<br>cause not proven"]:::f

    classDef a fill:#B9770E,stroke:#6E4409,stroke-width:2px,color:#FFFFFF
    classDef b fill:#943126,stroke:#571C16,stroke-width:2px,color:#FFFFFF
    classDef x fill:#707B7C,stroke:#3B4142,stroke-width:2px,color:#FFFFFF
    classDef c fill:#76448A,stroke:#432752,stroke-width:2px,color:#FFFFFF
    classDef e fill:#1A5276,stroke:#0B2E43,stroke-width:2px,color:#FFFFFF
    classDef f fill:#117864,stroke:#083D33,stroke-width:2px,color:#FFFFFF
```

### 02.4 — Printer Not Printing

```mermaid
flowchart LR
    A["🔨 Baseline<br>virtual printer<br>on 127.0.0.1:9100"]:::a --> B["❌ First attempt<br>listener still running,<br>no fault"]:::x --> C["💥 Second attempt<br>listener stopped"]:::b --> D["🔎 Spooler and driver<br>fine, port not<br>reachable"]:::c --> E["🛠 Start the<br>listener"]:::e --> F["✅ Waiting jobs<br>released, two<br>accounts tested"]:::f

    classDef a fill:#B9770E,stroke:#6E4409,stroke-width:2px,color:#FFFFFF
    classDef x fill:#707B7C,stroke:#3B4142,stroke-width:2px,color:#FFFFFF
    classDef b fill:#943126,stroke:#571C16,stroke-width:2px,color:#FFFFFF
    classDef c fill:#76448A,stroke:#432752,stroke-width:2px,color:#FFFFFF
    classDef e fill:#1A5276,stroke:#0B2E43,stroke-width:2px,color:#FFFFFF
    classDef f fill:#117864,stroke:#083D33,stroke-width:2px,color:#FFFFFF
```

### 02.5 — WiFi Connected, No Internet

```mermaid
flowchart LR
    A["🔨 Baseline<br>laptop and phone<br>have internet"]:::a --> B["💥 Fault<br>manual address with<br>gateway 192.168.100.254"]:::b --> C["🔎 Pings to the<br>internet fail,<br>route table shows<br>the bad gateway"]:::c --> D["🎯 Root cause<br>default route points<br>to a gateway with<br>no device"]:::d --> E["🛠 Set the adapter<br>back to DHCP"]:::e --> F["✅ Pings, nslookup<br>and Google Slides<br>checks pass"]:::f

    classDef a fill:#B9770E,stroke:#6E4409,stroke-width:2px,color:#FFFFFF
    classDef b fill:#943126,stroke:#571C16,stroke-width:2px,color:#FFFFFF
    classDef c fill:#76448A,stroke:#432752,stroke-width:2px,color:#FFFFFF
    classDef d fill:#C8102E,stroke:#7A0A1C,stroke-width:2px,color:#FFFFFF
    classDef e fill:#1A5276,stroke:#0B2E43,stroke-width:2px,color:#FFFFFF
    classDef f fill:#117864,stroke:#083D33,stroke-width:2px,color:#FFFFFF
```

---

<a id="evidence"></a>
## 🖼️ Evidence Volume

```mermaid
pie showData
    title Screenshots per ticket (79 total)
    "02.1 DNS" : 14
    "02.2 Email" : 13
    "02.3 VPN" : 20
    "02.4 Printer" : 14
    "02.5 WiFi" : 18
```

---

<a id="vs-scripts"></a>
## 🔀 Ticket vs Video Script

The tickets use the same topics as the video scripts, but not the same cause.

| Topic | Video Script (folder 01) | Ticket (folder 02) |
|---|---|---|
| DNS | 01.1 — wrong DNS servers on one PC | 02.1 — DNS service stopped on a server |
| Email | 01.2 — cannot **send** (port 25, no security, no authentication) | 02.2 — cannot **receive** (wrong incoming server name) |
| VPN | 01.3 — "Authentication failed" with the right password (locked account) | 02.3 — VPN stuck on "Connecting" (wrong laptop date) |
| Printer | 01.4 — virtual printer showing "Error", port pointed at an address with no device | 02.4 — printer port `127.0.0.1:9100` not reachable (listener stopped) |
| WiFi | 01.5 — address in the `169.254.x.x` range set by hand | 02.5 — manual address with a wrong gateway |

---

<a id="honesty"></a>
## 🧪 What Was Real and What Was Simulated

| Ticket | How the fault was made | Main limit stated in the ticket |
|---|---|---|
| 02.1 | `dnsmasq` stopped on an Azure VM (Windows client, Ubuntu server) | Reported team scope was role-played, and one client machine was tested |
| 02.2 | Incoming server name changed by hand in Thunderbird | One account on one PC. Sending was not tested. The number of "Invoice test" sends was not recorded |
| 02.3 | Firewall block (did not work), then the laptop date set to 2024 by hand | Free consumer VPN, not a company gateway. **Cause not proven** |
| 02.4 | A PowerShell listener on `127.0.0.1:9100` acts as the printer, then was stopped | The first attempt did not create the fault. One page was lost by my script. Two accounts on one PC |
| 02.5 | Manual address with a made-up gateway entered with `netsh` | The "make internet faster" story cause is role-play, not proven. The phone check was done before the fault |

- **Customers and quotes** are role-played.
- **Anything not done** is marked "described, not tested" inside each ticket.
- **Failed attempts are kept in the tickets** (VPN firewall block, printer first attempt) instead of being hidden.

---

<a id="scope-limitations"></a>
## 🚧 Scope & Limitations

- **Simulated tickets:** Each one is a role-played case, not a real customer ticket.
- **One fault per ticket:** Other causes of the same symptom are not covered.
- **Small labs:** One PC or one client machine per ticket, plus one phone or a second account in some. No real office networks.
- **Cause not proven in 02.3:** The ticket says what the screenshots show and nothing more.
- **Not a company runbook:** Real workplaces need their own priority rules, escalation paths and identity checks.

These limits are stated here so the tickets are read as demonstrations, not as guaranteed fixes.

---

<a id="repo-structure"></a>
## 📁 Repo Structure

```text
02-Ticket-simulations/
|-- README.md                  (this index)
|-- 02.1-DNS-Ticket.md
|-- 02.2-Email-Ticket.md
|-- 02.3-VPN-Ticket.md
|-- 02.4-Printer-Ticket.md
|-- 02.5-WiFi-Ticket.md
`-- screenshots/               (79 files, names are unique across the 5 tickets)
```

<div align="center">

🎥 **[Video Knowledge Base (folder 01)](../01-Video-knowledge-base/README.md)** · 🪟 **[Windows Commands](https://learn.microsoft.com/windows-server/administration/windows-commands/windows-commands)**

[⬅️ Back to Portfolio Root](../README.md)

</div>
