# Breaches (breaches)
An index and topic collection covering data breach intelligence, credential exposure databases, dark-web monitoring, and leak detection APIs. Breach intelligence platforms aggregate compromised credentials, stealer logs, ransomware leak-site posts, underground forum chatter, and dark-web marketplace listings into queryable APIs that security teams use to detect exposure of their organization, employees, customers, executives, and supply-chain partners. This collection indexes services like Have I Been Pwned for consumer breach lookup, Pwned Passwords for k-anonymity credential checks, enterprise breach intelligence platforms (CrowdStrike, Microsoft Defender, SentinelOne, Splunk), credential and identity exposure monitors (Okta, Auth0, 1Password, LastPass, Bitwarden), vulnerability and exposure feeds (NVD, CISA, Qualys, Rapid7, Tanium), and regulatory breach-notification authorities (CISA, FTC, NIST) that publish machine-readable feeds of disclosed breaches and known-exploited vulnerabilities.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Data Breach, Credential Exposure, Dark Web Monitoring, Threat Intelligence, Leak Detection, Breach Notification, Stealer Logs, Pwned Passwords

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Breach Record Schema](https://raw.githubusercontent.com/api-evangelist/breaches/refs/heads/main/json-schema/breaches-breach-record-schema.json)
- [JSONSchema - Exposed Credential Schema](https://raw.githubusercontent.com/api-evangelist/breaches/refs/heads/main/json-schema/breaches-exposed-credential-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/breaches/refs/heads/main/json-ld/breaches-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/breaches/refs/heads/main/vocabulary/breaches-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Email and Account Breach Lookup | APIs like Have I Been Pwned let consumers and security teams check whether an email address, username, or phone number has appeared in known data breaches and stealer log corpora. |
| Pwned Password Checking (K-Anonymity) | The Pwned Passwords API exposes 800+ million breached password hashes through a k-anonymity protocol, letting applications block known-compromised credentials without transmitting full hashes. |
| Dark Web and Underground Forum Monitoring | Enterprise breach intelligence platforms continuously scrape dark-web marketplaces, ransomware leak sites, Telegram channels, and underground forums for mentions of customer data, executives, brands, and credentials. |
| Stealer Log and Credential Exposure Feeds | Modern breach intelligence increasingly centers on infostealer malware logs (RedLine, Raccoon, Vidar, LummaC2) that capture browser-stored credentials, session cookies, and crypto wallets at scale. |
| Ransomware Leak-Site Tracking | Threat intelligence APIs track ransomware group leak sites (LockBit, Cl0p, ALPHV, Akira) to surface newly disclosed victim organizations and stolen data postings as they appear. |
| Vulnerability and Exposure Feeds | Authoritative vulnerability databases (NVD, CISA KEV) and commercial exposure platforms (Qualys, Rapid7, Tanium) expose CVE, CVSS, and known-exploited-vulnerability metadata via API. |
| Regulatory Breach Notification Feeds | Government authorities (FTC, state AGs, EU DPAs, HHS) publish disclosed breach filings; security teams ingest these feeds to track third-party and supply-chain breach exposure. |
| Credential Stuffing Defense | Identity providers (Okta, Auth0) and password managers (1Password, Bitwarden, LastPass) integrate with breach feeds to block re-use of known-compromised passwords and force resets on exposed accounts. |

## Use Cases

| Name | Description |
|------|-------------|
| Employee Credential Exposure Monitoring | Security teams continuously query breach intelligence APIs for corporate email domains to detect employee credentials exposed in third-party breaches and infostealer logs, triggering forced password resets. |
| Customer Account Takeover Prevention | Consumer applications integrate Pwned Passwords and breach lookup APIs at signup and login to block known-compromised credentials and notify customers of exposure. |
| Executive and VIP Protection | Brand and executive protection teams use dark-web monitoring APIs to detect doxxing, leaked personal data, and impersonation targeting C-suite, board members, and high-value employees. |
| Third-Party and Supply-Chain Risk | GRC teams ingest breach-notification feeds and regulatory disclosures via API to track breach incidents at vendors, suppliers, and partners that handle their data. |
| Ransomware Victim Intelligence | Threat intel teams subscribe to ransomware leak-site feeds via API to alert on newly named victims relevant to their industry, supply chain, or geography. |
| Vulnerability Prioritization | Vulnerability management teams combine NVD CVE data, CISA's Known Exploited Vulnerabilities (KEV) catalog, and commercial exposure platforms to prioritize patching based on breach exploitation evidence. |
| Regulatory Breach Disclosure Compliance | Privacy and legal teams query FTC, state AG, and EU DPA breach-notification APIs to track required disclosures and benchmark their own incident response. |
| AI Agent Breach Triage | AI agents wired to breach intelligence APIs autonomously enrich security alerts with exposure context, correlate stolen credentials with active sessions, and draft incident-response runbooks. |

## Integrations

| Name | Description |
|------|-------------|
| Have I Been Pwned | The canonical consumer breach-lookup service with 13+ billion breached accounts and 800+ million pwned passwords accessible via free and paid API tiers. |
| CrowdStrike Falcon Intelligence | Enterprise threat intelligence platform with adversary tracking, dark-web monitoring, and breach exposure feeds delivered via the Falcon API. |
| Microsoft Defender Threat Intelligence | Threat intelligence and breach exposure feeds integrated across Microsoft Defender, Sentinel, and Graph Security APIs. |
| Splunk Enterprise Security | SIEM platform that ingests breach intelligence and credential exposure feeds for correlation against authentication and access logs. |
| CISA Known Exploited Vulnerabilities (KEV) | Authoritative catalog of CVEs with evidence of active exploitation, published by the US Cybersecurity and Infrastructure Security Agency as a machine-readable feed. |
| NVD CVE API | The National Vulnerability Database REST API exposing CVE records, CVSS scores, CPE mappings, and CWE classifications used as the foundation of breach root-cause analysis. |
| Okta and Auth0 | Identity platforms that integrate breach-password feeds to block known-compromised credentials and trigger step-up authentication on suspected account takeover. |
| 1Password Watchtower | Consumer and enterprise password manager that surfaces breach exposure for stored credentials via integration with Have I Been Pwned and proprietary feeds. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Breach Record Schema](json-schema/breaches-breach-record-schema.json)
- [Exposed Credential Schema](json-schema/breaches-exposed-credential-schema.json)

### JSON Structure

- [Breach Record Structure](json-structure/breaches-breach-record-structure.json)
- [Exposed Credential Structure](json-structure/breaches-exposed-credential-structure.json)

### JSON-LD

- [Breaches Context](json-ld/breaches-context.jsonld)

## Vocabulary

- [Breaches Vocabulary](vocabulary/breaches-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 7 actions, 3 workflows, and 3 personas across breach intelligence, credential exposure, and dark-web monitoring

## Network

This index references the following breach intelligence, credential exposure, and threat intelligence repositories:

- [Have I Been Pwned](https://github.com/api-evangelist/have-i-been-pwned)
- [CrowdStrike](https://github.com/api-evangelist/crowdstrike)
- [Microsoft Defender](https://github.com/api-evangelist/microsoft-defender)
- [Microsoft Defender for Cloud](https://github.com/api-evangelist/microsoft-defender-for-cloud)
- [Microsoft Sentinel](https://github.com/api-evangelist/microsoft-sentinel)
- [Microsoft Graph](https://github.com/api-evangelist/microsoft-graph)
- [SentinelOne](https://github.com/api-evangelist/sentinelone)
- [Sophos](https://github.com/api-evangelist/sophos)
- [Symantec](https://github.com/api-evangelist/symantec)
- [Trellix](https://github.com/api-evangelist/trellix)
- [McAfee](https://github.com/api-evangelist/mcafee)
- [Splunk](https://github.com/api-evangelist/splunk)
- [Amazon Detective](https://github.com/api-evangelist/amazon-detective)
- [Amazon GuardDuty](https://github.com/api-evangelist/amazon-guardduty)
- [Amazon Macie](https://github.com/api-evangelist/amazon-macie)
- [Google Cloud Security Command Center](https://github.com/api-evangelist/google-cloud-security-command-center)
- [Google Safe Browsing](https://github.com/api-evangelist/google-safe-browsing)
- [Qualys](https://github.com/api-evangelist/qualys)
- [Rapid7](https://github.com/api-evangelist/rapid7)
- [Tanium](https://github.com/api-evangelist/tanium)
- [Sumo Logic](https://github.com/api-evangelist/sumo-logic)
- [Cloudflare](https://github.com/api-evangelist/cloudflare-com)
- [Fortinet](https://github.com/api-evangelist/fortinet)
- [Check Point](https://github.com/api-evangelist/check-point)
- [Palo Alto Networks](https://github.com/api-evangelist/palo-alto-networks)
- [BeyondTrust](https://github.com/api-evangelist/beyondtrust)
- [CyberArk](https://github.com/api-evangelist/cyberark)
- [Okta](https://github.com/api-evangelist/okta)
- [Auth0](https://github.com/api-evangelist/auth0)
- [1Password](https://github.com/api-evangelist/1password)
- [LastPass](https://github.com/api-evangelist/lastpass)
- [Bitwarden](https://github.com/api-evangelist/bitwarden)
- [NVD](https://github.com/api-evangelist/nvd)
- [Cybersecurity and Infrastructure Security Agency](https://github.com/api-evangelist/cybersecurity-and-infrastructure-security-agency)
- [Federal Trade Commission](https://github.com/api-evangelist/federal-trade-commission)
- [NIST](https://github.com/api-evangelist/nist)
- [Varonis](https://github.com/api-evangelist/varonis)
- [Zscaler](https://github.com/api-evangelist/zscaler)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
