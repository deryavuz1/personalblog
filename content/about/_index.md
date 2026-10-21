+++
title = 'Portfolio'
summary = 'Offensive security, infrastructure engineering, research, and competition leadership.'
+++

Offensive security engineer and red team lead with experience across enterprise, application, and cloud security.

{{< resume-download >}}

## Experience

### Toyota Motor North America · Red Team Security Engineer

*May 2026 - Present · On contract from TTS*

- Lead red team operations across Active Directory, Entra ID, and cloud environments, directing adversary emulation, social engineering, and purple team execution. Turn threat intelligence and defensive concerns into MITRE ATT&CK-aligned plans with defined attack objectives, technique sequences, payload requirements, and detection checks.
- Designed and ran a two-hour ransomware emulation for a Toyota subsidiary, partnering with threat intelligence to model BlackBasta tactics, techniques, and procedures (TTPs). Executed initial access, directory discovery, persistence, lateral movement, data staging, exfiltration, and encryption behaviors through manual commands and payloads. Explained the attack sequence and observed defensive gaps during live execution with more than 70 security stakeholders.
- Partner with the security operations center (SOC) and incident response (IR) teams on incident investigations and purple team engagements. During live emulation, compare the operator's execution sequence with Microsoft Sentinel telemetry and analyst observations to identify missed behaviors, delayed events, and correlation gaps.
- Work with SOC engineers to develop behavioral detection heuristics that connect directory reconnaissance, native Windows execution, and ransomware-adjacent activity across an attack sequence. Supply the commands, timing, and execution context needed to build and test detection logic during live exercises. The defensive teams developed and tested 12 new alerts during the ransomware engagement.
- Converted the campaign into reusable SCYTHE plans executed by emulation agents on domain-joined endpoints. Preserved the TTP sequence so defenders could replay attack behaviors, inspect the resulting telemetry, and test detection changes, reducing repeated requests for manual retesting.
- Lead social engineering campaigns and develop custom macro payloads for initial-access simulation. Coordinate scenario preparation, payload execution, and command-and-control (C2) staging with the broader emulation plan to test the progression from user interaction to execution and defensive visibility.
- Develop offensive tooling and payloads in Python and C#, and extend the internal C2 framework in Python, C#, and JavaScript. Added HTTPS/TLS support to its communication paths and refined Windows CMD and Bash execution into a terminal-style workflow for interacting with beacons.

### Confluent · Software Engineering Intern

*June 2025 - August 2025 · Cloud Infrastructure & Platform, Events team*

- Shipped a Terraform provider in Go for a Kubernetes-derived platform, delivering a project that had spent more than a year in the backlog. Implemented resource schemas, Kubernetes CustomResourceDefinition (CRD) support, and create, read, update, and delete operations across most resource types. Mapped declarative configuration to resource-management API calls and responses to Terraform state, handling resource identity, lifecycle behavior, and API errors.
- Integrated the provider into Semaphore CI/CD and delivered it through the internal provider store, replacing manual CLI provisioning with repeatable, declarative resource management.

### Praetorian · Senior Security Engineer

*June 2021 - May 2024*

- Led security engagements for Fortune 100 clients across enterprise networks, web applications, APIs, and cloud environments. Owned technical delivery from assessment planning and hands-on testing through reporting, client discussions, and remediation guidance.
- Conducted red team and assumed-breach engagements to demonstrate attack paths from a compromised account or endpoint to sensitive systems. Combined reconnaissance, credential attacks, lateral movement, and privilege escalation to test how identity and infrastructure controls held up against an attacker.
- Designed and executed phishing, vishing, and other social engineering campaigns to establish initial access for red team engagements. Combined tailored pretexts, supporting materials, payload delivery, and sustained phone interactions to obtain credentials or code execution and advance engagement objectives.
- Performed internal and external penetration tests across enterprise networks and internet-facing infrastructure. Mapped exposed services, tested network segmentation, and exploited configuration weaknesses to identify entry points and demonstrate access across trust boundaries.
- Identified and exploited Active Directory weaknesses involving access-control permissions, Kerberos delegation, certificate services, and SCCM. Chained credential exposure and excessive privileges into access to sensitive infrastructure, then worked with system owners to address the underlying permission and configuration weaknesses.
- Assessed web applications and REST/GraphQL APIs for authentication, authorization, and business-logic flaws. Combined static code analysis and vulnerability scanners with manual testing in Burp Suite and Postman. Validated findings, demonstrated exploitability, and gave engineering teams reproducible evidence and remediation guidance.
- Mentored junior consultants through assessment planning, hands-on testing, and technical reporting on client engagements. Reviewed testing decisions and evidence with them so they could develop findings and contribute independently to later assessments.
- Published three technical articles: [How to Leverage DFSCoerce](https://www.praetorian.com/blog/how-to-leverage-dfscoerce/), [Writing Great IR Playbooks](https://www.praetorian.com/blog/writing-great-ir-playbooks/), and [Building an Evidence Wiki](https://www.praetorian.com/blog/building-an-evidence-wiki/). Brought authentication-coercion research into the team's assessment workflow through coauthored guidance, internal presentations, and support on client engagements.

---

## Education

### University of Texas at San Antonio

*Master of Science in Cybersecurity Science*

### University of Pennsylvania

*Bachelor of Science in Engineering, Computer Engineering*

- Awarded the **Rachleff Scholarship** for undergraduate research.
- Served as **Undergraduate Chair of the International Student Advisory Board** from 2017 to 2021. Represented international students, worked with university leadership, and supported community initiatives.

---

## Leadership & achievements

### National Collegiate Cyber Defense Competition (NCCDC)

**6th place nationally · 2026**

*Team Captain · UTSA*

- Led UTSA's defense during the 16-hour national final, placing 6th in the nation's cybersecurity team rankings.

[Read UTSA's national competition recap on LinkedIn](https://www.linkedin.com/posts/practical-learning-experiences-prepare-students-share-7460027544382111745-08PG/).

### Southwest Collegiate Cyber Defense Competition (SWCCDC)

**1st place · 2026 Southwest champions**

*Team Captain · 2025-2026 seasons · 3rd place in 2025*

- Built mock CCDC ranges on Proxmox with Windows and Linux hosts, segmented networks, and vulnerable configurations across identity, DNS, mail, web, and database services.
- Trained teammates in service deployment, firewall rules, permission auditing, patching, and host and network log analysis. Practiced containment and recovery while checking service dependencies and availability.
- Assigned system ownership, ran hands-on exercises, and cross-trained teammates across host administration, networking, threat hunting, and incident response.

[Read the Southwest CCDC win announcement on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7441655399725948928/).

### Collegiate Penetration Testing Competition (CPTC)

*Team Captain · UTSA · 2025-2026 season*

- Led engagement scoping, test planning, coverage tracking, and client communication. Assigned testing responsibilities and consolidated findings into a coordinated assessment.
- Built a Proxmox range with collaborators using routed subnets, VM templates, and snapshots across corporate, guest, simulated cloud, and operational technology networks. Integrated directory services, payment APIs, web applications, and PLC/Modbus simulations with credential exposure and weak permissions for repeatable attack-path exercises.
- Taught open-source intelligence (OSINT), reconnaissance, Active Directory, and web/API testing. Reviewed exploitation evidence and coached reports and briefings that connected findings to business impact and remediation.

[Read how we built the CPTC practice range]({{< relref "posts/my-first-post.md" >}}).

---

## Writing & research

At Praetorian, I helped turn technical research and assessment practices into resources other security teams could use.

- [How to Leverage DFSCoerce](https://www.praetorian.com/blog/how-to-leverage-dfscoerce/): Authentication-coercion research.
- [Writing Great IR Playbooks](https://www.praetorian.com/blog/writing-great-ir-playbooks/): Practical guidance for incident response playbooks.
- [Building an Evidence Wiki](https://www.praetorian.com/blog/building-an-evidence-wiki/): Security evidence management and documentation.

## Conversations

Joined Phil Wylie on the Hacker Factory podcast for a conversation about my work as a security engineer.

[Listen to A Conversation with Senior Security Engineer, Derya Yavuz](https://open.spotify.com/episode/68HHpBC9DWhzz1lJ65mXuo).

---

## Certifications

- **OSCP** · Offensive Security Certified Professional
- **AZ-500** · Microsoft Certified: Azure Security Engineer Associate
- **AZ-104** · Microsoft Certified: Azure Administrator Associate

## Contact

[Email](mailto:deryayavuz7@gmail.com) · [LinkedIn](https://www.linkedin.com/in/derya-yavuz/) · [GitHub](https://github.com/deryavuz1)
