# SOC Home Lab — Wazuh + Suricata + VirusTotal

## 🏗️ Architecture
- Wazuh Manager (Docker on Kali Linux)
- Ubuntu Endpoint Agent "ICONIC"
- Suricata IDS/IPS
- VirusTotal Threat Intel Integration

## 🛠️ Tools Used
- Wazuh 4.10.3
- Suricata IDS
- VirusTotal API
- Docker
- Kali Linux
- Ubuntu

## 🎯 What I Built
- Deployed Wazuh SIEM using Docker
- Connected Ubuntu endpoint as monitored agent
- Configured Suricata IDS for network threat detection
- Integrated VirusTotal API for automated malware scanning
- File Integrity Monitoring detecting malware in real time

## 🔥 Attacks Simulated
- EICAR malware drop → detected by 66 AV engines
- Real-time FIM alerts triggering VirusTotal scan
- CIS Ubuntu Benchmark compliance scanning
- 193+ security events detected

## 📊 Results
- VirusTotal flagged EICAR with 66 engine detections
- Rule 87105 Level 12 alert fired
- 8 malware detection hits in dashboard
- Active endpoint monitoring confirmed

## 🏆 Key Findings
- File drop on monitored directory triggers instant VirusTotal scan
- Wazuh FIM + VirusTotal = powerful malware detection pipeline
- Real-time alerting with severity level classification

## 📜 Certifications
- Google Cybersecurity Professional Certificate ✅
- CompTIA Security+ — In Progress 🔄

## 🔗 Connect
- LinkedIn: https://www.linkedin.com/in/george-eze-654ba0327?utm_source=share_via&utm_content=profile&utm_medium=member_android
