# Awesome-Application-Security-Posture-Management-ASPM

# Awesome-Application-Security-Posture-Management-ASPM

# Awesome-Application-Security-Posture-Management-ASPM

**Top Application Security Posture Management ASPM (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Risk Correlation, Code-to-Runtime Context, Vulnerability Prioritization & Developer Remediation Workflows*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Application Security Posture Management (ASPM)**. These tools enable security teams to aggregate findings from disparate scanners, correlate code and runtime context, prioritize exploitable risks, and drive remediation through developer workflows—from fully managed enterprise platforms with agentic AI and deep code analysis to self-hosted dashboards that unify open-source scanners and provide compliance mapping.



**Examples** include CrowdStrike Falcon ASPM, Apiiro, OX Security, ArmorCode, Mend.io, Legit Security, Snyk AppRisk, Kondukto, and Jit (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted ASPM, vulnerability aggregation, and open security infrastructure. **Critical note**: The open-source ASPM landscape is nascent—**Foxnode ASPM** is the most complete aggregation dashboard, but it does not scan on its own and lacks the code-to-runtime correlation depth of Apiiro or the agentic remediation of ArmorCode. No open-source project matches CrowdStrike's unified graph or OX's code projection technology.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The dedicated Application Security Posture Management (ASPM) market is estimated at **$1.8B to $2.55B** in 2025–2026, growing rapidly at an annual rate exceeding 20% to 25% as organizations combat alert fatigue, scanner sprawl, and software supply chain compliance requirements. The sector remains **moderately fragmented**: while cloud security titans (e.g., CrowdStrike, Snyk, Invicti) are aggressively acquiring or bundling posture engines, specialized pure-play innovators (e.g., Apiiro, OX Security, ArmorCode) maintain strong defensibility through proprietary code-to-runtime graph correlation and agentic AI remediation rather than consolidating into a single winner-take-all outcome.

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Trial Limits | Key Capabilities & Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **[CrowdStrike Falcon ASPM](https://www.crowdstrike.com/en-us/platform/cloud-security/aspm/)** | **~$250B+ Market Cap** / ~$4.8B ARR | **£1,115/service/yr** (~$1,450/yr, 100 services MOQ on G-Cloud) or metered Falcon Flex platform contract | **15-day free trial** of Falcon Cloud Security (no credit card required) or 30-day sandbox Test Drive | Real-time cloud application mapping (microservices, APIs, data flows) via Bionic tech. Integrates runtime analysis directly into SOC detection workflows, monitoring shadow AI and reachability. |
| **[Snyk AppRisk](https://snyk.io/product/apprisk/)** | **~$3.7B–$7.4B Valuation** / ~$309M ARR | **$25/contributing dev/month** (Team tier, 5–10 devs); AppRisk platform module requires Enterprise custom plan | **Free forever tier**: up to 5 projects, 100 SAST tests/mo, 200–400 SCA tests/mo, 300 IaC tests/mo, 100 container tests/mo; or 14-day Enterprise trial | Asset discovery and posture visibility layered on Snyk. AppRisk Essentials covers discovery & posture; AppRisk Pro introduces runtime insights, reachability, and third-party scanner orchestration. |
| **[Kondukto](https://kondukto.io/)** *(Invicti)* | **~$625M Parent Valuation** (Invicti) / ~$40M–$64M ARR | **~$6,000–$7,000/yr** (Invicti entry tier for limited targets); enterprise ASPM custom quoted by asset count | **7-day free trial** of Invicti (up to 5 targets) or scheduled proof-of-concept for Kondukto ASPM platform | Orchestrates & normalizes findings across SDLC. Integrated with Invicti's runtime-validated DAST for proof-based vulnerability prioritization, eliminating false positives. |
| **[Apiiro](https://apiiro.com/)** | **~$500M–$600M Valuation** / ~$135M Total Funding | **~$55,000/yr** median enterprise starting contract (priced per Agent Compute Unit / repo scope) | **14-day free trial** with full platform evaluation and application inventory build | Deep Code Analysis (DCA) mapping runtime traffic to exact API controllers down to file and line level. AutoFix Agent automates developer remediation across Fortune 500 codebases. |
| **[OX Security](https://www.ox.security/)** | **~$250M–$500M Valuation** / ~$94M Total Funding ($10M+ ARR) | **~$350/month** entry-level baseline; ~$1,000/dev/yr ($100k/yr for 100 devs on AWS Marketplace) | **14-day free evaluation** via 'Start Free' trial registration or custom enterprise PoC | Active ASPM leveraging Code Projection and Pipeline Bill of Materials (PBOM). Unifies 10 native scanners and 120+ third-party tools into evidence-backed risk analysis. |
| **[Mend.io](https://www.mend.io/)** | **~$250M–$500M Est. Valuation** / ~$121M Total Funding | **$1,000/contributing dev/year** (Mend AppSec); $300/dev/yr (AI Security); $250/dev/yr (Renovate Enterprise) | **Free forever plan** for Open Source maintainers via Mend Renovate Community / Mend Bolt (free scanner extension) | Full-stack posture visibility across code packages, AI models, and agents (SBOM/AI-BOM). Offers continuous red-teaming simulations and in-application runtime protection. |
| **[ArmorCode](https://www.armorcode.com/)** | **~$200M–$277M Valuation** / ~$81M Total Funding | **~$4,500/year** (AWS Marketplace Bronze tier entry); mid-market & enterprise custom quoted | **14-day guided proof-of-concept (PoC)** / live sandbox environment upon demo verification | Powered by 40B+ findings and 320+ tool integrations. Features Anya, an agentic AI security champion with Model Context Protocol (MCP) server support for automated Jira and CI/CD actions. |
| **[Legit Security](https://www.legitsecurity.com/)** | **~$100M–$250M Valuation** / ~$70M–$80M Total Funding | **~$15,000–$25,000/yr** estimated enterprise entry contract (AWS Marketplace SaaS Contract by contributor scope) | **14-day free trial** for secrets detection / AI code capabilities; free open-source GitHub/GitLab posture tool (Legitify) | AI-native ASPM spanning code-to-cloud discovery, automated risk scoring, and AI-generated PR fixes. Strong focus on governance of AI coding assistants and supply chain integrity. |
| **[Jit](https://www.jit.io/)** *(Torq)* | **~$70M Acquisition Valuation** (Torq) / ~$46.7M Total Funding | **$50/contributing dev/month** (Growth tier); custom enterprise contracts via AWS Marketplace | **Free forever tier**: 1 developer seat on managed infrastructure with core SAST, SCA, secrets, and IaC PR scans | Developer-first 'shift left' ASPM integrating orchestration into pull requests. Built-in scanners and Company Context Graph align security plans to automated remediation. |

## Open-Source GitHub Projects



- **[Foxnode ASPM](https://github.com/valinorintelligence/foxnode-aspm)**

  **Open-source Application Security Posture Management platform** (license per repo) — **the most complete open-source ASPM dashboard** found in this research. **Features**: **16+ security tool parsers** covering SAST (Semgrep, SonarQube, Bandit), DAST (OWASP ZAP, Nuclei), SCA (Trivy, Snyk, Dependency-Check), cloud (Prowler), IaC (Checkov, tfsec), secrets (Gitleaks, TruffleHog), and universal SARIF. **AI Finding Triage** with false positive detection, auto-grouping, and contextual scoring. **Security Scorecard** (A–F) per product with trend tracking. **Compliance Mapping** to OWASP Top 10, PCI-DSS, SOC 2, CIS Benchmarks, ISO 27001. **Attack Path Analysis** visualizing exploitable chains with blast radius. **LLM/AI Security Scanner** detecting prompt injection and data poisoning (OWASP LLM Top 10). **SBOM & supply chain** tracking. **AI Remediation Copilot**. Jira bidirectional sync, Slack notifications, RBAC, REST API, Docker Compose deployment . **Tech stack**: Python (FastAPI), React, PostgreSQL, Redis. **Deploy**: Docker Compose (one command). **Trade-off**: **Aggregation platform, not a scanner**—it does not perform scanning itself; you must run and feed results from supported scanners. No code-to-runtime correlation or exploitability proof like Apiiro or OX. Newer project with growing but limited community validation. **Best for**: security teams wanting a centralized open-source ASPM dashboard to aggregate findings from multiple scanners, with AI-assisted triage and compliance mapping—without commercial ASPM pricing.



- **[Semgrep](https://github.com/semgrep/semgrep)**

  **Lightweight, fast SAST tool** (LGPL-2.1) — **the most widely adopted open-source SAST engine**, commonly used as a **scanner feeding into ASPM platforms** (including Foxnode). **Features**: YAML-based rules that mirror code patterns; community rule registry covering OWASP Top 10 across 30+ languages; runs locally or in CI. **Tech stack**: OCaml, Python. **Deploy**: CLI, CI/CD, or Semgrep Cloud. **Trade-off**: **Scanner only**—no aggregation, prioritization across tools, or posture management. Commercial Semgrep adds cross-file analysis and AI triage. **Best for**: teams needing a fast, customizable SAST scanner to feed into an ASPM aggregation layer.



- **[CodeQL](https://github.com/github/codeql)**

  **Semantic code analysis engine** (MIT for queries; free for public repos) — **the most powerful open-source SAST for deep data-flow analysis**, powering GitHub Advanced Security. **Features**: Treats code as a database queried with QL; models data flow and taint tracking across functions; free for public repos. **Tech stack**: QL, C++. **Deploy**: GitHub Actions, CLI. **Trade-off**: **Free only for public repos**—private use requires GitHub Advanced Security. Steeper learning curve than Semgrep. **Best for**: GitHub organizations already on Advanced Security wanting deep semantic analysis feeding into ASPM.



- **[Trivy](https://github.com/aquasecurity/trivy)**

  **Comprehensive open-source scanner** (Apache 2.0) — **the most widely used multi-purpose scanner** for containers, filesystems, repositories, and SBOMs. **Features**: Vulnerability scanning (OS packages, language dependencies), misconfiguration detection (IaC), secrets scanning, SBOM generation (CycloneDX, SPDX). Used as the vulnerability database source by TRUSCA and supported as an SCA parser by Foxnode. **Tech stack**: Go. **Deploy**: CLI, CI/CD, Docker. **Trade-off**: **Scanner only**—no aggregation or posture dashboard. **Best for**: teams needing a single scanner covering containers, dependencies, IaC, and secrets to feed into ASPM.



### Additional Strong Open-Source Options



- **TRUSCA** — Self-hosted SCA portal with SBOM management and license compliance (Apache 2.0). Seven-state VEX triage, component approval workflows, 30+ ecosystems. **Note**: SCA-only, not full ASPM—but essential for open-source supply chain governance. **Best for**: organizations needing deep SCA with SBOM and license compliance as part of their ASPM stack.

- **Scanr CLI** — Lightweight SCA CLI for Node.js, Python, and Rust (npm). CVE/OSV lookup, CI policy checks, SBOM generation. **Note**: Narrow ecosystem coverage; CLI-only. **Best for**: developers wanting fast, scriptable SCA with policy gates in CI.

- **CloudRec** — Multi-cloud CSPM platform (Apache 2.0). OPA policy engine, CloudRec Lite for local checks. **Note**: Cloud posture, not application security—complements ASPM for infrastructure risk. **Best for**: teams needing cloud posture management alongside AppSec.



**Frameworks for building custom systems**: Combine **Foxnode ASPM** as the aggregation and triage dashboard with **Semgrep** and **CodeQL** for SAST, **Trivy** or **TRUSCA** for SCA and container scanning, and **CloudRec** for cloud posture—creating an open-source ASPM stack. **None of these provide code-to-runtime correlation or exploitability proof** like Apiiro or OX Security; those require commercial platforms or significant custom engineering.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- ASPM platforms handling vulnerability data and code intelligence must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for security findings.

- **The "unified ASPM platform" vs. "aggregation dashboard" vs. "individual scanner" distinction is critical.** **CrowdStrike, Apiiro, OX, ArmorCode, Mend.io, Legit, Snyk AppRisk, Kondukto, and Jit** are **ASPM platforms**—they aggregate, correlate, prioritize, and often remediate across the SDLC. **Foxnode ASPM** is an **aggregation dashboard**—it unifies findings from 16+ scanners but does not scan itself or provide code-to-runtime correlation . **Semgrep, CodeQL, and Trivy** are **individual scanners**—they find issues but do not aggregate or prioritize across categories. **Choose based on whether you need a platform, a dashboard, or specific scanning capabilities.**

- **Apiiro and OX Security have the most differentiated technical approaches.** Apiiro's **runtime API endpoint matching** to the exact code line is materially more precise than competitors that match only to host or repository . OX's **Code Projection** and **PBOM** extend proof-based prioritization to build pipelines . **These are genuine differentiators** that open-source tools do not replicate.

- **ArmorCode has the most mature agentic AI in ASPM** with Anya, 40B+ findings, and 320+ integrations . **CrowdStrike's differentiation is runtime integration**—embedding ASPM findings into SOC detections for application context during incident response . **Mend.io uniquely covers AI/LLM security** alongside traditional AppSec . **Choose based on whether you prioritize agentic AI, runtime correlation, or AI component security.**

- **Foxnode ASPM is the only meaningful open-source ASPM dashboard** in this list, but it is **an aggregator, not a scanner**—it requires you to run Semgrep, Trivy, and other tools and feed results into it . **It does not provide code-to-runtime correlation, exploitability proof, or agentic remediation.** For teams wanting a Wiz-like ASPM experience without commercial pricing, it is the closest open-source option—but expectations should be calibrated.

- **Kondukto was acquired by Invicti in August 2025** . Its standalone availability may change; it is now part of Invicti's ASPM + DAST offering. **Verify current product status before evaluating.**

- **Pricing opacity is universal across commercial ASPM vendors.** CrowdStrike, Apiiro, OX, ArmorCode, Mend.io, Legit, Snyk AppRisk (enterprise), Kondukto/Invicti, and Jit (enterprise) require sales contact. **Validate with direct vendor conversations against your repository count, scanner sprawl, and remediation workflow needs.**

- Self-hosted open-source solutions require proper setup, scanner execution orchestration, API credentials for integrations, and ongoing maintenance. **Security findings contain sensitive vulnerability data**—ensure your deployment meets your organization's security standards before aggregating production scan results.



---



**Made for security engineers, AppSec teams, and organizations building transparent application security posture solutions.**

Let's make ASPM more open, data-driven, and developer-friendly.
