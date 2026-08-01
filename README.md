# CyberDefenders Blue Team Labs

My write-ups from CyberDefenders' Blue Team labs, solved using Wireshark. Each lab is a real network forensics investigation — starting from a PCAP file and ending with a full reconstruction of the attack.

📄 **[Full combined PDF report](./BlueTeam_Labs_Report.pdf)** — includes every lab write-up, evidence screenshots, and a complete Wireshark filter/command reference.

---

## Labs Completed

| # | Lab | Category | Key Technique | Tool |
|---|-----|----------|----------------|------|
| 1 | JetBrains | Network Forensics | TeamCity RCE (CVE-2024-27198), webshell upload, container escape | Wireshark |
| 2 | RetailBreach | Network Forensics | Directory brute-forcing, Stored XSS, session hijacking, path traversal | Wireshark |
| 3 | PoisonedCredentials | Network Forensics | LLMNR/NBT-NS poisoning, credential theft | Wireshark |

---

## What's Inside Each Write-Up

- The original incident scenario, explained in plain language
- A step-by-step walkthrough of the investigation, with annotated screenshots
- The final answers submitted for each lab's questions
- Every Wireshark filter and menu action used, with an explanation of why

---

## About

This is a personal learning log while working through **CyberDefenders' SOC Analyst Tier 1 track**. All lab scenarios and data belong to [CyberDefenders](https://cyberdefenders.org/) — this repo only documents my own investigation process and findings.

**Tools used:** Wireshark

**Skills practiced:** Network traffic analysis, HTTP request/response inspection, credential/session token extraction, timeline reconstruction, MITRE ATT&CK technique mapping, LLMNR/NBT-NS poisoning analysis.

---

⭐ If this is useful for your own blue-team learning, feel free to star the repo.
