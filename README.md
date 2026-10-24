# Threats-Vs-Vulnerabilities
Threats vs Vulnerabilities
A quick reference on one of the most commonly confused pairs in security: threats and vulnerabilities.

The short version
Threat	Vulnerability
Definition	Anything that could cause harm to an asset	A weakness that can be exploited
Origin	External (usually) or internal actor/event	Internal flaw in systems, process or people
Controllable?	Mostly no, you can only reduce exposure	Yes, you can find and fix it
Question it answers	Who or what could hurt us?	Where are we weak?
Examples	Ransomware gangs, phishing, insider, flood, DDoS	Unpatched software, weak passwords, open ports, no MFA
Managed by	Threat intelligence, monitoring, detection	Scanning, patching, hardening, training
An analogy
A burglar is the threat. An unlocked door is the vulnerability. The risk is the chance the burglar walks through that door and what they could take (the impact on your assets).

How they fit together
Risk = Threat x Vulnerability x Impact
No vulnerability? A threat has nothing to exploit.
No threat? A vulnerability may sit unused (but never assume it stays that way).
Low-value asset? Impact is small, so risk is small.
An exploit is the method a threat uses to take advantage of a vulnerability.

Worked examples
Scenario	Threat	Vulnerability	Risk
Public web app	SQL injection attacker	Unsanitised input	Customer data breach
Office laptops	Phishing campaign	Staff untrained, no MFA	Account takeover
Data centre	Flood or fire	No offsite backup	Extended outage, data loss
Server	Ransomware group	Unpatched OS	Encrypted systems, ransom demand
What to do about each
Threats (reduce likelihood and exposure)

Subscribe to threat intelligence feeds
Monitor logs and use detection tools (SIEM, EDR)
Run incident response drills
Vulnerabilities (remove the weakness)

Regular vulnerability scans and pen tests
Patch management and secure configuration
Least privilege, MFA, security awareness training
Self-check
A zero-day in your VPN appliance is a ______. (vulnerability)
The nation-state group exploiting it is a ______. (threat)
Likelihood x impact of that exploit succeeding is ______. (risk)
Further reading
NIST SP 800-30: Guide for Conducting Risk Assessments
MITRE ATT&CK (threat behaviours) and CVE/NVD (vulnerabilities)
OWASP Top 10
