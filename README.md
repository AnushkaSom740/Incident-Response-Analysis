🚨 Incident Response Analysis – DoS Attack
📌 Overview
This project demonstrates my ability to investigate and respond to a simulated Denial of Service (DoS) attack. The analysis covers detection, containment, eradication, and recovery steps, following industry-standard incident response methodologies.

🎯 Objectives
Detect abnormal traffic patterns and service disruptions.

Apply the NIST Incident Response Lifecycle (Preparation → Identification → Containment → Eradication → Recovery → Lessons Learned).

Document findings and propose mitigation strategies.

Showcase practical use of cybersecurity tools for log and traffic analysis.

🛠️ Tools & Techniques
Wireshark – Packet capture and traffic inspection.

TCPdump – Command-line traffic analysis.

Splunk / Chronicle – Log correlation and event monitoring.

System Monitoring – CPU, memory, and bandwidth usage tracking.

Frameworks Referenced – NIST IR Lifecycle, MITRE ATT&CK.

🔍 Methodology
Detection

Captured network traffic during simulated DoS attack.

Identified abnormal spikes in traffic volume and repeated requests from suspicious IPs.

Analysis

Correlated logs to confirm service disruption.

Verified attack vectors (e.g., SYN flood, HTTP request flood).

Containment

Blocked malicious IPs using firewall rules.

Rate-limited incoming traffic.

Eradication & Recovery

Cleared malicious sessions.

Restored normal service availability.

Lessons Learned

Importance of proactive monitoring and alerting.

Need for automated detection rules in SIEM.

📑 Key Findings
Attack originated from multiple IPs simulating a flood attack.

Service downtime lasted approximately X minutes before containment.

Recommended implementing load balancing and intrusion prevention systems (IPS) for resilience.

📈 Outcome / Impact
Successfully detected and mitigated simulated DoS attack.

Documented incident response workflow for future reference.

Strengthened understanding of network defense strategies.

▶️ How to View/Run
Open incident-report-analysis.docx for detailed analysis.

Splunk queries and Wireshark captures are available in the /analysis folder.

🔮 Future Improvements
Automate detection with SIEM correlation rules.

Integrate IDS/IPS for real-time blocking.

Explore cloud-based DDoS protection services
