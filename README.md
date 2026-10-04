# Datacom Cyber Security Operations Job Simulation — Forage

**Completed:** September 20, 2026  
**Platform:** Forage  
**Program:** Datacom Cyber Security Operations Job Simulation

## Scenario

A simulated cybersecurity operations exercise covering a ransomware incident investigation and a separate cybersecurity risk assessment for a simulated retail organization.

## Business Context

The simulation used two scenario environments:

- **Orion Health Services** — a simulated 250-person ANZ healthcare technology provider used for the cyberattack investigation.
- **RetailNova Pty Ltd** — a simulated Melbourne-based retail company used for the cybersecurity risk assessment.

> **Evidence boundary:** This was a controlled Forage virtual job simulation. It was not employment with Datacom and does not represent a real incident or assessment of Orion Health Services or RetailNova Pty Ltd.

## Investigation

### Task 1 — Cyberattack Investigation

The simulated incident involved a ransomware attack that began with a phishing email containing a malicious Excel attachment.

The investigation covered:
- Incident timeline and attack-chain reconstruction.
- Indicators of compromise.
- Containment and credential protection.
- Evidence preservation and collection.
- Recovery considerations.
- Potential data-exposure considerations.
- Root-cause analysis.
- MITRE ATT&CK mapping.
- Security improvement recommendations.
- Executive priorities.

[View Task 1 — Cyberattack Investigation](task-1/cyberattack-investigation.md)

### Task 2 — Cybersecurity Risk Assessment

Assessed major risks for the simulated RetailNova environment using a **5×5 likelihood/consequence** approach.

The scenario included approximately 1,200 employees, 85 stores, e-commerce/mobile platforms, AWS, cloud POS, Salesforce, SAP, payment integrations, customer/loyalty data, BYOD, VPN, Teams, Slack and third-party providers.

[View Task 2 — Risk Assessment](task-2/risk-assessment.md)

## Evidence / Indicators

The cyberattack scenario included:
- An overseas login.
- Mimikatz activity.
- The .orionlock file extension.
- A phishing email containing a malicious Excel attachment.

These indicators were considered within the simulated incident context.

## Findings

The simulation highlighted:
- A phishing-origin attack path leading into a ransomware scenario.
- Credential-access activity requiring containment and protection of identities.
- The need to preserve evidence while responding to the incident.
- The importance of considering possible data exposure alongside operational disruption.
- The value of mapping observed activity to MITRE ATT&CK techniques.

## Risk Analysis

The RetailNova assessment considered five major risk areas:

1. Phishing and credential compromise.
2. Ransomware and enterprise disruption.
3. Third-party/vendor exposure.
4. E-commerce/AWS compromise.
5. BYOD and remote-access compromise.

A 5×5 likelihood/consequence matrix was used to assess risk and establish mitigation priorities.

## Recommended Actions

The simulation identified these mitigation themes:

- Strong identity and access management.
- MFA and least privilege.
- Security-awareness and phishing training.
- Endpoint monitoring and response.
- Network and system segmentation.
- Resilient backups and recovery testing.
- Third-party risk management.
- Cloud security monitoring.
- Incident-response planning and testing.

## Response Priorities

For the simulated ransomware investigation, the documented focus areas included containment, credential protection, evidence preservation, recovery planning, data-exposure considerations, root-cause analysis, and executive prioritization.

## Skills Demonstrated

- Cyberattack Investigation
- Incident Response
- Information Security
- Risk Assessment
- Risk Management
- Security Analysis
- Open Source Intelligence (OSINT)
- Research
- MITRE ATT&CK Mapping
- Analytical Writing
- Communication

## Lessons Learned

- Incident investigation requires both technical evidence analysis and business-impact consideration.
- Credential protection and containment are central priorities during ransomware response.
- Evidence preservation should be considered alongside containment and recovery.
- Risk assessments become more actionable when likelihood and consequence are explicitly evaluated.
- Security recommendations should address identity, endpoint, network, cloud, backup and third-party risks together.

## Portfolio Relevance

This simulation strengthens the portfolio's SOC and incident-response narrative by demonstrating structured cyberattack investigation, risk assessment, OSINT/research, MITRE ATT&CK mapping and security recommendations in a controlled environment.

## Evidence

- [Task 1 — Cyberattack Investigation](task-1/cyberattack-investigation.md)
- [Task 2 — Risk Assessment](task-2/risk-assessment.md)
- [Completion Evidence](evidence/completion-date.md)
- [Certificate Information](certificate/README.md)

## Evidence Scope

This repository documents simulated learning activities completed through Forage. It does not claim employment, production access, or a real-world Datacom engagement.