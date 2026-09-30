# Awesome-Digital-Risk-Protection

# Top Digital Risk Protection (DRP) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Brand Protection, Dark Web Monitoring, Executive Digital Risk, Phishing Domain Detection & External Threat Intelligence*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Risk Protection (DRP)**. These systems monitor the open, deep, and dark web for brand abuse, leaked credentials, impersonation, and threats targeting executives and assets.

**Examples** include ZeroFox, Constella Intelligence, Recorded Future, SOCRadar, Group-IB, DarkOwl, Cyble, Flashpoint, IntSights (Rapid7 Threat Command), CybelAngel, Proofpoint DRP, Flare Systems, Digital Shadows (ReliaQuest), and Mandiant Advantage (the category leaders).

**Open-source emphasis**: Full commercial DRP platforms dominate. Open tooling covers **typosquatting detection**, **CT log monitoring**, **OSINT frameworks**, and **leak/paste monitoring** building blocks. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ZeroFox, Recorded Future, Flashpoint, Mandiant Advantage](https://www.zerofox.com/)**  
  Broad digital risk and threat intelligence platforms spanning brand, social, dark web, and geopolitical risk.

- **[SOCRadar, Cyble, Group-IB, Constella, DarkOwl](https://socradar.io/)**  
  DRP and cyber threat intelligence specialists with strong dark-web and credential-leak coverage.

- **[Rapid7 Threat Command (IntSights), Proofpoint DRP, CybelAngel, Flare, Digital Shadows](https://www.rapid7.com/)**  
  Enterprise DRP modules integrated with security operations and email/brand protection suites.

- **[Other commercial DRP platforms](https://www.zerofox.com/)**  
  Additional external attack-surface and executive-protection monitoring services.

## Open-Source GitHub Projects

- **[OpenBPL](https://github.com/openbpl/openbpl)**  
  Open-source brand protection toolkit—Certificate Transparency monitoring for lookalike domains and impersonation tripwires.

- **[dnstwist](https://github.com/elceef/dnstwist)**  
  Classic open tool for generating and checking domain permutations (typosquatting, homoglyphs) against your brand.

- **[SpiderFoot](https://github.com/smicallef/spiderfoot)**  
  Open-source OSINT automation—hundreds of modules for domain, leak, social, and infrastructure reconnaissance.

- **[AIL Framework](https://github.com/ail-project/ail-framework)**  
  Open Analysis Information Leak framework—crawl and analyze pastes, leaks, and unstructured sources for sensitive data.

- **[Phishing catchers / CT monitors](https://github.com/x0rz/phishing_catcher)**  
  Open Certificate Transparency consumers that alert on suspicious certificate issuances matching brand keywords.

- **[theHarvester & recon-ng](https://github.com/laramies/theHarvester)**  
  Open OSINT gathering tools for emails, subdomains, and public footprint expansion.

- **[ThreatForge & community CTI platforms](https://github.com/search?q=digital+risk+protection+OR+brand+protection+open+source)**  
  Emerging open CTI/DRP-oriented projects for threat monitoring and automation.

- **[Have I Been Pwned API patterns & local leak checkers](https://github.com/search?q=hibp+OR+credential+leak+monitor+open+source)**  
  Community tooling around public breach datasets for credential exposure workflows (use lawfully).

### Additional Strong Open-Source Options

- **Domain impersonation**: OpenBPL + dnstwist + CT phishing catchers.
- **OSINT automation**: SpiderFoot for broad external footprint scans.
- **Leak analysis**: AIL Framework for paste and unstructured leak triage.
- **Composable stacks**: CT alerts → domain screenshot/classification → ticket; SpiderFoot scheduled scans → SIEM.
- Commercial DRP still leads in dark-web coverage, takedown networks, and 24/7 analyst support.

**Frameworks for building custom systems**:  
**dnstwist** + **OpenBPL**/CT monitors for brand domains; **SpiderFoot** + **AIL** for OSINT and leak signals.  
Commercial DRP (ZeroFox, Recorded Future, SOCRadar, Group-IB, etc.) provides continuous dark-web and social coverage.  
Security teams often run open domain/CT monitoring in-house and buy commercial DRP for deeper sources. Fully open DRP is partial—strong on public web, limited on closed dark-web markets.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Only monitor assets you own or are authorized to protect. Accessing or scraping certain dark-web sources may be illegal or violate terms of service. Coordinate takedowns through proper legal and registrar channels.
- Open-source tools offer transparency but limited source coverage. Commercial DRP platforms shift collection and analyst workload to the vendor. Neither replaces solid external attack-surface management and incident response.

---

**Made for threat intel teams, brand protection leads, and security operations.**  
Let's expand open brand and OSINT monitoring while recognizing the dark-web depth and takedown reach that leading commercial DRP platforms deliver.
