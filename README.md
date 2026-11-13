## 🚀 Featured Projects

### 🛡️ [SOC Alert Monitoring & Log Correlation](https://github.com/kshitij-soc/SOC-Alert-Monitoring-Capstone)
SOC investigation in a virtual lab (Windows + Kali Linux). A Python-based incident analyzer parses Windows Event Logs and Sysmon telemetry, reconstructs a chronological timeline, extracts and correlates IOCs, and maps activity to MITRE ATT&CK. Network activity cross-checked with Wireshark.

### 🕷️ [Web Application Security Assessment](https://github.com/kshitij-soc/web-application-security-assessment)
Black-box DAST assessment of OWASP Juice Shop (Docker) using OWASP ZAP. Automated findings manually validated against the OWASP Top 10, including documented SQL injection testing and a security header review. Delivered as a risk-prioritized report with remediation recommendations.

### 🔀 [DOM-Based Open Redirect Burp Assessment](https://github.com/kshitij-soc/DOM-Based-Open-Redirect-Burp-Assessment)
Manual assessment of an authorized PortSwigger Web Security Academy lab. Used Burp Suite to capture and manipulate HTTP requests, validated the `url` parameter on the `/post` endpoint, and confirmed the DOM-based open redirect in the browser. Documented CWE-601 mapping, evidence, qualitative risk and remediation.

### 🪙 [Coincheck NEM Theft Investigation (2018)](https://github.com/kshitij-soc/coincheck-hack-investigation)
Independent, reproducible blockchain investigation of the January 2018 Coincheck hack using data collected from a public NEM node. Traced 526,300,010 XEM across 11 transfers out of the exchange wallet and 523,000,000 XEM onward to eight addresses, reconstructed the timeline, and analysed the single-signer hot-wallet weakness. Delivered an incident report, executive summary, mitigation plan, deck and an evidence portfolio with SHA-256 hashes, chain of custody and a finding-to-evidence matrix. Findings are labelled Confirmed, Strongly supported, Interpretation or Unknown, and a data-processing error found in self-review was documented and corrected.

### 🔐 [SecureLink VPN Gateway](https://github.com/kshitij-soc/SECURELINK-VPN-GATEWAY)
VMware lab building a secure VPN for remote access: strongSwan IKEv2/IPsec site-to-site and OpenVPN client-to-site with TLS 1.3, AES-256-GCM, certificate authentication and TOTP MFA. Added iptables access control, certificate revocation, centralized rsyslog logging, iperf3 performance testing and a Windows client test with Wireshark traffic analysis. Delivered as six documents with a traceability matrix and 38 evidence screenshots, with limitations stated openly.
