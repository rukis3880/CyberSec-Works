#  CyberNetics-Security-Sandbox  #

| A collection of Cyber Laboratory Projects  |  

**Project 1: Hacking Adventures with Kali Linux**
•	Conducted hands-on penetration testing using Kali Linux to simulate real-world hacking scenarios.
•	Explored and exploited vulnerabilities in various systems, enhancing practical cybersecurity skills.
•	Applied ethical hacking techniques to identify and address security weaknesses effectively.

**Project 2: Vulnerability Assessment with OpenVAS**
•	Executed comprehensive vulnerability assessments using OpenVAS to identify potential security risks.
•	Analyzed scan results to prioritize and remediate vulnerabilities, ensuring a robust security posture.
•	Developed a systematic approach to proactively manage and enhance the organization's cybersecurity resilience.

**Project 3: Endpoint Analysis and Digital Forensics with Velociraptor**
•	Velociraptor for endpoint analysis, enabling deep forensic investigation on individual devices.
•	Conducted detailed examinations of endpoints to identify and respond to security incidents promptly.
•	Enhanced incident response capabilities by utilizing Velociraptor's powerful endpoint monitoring features.

**Project 4: Real-Time Security Monitoring with Wazuh**
•	Deployed Wazuh for real-time security monitoring, providing continuous threat detection.
•	Configured and fine-tuned Wazuh rules to align with the organization's security policies.
•	Strengthened the incident detection and response capabilities with effective real-time monitoring.

**Project 5: Network Traffic Analysis with Wireshark**
•	Conducted in-depth network traffic analysis using Wireshark to identify anomalies and potential threats.
•	Interpreted packet captures to analyze communication patterns and detect malicious activities
•	Improved network security by gaining insights into traffic behavior and implementing proactive measures.

**Project 6: Realtime Log Ingestion and Scanning with Splunk Enterprise, Sysmon, Cisco**
•	Ingested Sysmon logs and investigated unauthorized user behavior traffic.
•	Ingested Cisco device and edge device logs to observe and interdict unauthorized asset exfiltration
•	Improved network security by gaining insights into traffic behavior and implementing proactive measures.

**Project 7: Digital Forensic Investigation with FTK Imager, KAPE, EZ Tools, Volatility 3**
•The Forensic Workstation Principle
A forensic workstation is a dedicated system (or VM) used exclusively for analysis. This separation ensures that analyst activity does not contaminate evidence, prevents malware from spreading to the analyst machine, and provides a clean, repeatable environment. In this lab, the analysis VM fulfils this role. 

•Write Protection and Evidence Integrity
The cardinal rule of digital forensics is that original evidence must never be altered. This is enforced through software write-blockers (Registry-based on Windows, wrtblkr tools, or hardware write-blockers on physical engagements). Any action taken on a forensic image must be performed on a verified copy, not the original. FTK Imager enforces this by mounting images in read-only mode by default.

•Hash Verification
Cryptographic hashing (MD5 and SHA-256) is used to verify that an evidence copy is identical to the 
original at the time of acquisition and at all subsequent stages of the investigation. A mismatch in hash values means the evidence has been altered - intentionally or not - and its integrity cannot be established in court. Hash verification is not optional; it is a mandatory step before and after every evidence transfer.

•Chain of Custody
Chain of custody is a chronological documentation record that tracks who had access to evidence, when, why, and what actions they took. Even a forensically perfect analysis is inadmissible if chain of custody is broken. Every evidence item must have a unique identifier, acquisition timestamp, hash values, and a log of every person who handled it.

•KAPE vs Full Disk Image
KAPE performs targeted triage collection - it copies only the files and artefacts relevant to an investigation (event logs, registry hives, prefetch, etc.) without imaging the full disk. This is orders of magnitude faster than a full image and is used when speed is critical (live system, limited window). A full disk image with FTK Imager captures everything, including unallocated space and deleted files, and is used when comprehensive analysis is required.
