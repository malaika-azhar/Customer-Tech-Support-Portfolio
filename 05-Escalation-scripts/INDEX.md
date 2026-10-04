<div align="center">

# 📇 Index — Escalation Scripts

**05 — Escalation Scripts · Customer Tech Support Portfolio**

Find a script by number, symptom, team, check or section

⬅️ **[Back to Portfolio](../README.md)** · 📖 **[Folder README](README.md)**

![Scripts](https://img.shields.io/badge/Scripts-5-2C3E70?style=for-the-badge)
![Customer Scripts](https://img.shields.io/badge/Customer_Scripts-20-6f42c1?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Simulated_Scripts-566573?style=for-the-badge)

</div>

> [!NOTE]
> Simulated. All tickets, customers and results in these scripts are examples. Team names and tools differ between companies.

---

## 📑 Table of Contents

1. [All Scripts](#all-scripts)
2. [Find by Symptom](#by-symptom)
3. [Find by Team](#by-team)
4. [Find by Check or Command](#by-check)
5. [Jump to a Section](#by-section)
6. [Contents of Each Script](#contents)
7. [Related Work](#related)

---

<a id="all-scripts"></a>
## 📂 All Scripts

| # | Script | Ticket | Priority | Escalated To |
|:---:|---|---|:---:|---|
| 05.1 | [Website Down After DNS Change](05.1-Website-Down.md) | ESC-2026-001 | P1 | Network / DNS team |
| 05.2 | [VPN Authentication Failed, Recurring](05.2-VPN-Auth-Failed.md) | ESC-2026-002 | P2 | Senior Network Engineer |
| 05.3 | [Email Delivery Failure](05.3-Email-Delivery-Failure.md) | ESC-2026-003 | P1 | Email Security Team |
| 05.4 | [Printers Down After Windows Update](05.4-Printer-Update-Issue.md) | ESC-2026-004 | P1 | Systems Team |
| 05.5 | [WiFi Down, DHCP Pool Exhausted](05.5-WiFi-DHCP-Exhaustion.md) | ESC-2026-005 | P1 | Network Team |

---

<a id="by-symptom"></a>
## 🗣️ Find by Symptom

| The customer says | Script |
|---|---|
| "My website is down" / "site can't be reached" after a DNS change | [05.1 Website Down](05.1-Website-Down.md) |
| "I can't connect to the VPN" / "my account keeps locking" | [05.2 VPN Lockout](05.2-VPN-Auth-Failed.md) |
| "Emails from a client are not arriving" | [05.3 Email Failure](05.3-Email-Delivery-Failure.md) |
| "Nothing prints since the update" | [05.4 Printers](05.4-Printer-Update-Issue.md) |
| "Nobody can connect to the WiFi" / "WiFi connected but no internet" | [05.5 WiFi and DHCP](05.5-WiFi-DHCP-Exhaustion.md) |

---

<a id="by-team"></a>
## 👥 Find by Team

| Team | Used in | When |
|---|---|---|
| Network / DNS team | [05.1](05.1-Website-Down.md) | Authoritative answer differs from public resolvers, or the record is wrong |
| Hosting team | [05.1](05.1-Website-Down.md) | Many sites are down, not one domain |
| Senior Network Engineer | [05.2](05.2-VPN-Auth-Failed.md) | Repeated lockouts, or Tier 1 cannot see the lockout source |
| Security team | [05.2](05.2-VPN-Auth-Failed.md), [05.4](05.4-Printer-Update-Issue.md) | Unknown lockout source (05.2). Before removing a security update (05.4) |
| Email Security Team | [05.3](05.3-Email-Delivery-Failure.md) | A filter rule held or blocked the mail |
| Mail Flow team | [05.3](05.3-Email-Delivery-Failure.md) | The trace finds no record of the mail |
| Systems Team | [05.4](05.4-Printer-Update-Issue.md) | Many computers lost printing after the same update |
| Network Team | [05.4](05.4-Printer-Update-Issue.md), [05.5](05.5-WiFi-DHCP-Exhaustion.md) | Printers do not answer ping (05.4). DHCP pool is full (05.5) |

---

<a id="by-check"></a>
## 🔎 Find by Check or Command

| Check | What it tells you | Script |
|---|---|---|
| `dig` on the authoritative server and on public resolvers | Cache delay or wrong DNS record | [05.1](05.1-Website-Down.md) |
| Lockout event 4740 and failed sign-in event 4625 | Which device keeps sending the wrong password | [05.2](05.2-VPN-Auth-Failed.md) |
| Message trace for the sender | Held, rejected, delivered or never seen | [05.3](05.3-Email-Delivery-Failure.md) |
| `Authentication-Results` header (SPF, DKIM, DMARC) | Whether the sender is genuine | [05.3](05.3-Email-Delivery-Failure.md) |
| Test page from a computer without the update | Computer fault or printer fault | [05.4](05.4-Printer-Update-Issue.md) |
| Event Viewer, PrintService Admin log | Why the driver fails to load | [05.4](05.4-Printer-Update-Issue.md) |
| `ipconfig` showing `169.254.x.x` | The device got no address from DHCP | [05.5](05.5-WiFi-DHCP-Exhaustion.md) |
| DHCP scope statistics and lease list | Pool full, and what is filling it | [05.5](05.5-WiFi-DHCP-Exhaustion.md) |

---

<a id="by-section"></a>
## 🧭 Jump to a Section

| Script | Escalation Flow | Customer Scripts | Escalation Note | Decision Path | Mistakes & Fixes |
|---|:---:|:---:|:---:|:---:|:---:|
| 05.1 Website Down | [Go](05.1-Website-Down.md#escalation-flow) | [Go](05.1-Website-Down.md#customer-scripts) | [Go](05.1-Website-Down.md#internal-note) | [Go](05.1-Website-Down.md#decision-path) | [Go](05.1-Website-Down.md#mistakes-fixes) |
| 05.2 VPN Lockout | [Go](05.2-VPN-Auth-Failed.md#escalation-flow) | [Go](05.2-VPN-Auth-Failed.md#customer-scripts) | [Go](05.2-VPN-Auth-Failed.md#internal-note) | [Go](05.2-VPN-Auth-Failed.md#decision-path) | [Go](05.2-VPN-Auth-Failed.md#mistakes-fixes) |
| 05.3 Email Failure | [Go](05.3-Email-Delivery-Failure.md#escalation-flow) | [Go](05.3-Email-Delivery-Failure.md#customer-scripts) | [Go](05.3-Email-Delivery-Failure.md#internal-note) | [Go](05.3-Email-Delivery-Failure.md#decision-path) | [Go](05.3-Email-Delivery-Failure.md#mistakes-fixes) |
| 05.4 Printers | [Go](05.4-Printer-Update-Issue.md#escalation-flow) | [Go](05.4-Printer-Update-Issue.md#customer-scripts) | [Go](05.4-Printer-Update-Issue.md#internal-note) | [Go](05.4-Printer-Update-Issue.md#decision-path) | [Go](05.4-Printer-Update-Issue.md#mistakes-fixes) |
| 05.5 WiFi and DHCP | [Go](05.5-WiFi-DHCP-Exhaustion.md#escalation-flow) | [Go](05.5-WiFi-DHCP-Exhaustion.md#customer-scripts) | [Go](05.5-WiFi-DHCP-Exhaustion.md#internal-note) | [Go](05.5-WiFi-DHCP-Exhaustion.md#decision-path) | [Go](05.5-WiFi-DHCP-Exhaustion.md#mistakes-fixes) |

---

<a id="contents"></a>
## 📊 Contents of Each Script

| Script | Customer Scripts | Diagnostic Checks | Flowcharts | Mistakes Covered |
|---|:---:|:---:|:---:|:---:|
| 05.1 Website Down | 4 | 5 | 2 | 5 |
| 05.2 VPN Lockout | 4 | 5 | 2 | 6 |
| 05.3 Email Failure | 4 | 5 | 2 | 6 |
| 05.4 Printers | 4 | 5 | 2 | 6 |
| 05.5 WiFi and DHCP | 4 | 5 | 2 | 6 |
| **Total** | **20** | **25** | **10** | **29** |

Every script has the same parts: Escalation Record, Project Background, Escalation Flow, When to Escalate, Customer Scripts, Internal Escalation Note, Decision Path, Project Summary, Common Mistakes & Fixes, Scope & Limitations, What I Learned and Skills Demonstrated.

---

<a id="related"></a>
## 🔗 Related Work

- 📖 **[Folder README](README.md)** — overview, flowcharts, tables and rules shared by all five scripts
- 🎫 **[02.1 DNS Ticket](../02-Ticket-simulations/02.1-DNS-Ticket.md)** — the real lab ticket behind the DNS topic in 05.1
- ⬅️ **[Back to Portfolio](../README.md)**

<div align="center">

⬅️ **[Back to Portfolio](../README.md)** · 📖 **[Folder README](README.md)** · 📂 **[All Scripts](#all-scripts)**

</div>
