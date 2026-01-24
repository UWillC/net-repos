# net-repos

A curated collection of network/DevOps projects worth your attention.

**Rule:** Only projects I've tested myself or plan to use.

---

## Table of Contents

- [Automation](#automation)
- [Diagnostics](#diagnostics)
- [Monitoring](#monitoring)
- [Templates & Parsing](#templates--parsing)
- [Utilities](#utilities)
- [Security](#security)
- [AI Tools](#ai-tools)

---

## Automation

> Network automation tools: Ansible, Nornir, Netmiko, NAPALM...

_No entries yet — add the first one!_

<!-- TEMPLATE:
### [Project Name](link)
**Stars:** X | **Last update:** YYYY-MM
**What it does:** One sentence description
**Why it's worth it:** Your opinion / use case
-->

---

## Diagnostics

> Network diagnostic tools: traceroute, path analysis, troubleshooting...

### [ttl](https://github.com/lance0/ttl)
**Author:** lance0 | **Language:** Rust
**What it does:** Advanced network diagnostic tool — "traceroute on steroids" with continuous monitoring and real-time visualization
**Why it's worth it:** Goes beyond traditional traceroute with features like:
- Path MTU discovery
- NAT device identification
- Route instability detection & flap alerting
- IX identification via PeeringDB
- MPLS label parsing
- Multi-flow ECMP path enumeration
- ASN, GeoIP, reverse DNS enrichment
**Links:**
- [Crates.io](https://crates.io/crates/ttl)

---

## Monitoring

> Network monitoring: Grafana, Prometheus, LibreNMS, Netbox...

### [latency-monitor](https://github.com/mirceaulinic/latency-monitor)
**Author:** Mircea Ulinic | **Last update:** 2026-01
**What it does:** Latency monitoring system with Grafana dashboard
**Why it's worth it:** Complete project with architecture docs, code, and live demo
**Links:**
- [Article](https://mirceaulinic.net/2026-01-15-latency-monitor/)
- [Architecture](https://lm.mirceaulinic.net/en/latest/arch/)
- [Live Grafana](http://dash.mirceaulinic.net:3000/public-dashboards/858e54dfad8141868a602b22bd8b7138)

---

## Templates & Parsing

> Templates and parsers: ntc-templates, TextFSM, TTP...

### [ntc-templates](https://github.com/networktocode/ntc-templates)
**Author:** Network to Code | **Stars:** 1.5k+
**What it does:** Collection of TextFSM templates for parsing CLI output
**Why it's worth it:** Industry standard, huge template library for Cisco, Arista, Juniper and more

---

## Utilities

> Network utilities: calculators, converters, helpers...

### [ipcalc](https://github.com/kjokjo/ipcalc)
**Author:** Krischan Jodies | **Language:** Perl/CGI
**What it does:** IP subnet calculator — CIDR, netmask, broadcast, host range
**Why it's worth it:** Classic tool, simple and effective. Inspiration for NetDevOps Micro-Tools subnet calc.
**Links:**
- [Live Demo](https://jodies.de/ipcalc)

---

## Security

> Network security: CVE tools, hardening, compliance...

_No entries yet — add the first one!_

---

## AI Tools

> Tools for AI-assisted development and Claude Code workflow

### [ccusage](https://github.com/ryoppippi/ccusage)
**Author:** ryoppippi | **Language:** TypeScript
**What it does:** CLI tool to track Claude Code API usage and costs
**Why it's worth it:** Essential for monitoring Claude Code spending — shows tokens, costs, and usage history per session/day/month
**Best command:** `ccusage monthly --compact` — clean monthly summary

---

## How to add a project

1. Choose the right category
2. Use this template:

```markdown
### [Project Name](link)
**Author:** X | **Stars:** X | **Last update:** YYYY-MM
**What it does:** One sentence description
**Why it's worth it:** Your opinion / use case
**Links:** (optional)
- [Documentation](link)
- [Demo](link)
```

3. Commit with a description of what you're adding

---

_Last updated: 2026-01-24_
