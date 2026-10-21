+++
title = 'Portfolio'
summary = 'Offensive security, infrastructure engineering, research, and competition leadership.'
+++

Offensive security engineer and red team lead with experience across enterprise, application, and cloud security.

{{< resume-download >}}

## Experience

### Toyota Motor North America · Red Team Security Engineer

*May 2026 - Present · On contract from TTS*

- Lead red team operations across Active Directory, Entra ID, and cloud environments. Translate threat intelligence and defensive concerns into MITRE ATT&CK-aligned emulation plans with attack objectives, technique dependencies, payload requirements, and telemetry validation criteria.
- Design and execute adversary emulation and purple team engagements spanning initial access, discovery, persistence, lateral movement, and exfiltration. Develop and adapt payloads and malware in Python and C# to reproduce adversary TTPs and test endpoint defenses. Chain discovery, data staging, and exfiltration techniques (e.g., ADSI enumeration, Robocopy staging, and C2 transfers).
- Partner with SOC and IR on investigations and detection engineering, correlating operator commands, execution timing, Microsoft Sentinel telemetry, and analyst observations. Develop behavioral heuristics across reconnaissance, persistence, native Windows execution, and data movement; identify missing events, telemetry delays, and correlation gaps.
- Build reusable SCYTHE emulation plans with ordered TTP sequences and agent execution on domain-joined endpoints. Replay campaigns to validate telemetry collection and detection changes, reducing repeated manual execution.
- Lead social engineering campaigns and develop custom macro payloads for initial access. Coordinate payload delivery and C2 staging to evaluate endpoint controls, payload execution, and SOC visibility.
- Expand an internal, homegrown C2 platform's communication, command execution, and beacon tasking capabilities.

### Confluent · Software Engineering Intern

*June 2025 - August 2025 · Cloud Infrastructure & Platform, Events team*

- Shipped a Terraform provider in Go for a Kubernetes-derived resource-management platform, implementing resource schemas, CRD support, and CRUD across most resource types. Translated declarative configuration into API requests and mapped responses to Terraform state, handling resource identity, lifecycle behavior, and API errors.
- Integrated the provider into Semaphore CI/CD and delivered it through the internal provider store, replacing manual CLI provisioning with declarative Terraform workflows.

### Praetorian · Senior Security Engineer

*June 2021 - May 2024*

- Led security engagements for Fortune 100 clients across enterprise networks, web applications, APIs, and cloud environments. Owned technical delivery from scoping and assessment planning through hands-on testing, reporting, client discussions, and remediation guidance.
- Conducted red team, assumed-breach, and internal and external penetration tests, mapping exposed services and configuration weaknesses. Chained reconnaissance, credential attacks, privilege escalation, and lateral movement to test segmentation, identity controls, and access to sensitive systems.
- Designed and executed phishing, vishing, and tailored social engineering campaigns to establish initial access. Developed pretexts, supporting materials, and payload-delivery workflows, using direct phone interactions to obtain credentials or code execution.
- Exploited Active Directory attack paths involving ACL abuse, Kerberos delegation, Active Directory Certificate Services (AD CS) misconfigurations, authentication coercion, and SCCM credential exposure. Used BloodHound, Impacket, Rubeus, and Certipy to map privilege relationships and chain identity weaknesses into privilege escalation and lateral movement.
- Assessed web applications and REST/GraphQL APIs for authentication bypass, broken access control, and business-logic vulnerabilities. Combined source-code review, static analysis with Semgrep, and vulnerability scanning with manual request manipulation in Burp Suite and Postman to validate exploitability and trace vulnerable code paths.
- Mentored junior consultants in assessment planning, testing methodology, evidence collection, and technical reporting. Reviewed testing decisions and findings to help them contribute independently to later client engagements.
- Published [How to Leverage DFSCoerce](https://www.praetorian.com/blog/how-to-leverage-dfscoerce/), [Writing Great IR Playbooks](https://www.praetorian.com/blog/writing-great-ir-playbooks/), and [Building an Evidence Wiki](https://www.praetorian.com/blog/building-an-evidence-wiki/). Integrated authentication-coercion research into assessment workflows through coauthored guidance, internal presentations, and support on client engagements.

---

## Skills

{{< skills >}}

---

## Education

### University of Texas at San Antonio

*Master of Science in Cybersecurity Science*

### University of Pennsylvania

*Bachelor of Science in Engineering, Computer Engineering*

- Awarded the **Rachleff Scholarship** for undergraduate research.
- **Undergraduate Chair, International Student Advisory Board** (2017-2021), representing international students to university leadership.

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

- Built Proxmox CCDC ranges with segmented Windows/Linux networks and vulnerable identity, DNS, mail, web, and database services.
- Trained teammates in service deployment, firewall rules, permissions, patching, and host/network log analysis, validating dependencies and availability during containment and recovery.
- Assigned system ownership and cross-trained teammates in host administration, networking, threat hunting, and incident response.

[Read the Southwest CCDC win announcement on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7441655399725948928/).

### Collegiate Penetration Testing Competition (CPTC)

*Team Captain · UTSA · 2025-2026 season*

- Led scoping, test planning, task assignment, coverage tracking, and client communication.
- Built a Proxmox range with collaborators: segmented networks, VM templates, snapshots, directory services, payment APIs, web applications, and PLC/Modbus simulations. Seeded credential exposure and weak permissions for attack-path exercises.
- Taught OSINT, reconnaissance, AD and web/API testing; reviewed exploit evidence, remediation, client reports, and briefings.

[Read how we built the CPTC practice range]({{< relref "posts/my-first-post.md" >}}).

---

## Writing & research

- [How to Leverage DFSCoerce](https://www.praetorian.com/blog/how-to-leverage-dfscoerce/): Authentication-coercion research.
- [Writing Great IR Playbooks](https://www.praetorian.com/blog/writing-great-ir-playbooks/): Practical guidance for incident response playbooks.
- [Building an Evidence Wiki](https://www.praetorian.com/blog/building-an-evidence-wiki/): Security evidence management and documentation.

## Conversations

[Hacker Factory with Phil Wylie: A Conversation with Derya Yavuz](https://open.spotify.com/episode/68HHpBC9DWhzz1lJ65mXuo).

---

## Certifications

- **OSCP** · Offensive Security Certified Professional
- **AZ-500** · Microsoft Certified: Azure Security Engineer Associate
- **AZ-104** · Microsoft Certified: Azure Administrator Associate
