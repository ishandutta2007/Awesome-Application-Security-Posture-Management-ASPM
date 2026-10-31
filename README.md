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
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[CrowdStrike Falcon ASPM](https://www.crowdstrike.com/en-us/platform/cloud-security/aspm/)**
  **Application security posture management integrated with Falcon Cloud Security** (built on the Bionic acquisition). Delivers a **real-time map of cloud applications**—microservices, APIs, data flows, dependencies—without outdated diagrams. Uniquely analyzes **application code in runtime** to surface exploitable vulnerabilities, not just vulnerable packages. Detects **shadow AI**, monitors external AI services, and identifies breach paths combining application weaknesses with AI misconfigurations. ASPM findings are **embedded directly into runtime detections**, giving SOC teams application context for faster triage. Named a **Customers' Choice in 2026 Gartner Peer Insights for ASPM Tools** . **Pricing**: Quote-only; enterprise contracts. **Free tier**: None. **Best for**: CrowdStrike customers wanting ASPM tightly integrated with runtime protection and cross-domain threat correlation—**trade-off**: entry cost and ecosystem lock-in.

- **[Apiiro](https://apiiro.com/)**
  **Agentic Application Security Platform** named a **Leader in IDC MarketScape for ASPM 2025**. Core differentiator: **Deep Code Analysis (DCA)** engine that builds an extended SBOM (XBOM) and enables **true runtime API endpoint matching**—mapping runtime traffic to the **exact API controller in code**, including file, line, and code owner. This is materially more precise than competitors that match only to host, service, or repository . The **AutoFix Agent** automates remediation. Fortune 500 customers include USAA, TIAA, BlackRock, Bloomberg, SoFi, and Shell. **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises needing the most precise code-to-runtime correlation and automated remediation—**trade-off**: enterprise pricing and implementation commitment.

- **[OX Security](https://www.ox.security/)**
  **Active ASPM platform** named a **Leader in IDC MarketScape for ASPM 2025** . Key technologies: **Code Projection** traces runtime behavior back to source code to prove reachability and exploitability; **PBOM (Pipeline Bill of Materials)** extends SBOM coverage to build pipelines; **AppSec Data Fabric** normalizes results from 10 native scanners and **120+ third-party tools** into a single evidence-backed finding. Claims **92% reduction in false positives**. **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises wanting evidence-based prioritization with full supply chain (code + pipeline) visibility—**trade-off**: complexity and enterprise-only positioning.

- **[ArmorCode](https://www.armorcode.com/)**
  **AI-powered ASPM platform** with **Anya, agentic AI virtual security champion**. Built on **40B+ findings** and **320+ integrations** . **Anya** provides conversational security queries, AI-driven remediation with code-specific guidance, and automated actions via **MCP server** (Jira ticket creation, incident response, pipeline triggers). Claims **80% reduction in MTTR** with AI remediation . Strong **software supply chain security (SSCS)** with composite SBOMs and CRA compliance support. **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises wanting the most mature agentic AI in ASPM with broad tool integration and compliance focus—**trade-off**: enterprise scale and pricing.

- **[Mend.io](https://www.mend.io/)**
  **Unified AppSec and AI security platform** with **full-stack visibility** across packages, AI models, agents, and system prompts (SBOM/AI-BOM). **Continuous AI behavioral testing** with 1,000+ concurrent red-team simulations per build. **Runtime in-application protection** blocks unsafe behavior in production (80% MTTR reduction). Strong **compliance evidence layer** for EU AI Act, Executive Order 14028, and Cyber Resilience Act . **Pricing**: Quote-only. **Free tier**: Limited for open source. **Best for**: organizations needing to secure both traditional code and embedded AI/LLM components with runtime defense—**trade-off**: broader scope than pure ASPM.

- **[Legit Security](https://www.legitsecurity.com/)**
  **AI-native ASPM platform** with AI across the **entire lifecycle**: discovery (code-to-cloud correlation, malicious model detection), prioritization (AI-assisted risk scoring with explainability), and remediation (AI-generated fix suggestions in PR checks). Explicit focus on **securing AI-generated code** and governing AI development. Users control when/where AI is applied based on policy . **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations adopting AI coding assistants that need ASPM tuned for AI-generated code risks—**trade-off**: newer vendor than CrowdStrike or Apiiro.

- **[Snyk AppRisk](https://snyk.io/product/apprisk/)**
  **ASPM offering within the Snyk platform**. **Essentials**: automated app asset discovery, tailored security controls, risk-based prioritization. **Pro**: adds **runtime insights** (whether an app is deployed/public-facing, whether vulnerable packages are actually used at runtime), integrations with **non-Snyk tools**, advanced policies, and analytics . **Pricing**: Quote-only; tiered by developers and features. **Free tier**: Limited for open source. **Best for**: Snyk customers wanting ASPM capabilities layered on their existing Snyk investment—**trade-off**: Pro tier required for full multi-tool ASPM.

- **[Kondukto](https://kondukto.io/)**
  **ASPM and orchestration platform** acquired by **Invicti Security** in August 2025 . Unified management of AppSec tools across SDLC, AI-powered remediation, and automation at scale. Combined with Invicti's runtime-validated DAST, delivers **proof-based prioritization**—only vulnerabilities confirmed exploitable by DAST are surfaced as critical. **Pricing**: Quote-only; now part of Invicti offerings. **Free tier**: None. **Best for**: existing Invicti DAST customers wanting ASPM orchestration with runtime-validated findings—**trade-off**: acquisition integration in progress.

- **[Jit](https://www.jit.io/)**
  **Open ASPM platform** with a **"shift left" philosophy**—prioritizing remediation before production, not after. Includes **built-in scanners** out of the box (SAST, SCA, secrets, IaC, DAST) plus ability to ingest third-party tools. **Developer-first**: change-based scanning in GitHub/GitLab/IDE, auto-remediation suggestions, developer security portals with scores per service. Security Plans align programs to outcomes (SOC2, reduce criticals by X%). Prioritization uses runtime and business context . **Pricing**: Quote-only; developer-based plans. **Free tier**: Limited. **Best for**: developer-led organizations wanting ASPM that prevents issues before production rather than managing backlogs—**trade-off**: less depth in enterprise governance than ArmorCode or OX.

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
