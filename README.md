# Cyber-Security-Analysis-with-NIST-CSF-Mapping
Assessment of Qualicart’s security using NIST CSF (Identify, Protect, Detect, Respond, Recover). Deliverables: gap→target maturity map, Incident Response Plan, severity model, detection/reporting workflows, tabletop scenarios, comms plan, and a costed 3-year roadmap to lift security maturity.


**What’s in this repo**

/report — Final Analysis Report (PDF): executive summary, gap analysis, incident playbooks, comms, KPIs, and roadmap

/mappings — NIST CSF subcategory map (current → target maturity; priority tags)

/costs — Investment vs. loss scenarios (prevention vs. breach costs)

If you’re time-crunched, start with the Executive Summary and the 3-Year Roadmap.


**Methods & Framework**

Framework: NIST CSF v1.x mapping across ID/PR/DE/RS/RC

Approach: Current-state maturity scoring → prioritized gaps → target state → program plan

Operationalization: IR team roles, severity levels, detection/reporting pipelines, tabletop exercises, KPI set (MTTD/MTTR, patch SLAs, phishing click-rates)


**Key Deliverables (highlights)**

Cybersecurity Incident Response Plan (CIRP) with roles (IRM, TRT, Forensics, Legal/Compliance, Comms) and minute-one actions

Incident taxonomy & severity model (Low/Medium/High/Critical) aligned to app, APIs, and payment systems

Detection & reporting workflow (SIEM + employee channel + non-retaliation policy)

Tabletop scenarios (phishing, ransomware, DDoS, insider, third-party) with post-mortem loop

3-Year Roadmap (quarterly milestones) to lift 37 subcategories to High maturity

Cost modeling comparing prevention investments vs. industry breach costs


**Findings at a glance**

Baseline: Majority Low/Medium maturity; only one subcategory initially High

High-leverage gaps: Asset inventory (ID.AM), Access control/MFA (PR.AA/PR.AC), Awareness & training (PR.AT), Continuous monitoring + SIEM (DE.CM), Response playbooks (RS.RP/RS.MI)

KPIs define progress: MTTD/MTTR, patch timelines, phishing click-rates, audit scores


**3-Year Roadmap**

Year 1 – Foundation & Visibility: Asset inventory, governance, supply-chain risk, risk tolerance defined

Year 2 – Safeguards & Detection: RBAC/MFA, data security, endpoint & integrity monitoring, SIEM in place

Year 3 – Response & Recovery: Playbooks, crisis comms, DR testing, continuous improvement cycles


**Cost & Risk Rationale**

Modeled investments (training, asset discovery, MFA, SIEM, backups) are significantly lower than projected breach losses and reputational damage common in e-commerce and supply-chain platforms. Prevention wins on both finance and resilience.


**How to use this repo**

Read /report/final_report.pdf for context and decisions.

Open /mappings to see exact NIST CSF subcategory deltas and priorities.

Use /artefacts during tabletop runs and to brief execs/security teams.

Track KPIs from /report to measure maturity lift over time.

Tech & Governance: NIST CSF • IR playbooks • SIEM-driven detection • RBAC/MFA • Backup/DR • KPI-led improvement

Author: Jay Goodman (Team XYZ) — contributions noted in report.
