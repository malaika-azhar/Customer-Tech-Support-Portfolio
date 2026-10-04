<a id="top"></a>
<div align="center">

# 🎧 Customer Tech Support Portfolio

**Tier-2 Technical Support · Troubleshooting · Escalation**

25 projects that show how a support ticket goes from the first call to a fix or a clean handover.

![Projects](https://img.shields.io/badge/Projects-25-005EB8?style=for-the-badge)
![Folders](https://img.shields.io/badge/Folders-5-6f42c1?style=for-the-badge)
![Windows](https://img.shields.io/badge/Endpoint-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Support](https://img.shields.io/badge/Skill-Customer_Support-E95420?style=for-the-badge)
![Cost](https://img.shields.io/badge/Cost-Free-2ea44f?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

<p align="center"><a href="INDEX.md">🗂️ Full Index</a> · <a href="#whats-inside">📁 What's Inside</a> · <a href="#problems-covered">🧩 Problems Covered</a> · <a href="#navigate">🧭 How to Navigate</a></p>

</div>

---

<a id="contents"></a>
## 📑 Table of Contents

1. [At a Glance](#at-a-glance)
2. [About This Portfolio](#about)
3. [What's Inside](#whats-inside)
4. [Problems Covered](#problems-covered)
5. [How the Projects Fit Together](#fit-together)
6. [How to Navigate](#navigate)
7. [Skills Demonstrated](#skills-demonstrated)
8. [Tools & Standards](#tools-standards)
9. [Scope & Limitations](#scope-limitations)
10. [Repo Structure](#repo-structure)
11. [Author](#author)

---

<a id="at-a-glance"></a>
## 📊 At a Glance

| 📁 Folders | 📄 Projects | 🧩 Problems Covered | 🛠️ Deliverable Types |
|:---:|:---:|:---:|:---:|
| **5** | **25** | **5** | **5** |

<p align="right"><a href="#contents">↑ Back to contents</a></p>

---

<a id="about"></a>
## 📖 About This Portfolio

A Tier-2 support engineer does more than fix a problem. They explain it clearly, work it step by step, and hand it on with enough evidence that nobody has to start again.

This portfolio covers five common problems (DNS, Email, VPN, Printer and WiFi). Each one is worked in five different ways, so the same problem is shown from the first customer call to the final escalation.

- **Learn it:** a video script that explains the problem in plain language.
- **Practice it:** a ticket simulation worked from report to resolution.
- **Diagnose it:** a decision flowchart with a branch for each cause.
- **Fix it:** a step-by-step solution guide written for the customer.
- **Hand it on:** an escalation script with everything the next team needs.

<p align="right"><a href="#contents">↑ Back to contents</a></p>

---

<a id="whats-inside"></a>
## 📁 What's Inside

| Folder | What it holds | Projects |
|---|---|:---:|
| [01-Video-knowledge-base](01-Video-knowledge-base/) | Video scripts that explain each problem | 5 |
| [02-Ticket-simulations](02-Ticket-simulations/) | Practice tickets worked from report to resolution | 5 |
| [03-Troubleshooting-flowcharts](03-Troubleshooting-flowcharts/) | Decision flowcharts with a branch for each cause | 5 |
| [04-Solution-guides](04-Solution-guides/) | Step-by-step fixes written for the customer | 5 |
| [05-Escalation-scripts](05-Escalation-scripts/) | Ready-to-send messages for handing a ticket on | 5 |

Every project is listed, with direct links, in the [Full Index](INDEX.md).

<p align="right"><a href="#contents">↑ Back to contents</a></p>

---

<a id="problems-covered"></a>
## 🧩 Problems Covered

| Problem | Typical customer complaint | Start here |
|---|---|---|
| 🌐 **DNS** | "Server not found" | [DNS Flowchart](03-Troubleshooting-flowcharts/03.5-DNS-Flowchart.md) |
| 📧 **Email** | "Email is not working" | [Email Flowchart](03-Troubleshooting-flowcharts/03.2-Email-Flowchart.md) |
| 🔐 **VPN** | "VPN won't connect" | [VPN Flowchart](03-Troubleshooting-flowcharts/03.3-VPN-Flowchart.md) |
| 🖨️ **Printer** | "Printer is offline" | [Printer Flowchart](03-Troubleshooting-flowcharts/03.4-Printer-Flowchart.md) |
| 📶 **WiFi** | "WiFi is not working" | [WiFi Flowchart](03-Troubleshooting-flowcharts/03.1-WiFi-Flowchart.md) |

The [Find by Problem](INDEX.md#find-by-problem) table in the index links the video, ticket, flowchart, guide and escalation script for each one.

<p align="right"><a href="#contents">↑ Back to contents</a></p>

---

<a id="fit-together"></a>
## 🔗 How the Projects Fit Together

```mermaid
flowchart LR
    A["🎬 Learn"]:::s1 --> B["🎫 Practice"]:::s2 --> C["🧭 Diagnose"]:::s3 --> D["📘 Fix"]:::s4 --> E["📨 Escalate"]:::s5

    classDef s1 fill:#1A5276,stroke:#0B2E43,stroke-width:2px,color:#FFFFFF,font-weight:bold
    classDef s2 fill:#76448A,stroke:#432752,stroke-width:2px,color:#FFFFFF,font-weight:bold
    classDef s3 fill:#B9770E,stroke:#6E4409,stroke-width:2px,color:#FFFFFF,font-weight:bold
    classDef s4 fill:#117864,stroke:#083D33,stroke-width:2px,color:#FFFFFF,font-weight:bold
    classDef s5 fill:#2C3E70,stroke:#131B3A,stroke-width:2px,color:#FFFFFF,font-weight:bold
```
<p align="center"><em>The five folders follow the life of a ticket, in the same order.</em></p>

The flowcharts also point to each other. WiFi is the base layer, so Email, VPN, Printer and DNS send you there first when the network itself is the problem. WiFi and VPN point to DNS when pinging an IP works but pinging a name does not.

<p align="right"><a href="#contents">↑ Back to contents</a></p>

---

<a id="navigate"></a>
## 🧭 How to Navigate

1. **Know the problem?** Use [Find by Problem](INDEX.md#find-by-problem) in the index and open the format you need.
2. **Want to see how a ticket is solved?** Read one problem from start to finish. The index has a [suggested reading order](INDEX.md#reading-order).
3. **Want to see the diagnosing logic?** Open [03-Troubleshooting-flowcharts](03-Troubleshooting-flowcharts/). Each flowchart has a Master chart and three branches.
4. **Looking for something specific?** The [Full Index](INDEX.md) lists all 25 projects.

<p align="right"><a href="#contents">↑ Back to contents</a></p>

---

<a id="skills-demonstrated"></a>
## 🛠️ Skills Demonstrated

- Structured troubleshooting for DNS, email, VPN, printer and WiFi faults
- Separating client, network, account, server and provider faults
- Reading `ping`, `nslookup`, `ipconfig` and `netsh` output
- Writing for the customer: clear fixes and calm updates during an incident
- Writing escalation evidence so the next team does not have to repeat questions
- Building decision flowcharts and numbered step guides
- Keeping a consistent layout across 25 documents

<p align="right"><a href="#contents">↑ Back to contents</a></p>

---

<a id="tools-standards"></a>
## 🔧 Tools & Standards

| Item | Detail |
|---|---|
| **Client OS** | Windows |
| **Commands** | `ping`, `nslookup`, `ipconfig`, `netsh`, `Test-NetConnection` |
| **Format** | Markdown with Mermaid and PNG diagrams |
| **File naming** | Numbered by folder (for example `03.4-Printer-Flowchart.md`) |
| **Images** | Stored in a `screenshots/` folder inside the folder that uses them |

<p align="right"><a href="#contents">↑ Back to contents</a></p>

---

<a id="scope-limitations"></a>
## 🚧 Scope & Limitations

- **Windows clients only.** Other operating systems use different commands.
- **Simulations, not live incidents.** The tickets are practice scenarios, and the flowcharts were not run against a live outage.
- **Support-agent access only.** Router, server, firewall and gateway changes are outside these projects, so they end in an escalation.
- **Vendor settings vary.** Email, VPN and printer settings depend on the provider or company, so follow their published settings.

<p align="right"><a href="#contents">↑ Back to contents</a></p>

---

<a id="repo-structure"></a>
## 📁 Repo Structure

```text
customer-tech-support-portfolio/
|-- README.md
|-- INDEX.md
|-- PROJECTS-SUMMARY.md
|-- 01-Video-knowledge-base/
|-- 02-Ticket-simulations/
|-- 03-Troubleshooting-flowcharts/
|-- 04-Solution-guides/
`-- 05-Escalation-scripts/
```

<p align="right"><a href="#contents">↑ Back to contents</a></p>

---

<a id="author"></a>
## 👤 Author

**Malaika** · [github.com/malaika-azhar](https://github.com/malaika-azhar)

<div align="center">

[🗂️ Full Index](INDEX.md) · [↑ Back to top](#top)

</div>
