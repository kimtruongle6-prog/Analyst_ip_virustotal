# 🛡️ Analyst IP VirusTotal

A Python-based utility designed to perform rapid threat analysis on IP addresses using the VirusTotal API.

---

## 📝 Data Source & Provenance
> [!IMPORTANT]
> All data analyzed in this project was captured through a **Honeypot deployed on Google Cloud Platform (GCP)**.

* **Target IPs**: Entities attempting to scan or brute-force cloud instances.
* **Goal**: Bridging automated data collection (Honeypot) with threat intelligence enrichment.

---

## 🚀 Key Features
- **IP Reputation**: Checks safety status against 70+ security vendors.
- **Enrichment**: Retrieves `AS Owner` and `Country` data.
- **Malware Linkage**: Identifies files communicating with the target IP.

---

## 🛠️ Usage

### 1. Install Dependencies
```python
!pip install vt-py nest_asyncio
