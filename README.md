# Soc Analyst Notes and Training
## Table of Contents
1. Index
2. Research and Notes
3. Labs/Experience/Work
# Index
- Jira
- Splunk Detect
- Splunk Investigate
- Splunk Remediate
- Wireshark
- tcpdump
- Python
- Bash
- PowerShell
- SecOps
- Email Investigation
    - Header Analysis
    - Office Doc investigation
    - Marco Extraction
- Basic Malware Analysis Static
- Dynamic Analysis
- Event Log analysis
- EDR 
- IDS/IPS
- Comprehension of attack exploits on operating systems/protocols
- Linux Systems
- Windows System
- Mac OS
- AWS
- Basic understanding of network structures and Cloud architectures
- Application Security & maintenance alert/Response
- Fireblocks
- Nessus
- Kibana
- ElasticSearch
- SolarWinds
- Cyber-Attack Vectors
    - Buffer Overflow
    - Phising
- Information Security Operation Center 
- Threat Hunting
- IOC's
- DFARS
- ITAR/EAR
- NIST
- CMMC
# Notes and Research
## The Goal
Software Solutions for a Minimalistic Realtor SOC
Building an SOC for a realtor company with limited resources requires careful consideration of cost, ease of use, and effectiveness. Here are some program options across three key areas:

1. Threat Detection:

Security Information and Event Management (SIEM):
Open-source options: AlienVault, ELK Stack
Commercial options: Crowdstrike Falcon SIEM, Palo Alto Cortex XDR
Endpoint Detection and Response (EDR):
Open-source options: OSSEC HIDS, Wazuh
Commercial options: SentinelOne, Crowdstrike Falcon Endpoint Protection
Vulnerability Management:
Open-source options: OpenVAS, Nessus
Commercial options: Qualys Vulnerability Management, Rapid7 Nexpose
2. Compliance Management:

Compliance-as-a-Service (CaaS) platforms:
Third-party solutions: GRC Compliance, ZenGRC
Regulatory information resources:
Government websites: HIPAA.gov, PCI DSS
Security awareness training platforms:
Open-source options: KnowBe4
Commercial options: PhishMe, CIS Security
3. Incident Response:

Security orchestration, automation, and response (SOAR) platforms:
Open-source options: XSOAR
Commercial options: Palo Alto Cortex XSOAR, Splunk Phantom
Threat intelligence feeds:
Open-source options: AlienVault Open Threat Exchange (OTX)
Commercial options: ThreatConnect, FireEye iDefense
Additional Considerations:

Cloud-based solutions: Consider cloud-based options for easier deployment and management with limited team resources.
Integration: Choose tools that integrate well with each other to streamline workflows and improve efficiency.
Scalability: Select solutions that can scale as your security needs and resources grow.
Training and support: Ensure your team has adequate training and support to effectively use the chosen tools.
Remember: While open-source tools offer cost advantages, commercial solutions often provide more advanced features and support. Evaluating your specific needs and budget will help you determine the best balance.

Final Note: Building an effective SOC requires more than just software. Establishing clear security policies, procedures, and incident response plans is crucial for a successful outcome. Additionally, consider engaging external consultants or a managed security service provider (MSSP) if your internal team needs additional expertise.

I hope this information helps you build a robust and effective SOC for your realtor company with limited resources.
## Building Out w/ Open-Source Options
Building a Realtor SOC with Open Source Tools: A Step-by-Step Guide
Securing your realtor company with a minimal security team doesn't mean compromising on protection. Open-source software offers a powerful and cost-effective way to build a robust SOC. Here's a step-by-step guide to get you started:

1. Define Your Goals and Scope:

Threat Detection: What types of threats are you most vulnerable to? (Phishing, ransomware, malware)
Compliance: Which regulations apply to your business? (HIPAA, PCI DSS)
Incident Response: How will you respond to security incidents?
Team Capabilities: Assess your team's technical expertise and available resources.
2. Choose Your Open-Source Toolkit:

SIEM:
AlienVault: User-friendly interface, good threat detection capabilities, free community edition.
ELK Stack: Powerful and customizable, requires technical expertise, free and open-source.
Endpoint Detection and Response (EDR):
OSSEC HIDS: Intrusion detection system, lightweight, requires some security knowledge.
Wazuh: Unified security platform, includes HIDS, SIEM, and vulnerability scanning, steeper learning curve.
Vulnerability Management:
OpenVAS: Comprehensive vulnerability scanner, free and open-source.
Nessus: Powerful scanner with advanced features, free for personal use, paid versions for businesses.
Compliance Management:
Free compliance checklists and templates: Available online through government websites and security organizations.
Open-source security awareness training tools: KnowBe4 offers free training modules.
Incident Response:
XSOAR: Free and open-source SOAR platform, requires significant customization.
Manual scripts and tools: Develop your own scripts for automation and reporting.
Threat Intelligence Feeds:
AlienVault Open Threat Exchange (OTX): Free community intelligence feed.
MISP: Open-source threat intelligence platform, allows sharing and collaboration.
3. Deploy and Configure:

Follow detailed installation guides for each tool.
Integrate your chosen tools for streamlined workflows.
Customize configurations based on your specific needs.
Develop incident response procedures and playbooks.
4. Training and Documentation:

Train your team on using the chosen tools effectively.
Document your SOC setup and procedures for future reference.
5. Ongoing Monitoring and Improvement:

Regularly monitor your systems for threats and vulnerabilities.
Review your logs and logs from integrated tools to identify security incidents.
Refine your SOC configuration and procedures based on real-world experience.
Additional Tips:

Start small and scale gradually.
Seek help from open-source communities and forums.
Consider engaging security consultants for initial setup and guidance.
Regularly update your tools and threat intelligence feeds.
Building a successful SOC with open-source tools requires dedication and ongoing effort. But by following these steps and leveraging the power of open-source communities, you can create a robust and effective security posture for your realtor company even with limited resources. Remember, even a well-configured open-source SOC is only as effective as the team using it. Invest in training and empower your team to become your first line of defense.
## Basic Malware Analysis Static
- Watch mark hammond and mimic what he is doing, 1 windows, 1 linux
