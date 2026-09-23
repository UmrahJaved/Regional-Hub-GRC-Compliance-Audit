# Regional-Hub-GRC-Compliance-Audit
Governance, Risk &amp; Compliance audit of the Regional R&amp;D and Production Hub network design by **Netify**.

The Governance, Risk & Compliance (GRC) report evaluates the proposed network infrastructure for the NVIDIA Regional R&D and Production Hub. It reviews the design, configurations, security controls, and Packet Tracer implementation against NVIDIA’s RFQ requirements.

The audit identifies major weaknesses in both technical security and governance. 

**Out of 14 assessed controls, none fully passed; 10 failed and 5 partially passed, resulting in an overall unsatisfactory rating.**

Key issues include:
* Weak and reused administrative credentials (“Cisco123”)
* VPN access without MFA
* Unrestricted server network traffic (ALLOW_ALL ACL)
* Exposed credentials in documentation
* Use of unencrypted FTP
* Incomplete ACLs and DMZ restrictions
* Missing Access Control Matrix
* No identified cybersecurity owner
* Inconsistent documentation

Regulatory applicability confirms GDPR, NIS2, and CyFun as mandatory frameworks; ISO 27001 is voluntary.

The risk register lists 14 risks:
* **2 Critical, 5 High, 7 Medium**  
Top priorities are replacing weak credentials, restricting server traffic, and removing exposed secrets.

The report concludes that significant remediation is required before go‑live, and several controls need verification or redesign.
