# Cybersecurity Labs & Investigations

> A hands-on defensive security portfolio focused on SOC analysis, log investigation, Linux administration, and security automation.

This repository documents practical cybersecurity work as I build toward an entry-level **Blue Team / SOC Analyst** role. Each project is designed to show not only the result, but also the investigation process, evidence, assumptions, and lessons learned.

## Portfolio Map

| Area | What it demonstrates | Projects |
|---|---|---|
| SOC & SIEM investigations | Alert triage, timeline building, evidence analysis, and incident reporting | [SOC Labs](soc-labs/) |
| Linux security | Service management, command-line investigation, and system administration | [Linux Services](linux/services/) |
| Security automation | Python tools, log analysis, simulations, and scripting fundamentals | [Python Projects](python-projects/) |
| Network analysis | Packet inspection, traffic baselining, and protocol analysis | [Network Analysis](network-analysis/) |
| Windows telemetry | Event Log analysis, authentication activity, and endpoint investigation | [Windows Event Logs](windows-event-logs/) |
| Phishing analysis | Header analysis, indicator extraction, and safe investigation workflows | [Phishing Analysis](phishing-analysis/) |
| Detection engineering | Detection logic, testing notes, and false-positive analysis | [Detection Labs](detection-labs/) |

## Featured Work

### SOC investigations

- [HTB SOC Skills Assessment](soc-labs/HTB%20SOC%20Skills%20Assessment/) — practical SOC investigation exercise.
- [Elastic SIEM Investigation](soc-labs/htb-elastic-siem-investigation/) — alert review and evidence-driven investigation using Elastic.

### Security tooling

The [Python Projects](python-projects/) section includes:

- IP checking and port-scanning utilities
- Log-analysis and password-auditing tools
- SOC analyst and login-firewall simulators
- A cybersecurity incident tracker
- Security fundamentals study exercises

### Linux administration

- [Managing Services](linux/services/managing-services.md) — practical service-management notes and `systemctl` command usage.

## Lab Write-up Standard

Each investigation should aim to include:

1. **Objective** — the question or skill being tested.
2. **Environment** — tools, operating systems, data sources, and lab platform.
3. **Method** — reproducible commands and investigation steps.
4. **Evidence** — relevant logs, screenshots, indicators, or query results.
5. **Findings** — what happened and why the evidence supports that conclusion.
6. **Lessons learned** — improvements, limitations, and next steps.

## Skills Demonstrated

- SOC alert triage and investigation
- Windows Event Log and SIEM analysis
- Linux service administration
- Network and protocol fundamentals
- Python security scripting
- Detection thinking and incident documentation
- Clear, reproducible technical communication

## Ethics & Safety

All exercises are performed in personal, authorised, or purpose-built training environments. Sensitive information, credentials, and unauthorised target data are not included.

## Roadmap

- Add packet-capture investigations using Wireshark
- Publish Windows authentication and PowerShell event-log labs
- Document a complete phishing-email investigation
- Build and test detection rules with expected and false-positive cases
- Standardise screenshots, evidence tables, and investigation summaries
