# Awesome-Data-Loss-Prevention

## Top Data Loss Prevention (Cloud DLP) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Cloud & Endpoint DLP, Sensitive Data Detection, Policy Enforcement, SaaS/GenAI Protection & Exfiltration Prevention*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Loss Prevention (Cloud DLP)**. These systems discover, classify, monitor, and block sensitive data leaving approved channels—across cloud apps, email, endpoints, web, and increasingly GenAI interfaces.



**Examples** include Microsoft Purview DLP, Google Cloud DLP, Netskope DLP, Symantec DLP, Forcepoint DLP, Proofpoint DLP, Digital Guardian, Varonis, GTB Technologies, and Trellix DLP (the category leaders).



**Open-source emphasis**: Full enterprise DLP (inline blocking, multi-channel policy, endpoint agents) is almost entirely commercial. Strong open building blocks exist for **PII detection and redaction** (Presidio) and limited historical community DLP projects. This section expands those while remaining realistic about the commercial gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Microsoft Purview DLP](https://www.microsoft.com/en-us/security/business/information-protection/microsoft-purview-data-loss-prevention)**  

  Native Microsoft 365 and cloud DLP with sensitivity labels, policy enforcement across Exchange, SharePoint, Teams, endpoints, and growing GenAI coverage.



- **[Google Cloud DLP](https://cloud.google.com/sensitive-data-protection)**  

  Google Cloud Sensitive Data Protection (formerly Cloud DLP) for discovering, classifying, and de-identifying sensitive data in Google Cloud and pipelines.



- **[Netskope DLP](https://www.netskope.com/)**  

  Cloud-native DLP within the Netskope SASE/SSE platform—strong on SaaS, web, and GenAI data protection with inline controls.



- **[Symantec DLP (Broadcom)](https://www.broadcom.com/products/cybersecurity/information-protection)**  

  Established enterprise DLP suite covering endpoint, network, cloud, and discovery use cases.



- **[Forcepoint DLP](https://www.forcepoint.com/product/dlp-data-loss-prevention)**  

  Hybrid and cloud DLP with behavioral analytics, strong policy controls, and coverage across channels.



- **[Proofpoint DLP](https://www.proofpoint.com/)**  

  DLP capabilities focused on email, cloud, and people-centric threat and data protection.



- **[Digital Guardian](https://www.digitalguardian.com/)**  

  Data protection and DLP platform emphasizing endpoint visibility and control of sensitive data movement.



- **[Varonis](https://www.varonis.com/)**  

  Data security platform with classification, permissions, and controls that complement DLP for unstructured data.



- **[GTB Technologies](https://gttb.com/)**  

  DLP and data protection solutions for discovering and controlling sensitive information.



- **[Trellix DLP](https://www.trellix.com/)**  

  Data loss prevention offerings within the Trellix (former McAfee enterprise) security portfolio.



## Open-Source GitHub Projects

- **[Presidio](https://github.com/data-privacy-stack/presidio)**  

  Leading open-source framework for detecting, redacting, masking, and anonymizing PII in text, images, and structured data—core building block for DLP-style controls.



- **[ceil-dlp and LLM guardrail projects](https://github.com/)**  

  Open plugins that apply Presidio-style PII/secret protection to LLM requests and agent workflows.



- **[Historical / community DLP projects (OpenDLP, MyDLP-style)](https://github.com/)**  

  Older open efforts focused on data-at-rest scanning and basic network/endpoint monitoring (limited modern maintenance).



- **[Regex and content inspection libraries](https://github.com/)**  

  Open pattern engines and scanners used to detect credit cards, SSNs, secrets, and other sensitive tokens.



- **[Network IDS / content-aware open tools](https://github.com/)**  

  Projects such as Suricata/Snort with custom rules that can flag sensitive data patterns in transit (not full DLP).



- **[Document redaction open tools](https://github.com/)**  

  Libraries that combine OCR and PII detection to redact sensitive content in files.



- **[Secrets scanning open tools](https://github.com/)**  

  Gitleaks, TruffleHog, and similar projects for preventing credential leakage (adjacent to DLP).



- **[Documentation and Presidio playbooks](https://microsoft.github.io/presidio/)**  

  Guides for deploying PII detection/redaction pipelines and integrating them into applications and gateways.



- **[Self-hosted detection prototypes](https://github.com/)**  

  Patterns combining Presidio + proxies/gateways for limited-scope data protection before commercial DLP.



- **[Policy template and classification open resources](https://github.com/)**  

  Shared sensitive-data taxonomies and example policies for internal DLP program design.



### Additional Strong Open-Source Options

- Using **Presidio** for application-level and pipeline PII detection and redaction.

- Scanning repos and configs with open secrets detectors.

- Applying content inspection at gateways where feasible.

- Accepting that enterprise multi-channel DLP (endpoint agents, inline SaaS/web blocking, email DLP, GenAI controls, policy management, and incident workflows) still requires commercial platforms (Purview, Netskope, Forcepoint, Symantec, Proofpoint, Digital Guardian, etc.).

- Focusing open-source efforts on detection accuracy and protecting data before it reaches external channels.



**Frameworks for building custom systems**: Detect with Presidio → redact or block in app/API gateways → scan code and storage with open tools → escalate residual risk to commercial DLP for broad coverage. Suitable for application owners and small estates. Most enterprises run commercial Cloud/SASE DLP for comprehensive protection.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- DLP involves monitoring and potentially blocking user activity. Open-source tools are not substitutes for regulated enterprise DLP programs. False negatives leave data at risk; false positives disrupt work. This list is not security or legal advice.



---

**Made for security, privacy, and data protection teams.**

Let's keep sensitive data from leaving approved channels—with as much openness as practical.
