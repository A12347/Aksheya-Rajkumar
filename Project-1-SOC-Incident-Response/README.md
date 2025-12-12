# Project 1 — SOC Incident Response Using SIEM & EDR

## Objective
Demonstrate a basic SOC workflow: alert triage → investigation → response documentation.

## Tools Used
- ConnectWise SIEM
- SentinelOne EDR
- AWS CloudTrail / GuardDuty (supporting evidence)
- Cloudflare WAF (supporting evidence)

## Scenario 1: Suspicious Login / Risky Sign-in
### Steps
1. Alert observed in SIEM
2. Collected key indicators (user, IP, time, source)
3. Checked supporting logs (cloud / identity logs)
4. Classified severity and recommended action
5. Documented incident summary + next steps

## Scenario 2: Endpoint Malware Detection
### Steps
1. Malware alert observed in EDR
2. Checked device/user context and process info
3. Recommended containment and escalation steps
4. Documented findings and remediation notes

## Deliverables
- Incident summary template
- Investigation checklist
- Lessons learned notes

## Notes
All examples are training-focused and do not include sensitive client information.

