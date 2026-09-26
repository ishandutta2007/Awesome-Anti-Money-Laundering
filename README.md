# Awesome-Anti-Money-Laundering

# Top Anti-Money Laundering (AML) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Transaction Monitoring, Sanctions Screening, PEP Checks, Case Management & Financial Crime Detection*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Anti-Money Laundering (AML)**. These systems screen customers and payments against sanctions/PEP lists, monitor transactions for suspicious patterns, and support investigation workflows required by financial regulators.

**Examples** include ComplyAdvantage, Feedzai, Napier AI, NICE Actimize, Flagright, Sanction Scanner, Lucinity, SEON, Unit21, and Silent Eight (the category leaders).

**Open-source emphasis**: Full enterprise AML suites are predominantly commercial. Open strength includes **OpenSanctions** for list data, **Marble** and **Jube** for monitoring/case engines, and research-grade transaction monitoring stacks. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ComplyAdvantage](https://complyadvantage.com/)**  
  AML data and screening platform—sanctions, PEP, adverse media—with APIs widely used by fintechs and banks.

- **[Feedzai, NICE Actimize, Napier AI](https://www.feedzai.com/)**  
  Enterprise transaction monitoring and financial crime platforms combining rules, ML, and case management.

- **[Flagright, Unit21, Lucinity, SEON](https://www.flagright.com/)**  
  Modern AML and fraud platforms oriented toward real-time monitoring, risk scoring, and investigator workflows for fintechs.

- **[Sanction Scanner, Silent Eight](https://www.sanctionscanner.com/)**  
  Screening and adverse-media focused solutions for KYC/AML compliance programs.

- **[Other commercial AML platforms](https://complyadvantage.com/)**  
  Additional solutions from major vendors (Oracle, SAS, FICO, etc.) for large-bank AML estates.

## Open-Source GitHub Projects

- **[OpenSanctions](https://github.com/opensanctions/opensanctions)**  
  Leading open database of sanctions, PEPs, and persons of interest—crawlers, entity graph (FollowTheMoney), and matching API (yente) for screening pipelines.

- **[Marble](https://github.com/checkmarble/marble)**  
  Open-source real-time decision engine for fraud and AML—transaction monitoring, screening, continuous monitoring, and investigation workflows; self-host option.

- **[Jube](https://github.com/jube-home/aml-fraud-transaction-monitoring)**  
  Open-source (AGPL) AML and fraud platform—real-time transaction monitoring, hybrid rules + ML, and case management.

- **[yente (OpenSanctions API)](https://github.com/opensanctions/yente)**  
  Open matching and search API for OpenSanctions datasets—bulk entity resolution for customer and payment screening.

- **[FollowTheMoney](https://github.com/opensanctions/followthemoney)**  
  Open data model and tooling for investigative entity graphs used across OpenSanctions and related fincrime projects.

- **[Research AML / TM ML pipelines](https://github.com/dirumisra/aml-transaction-monitoring)**  
  Open educational and research systems for transaction monitoring with ML, explainability (SHAP), and SAR-oriented workflows.

- **[Name-matching & fuzzy screening libraries](https://github.com/search?q=sanctions+screening+OR+name+matching+PEP+open+source)**  
  Community libraries for fuzzy name matching against sanctions lists.

- **[Rules engines adaptable to AML](https://github.com/search?q=business+rules+engine+transaction+monitoring)**  
  Open rules engines used to encode typologies and velocity checks in custom TM systems.

### Additional Strong Open-Source Options

- **Sanctions data**: OpenSanctions + yente as the open screening foundation.
- **Monitoring engines**: Marble or Jube for self-hosted TM and case management.
- **Entity graphs**: FollowTheMoney for investigative link analysis.
- **Composable stacks**: Core banking events → rules/ML → OpenSanctions screen → case queue.
- Commercial platforms still lead in regulated-bank coverage, typology libraries, and audit-ready case management.

**Frameworks for building custom systems**:  
**OpenSanctions** for list data and matching; **Marble** or **Jube** for monitoring and cases.  
Commercial AML platforms (ComplyAdvantage, Feedzai, Actimize, Flagright, Unit21, etc.) provide scale, model maintenance, and regulatory track records.  
Fintechs sometimes combine open screening with commercial TM; large banks typically rely on commercial suites. Fully open AML stacks are possible for lower-risk or internal use but require substantial compliance design and ongoing list/model governance.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AML systems are highly regulated. Deploying monitoring or screening software does not by itself satisfy BSA/AML, EU AMLD, or local obligations. False positives/negatives have serious customer and regulatory impact. Engage qualified compliance counsel and, where required, independent model validation.
- Open-source tools offer transparency and data control but place full responsibility for effectiveness, audit trails, and regulatory acceptance on the operator. Commercial platforms shift product and support burden to the vendor—neither replaces a complete AML program (policies, training, SAR processes).

---

**Made for compliance officers, fintech builders, and financial crime teams.**  
Let's expand open, auditable AML tooling while recognizing the regulatory depth and operational maturity that leading commercial AML platforms deliver.
