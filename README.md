<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00ff41,100:0d1117&height=180&section=header&text=ThreatLensX&fontSize=52&fontColor=00ff41&fontAlignY=38&desc=Open-Source+SOC+Reconnaissance+%26+Threat+Intelligence+Platform&descAlignY=58&descSize=15&descColor=ffffff&animation=fadeIn" width="100%"/>

</div>

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-00ff41?style=for-the-badge)](https://github.com/rilwan26/ThreatLensX)
[![Built For](https://img.shields.io/badge/Built_For-SOC_Operations-4B0082?style=for-the-badge&logo=shield&logoColor=white)](https://github.com/rilwan26/ThreatLensX)
[![Ethical](https://img.shields.io/badge/Authorized_Use_Only-red?style=for-the-badge&logo=hackthebox&logoColor=white)](https://github.com/rilwan26/ThreatLensX)

</div>

---

## 📌 Overview

**ThreatLensX** is an open-source SOC reconnaissance and threat intelligence platform designed for security analysts, penetration testers, and red teamers. It automates web reconnaissance, vulnerability detection, and threat analysis workflows — cutting manual reconnaissance time significantly.

Built by a CEH-certified analyst with hands-on experience in enterprise VAPT and SOC operations.

> ⚠️ **Legal Notice:** This tool is for **authorized security testing only**. Always obtain written permission before scanning any target. Unauthorized use may violate laws.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔍 **Web Reconnaissance** | Comprehensive surface mapping of target domains |
| 🌐 **IP & DNS Analysis** | Reverse DNS, ASN lookup, geolocation, and DNS record enumeration |
| 🔐 **SSL/TLS Inspection** | Certificate chain analysis, cipher strength, expiry detection |
| 🛡️ **Security Headers Audit** | CSP, HSTS, X-Frame-Options, and more |
| 🕷️ **Web Crawling & OSINT** | Spider-based link harvesting and metadata extraction |
| 🕵️ **Dark Web Scanning** | Tor-supported scanning for anonymous threat intelligence |
| 📊 **Vulnerability Detection** | CVE mapping with CVSS v3 scoring |
| 🔥 **WAF Detection** | Identifies Web Application Firewall presence and fingerprinting |
| 📁 **Export Capabilities** | JSON output for integration into SIEM and reporting pipelines |

---

## 🚀 Installation

### Prerequisites

- Python 3.8+
- pip
- (Optional) Tor for dark web scanning

```bash
# Clone the repository
git clone https://github.com/rilwan26/ThreatLensX.git
cd ThreatLensX

# Create virtual environment
python3 -m venv venv
source venv/bin/activate      # Linux/macOS
# venv\Scripts\activate       # Windows

# Install dependencies
pip install -r requirements.txt
```

---

## ⚡ Usage

```bash
# Basic scan
python scanner.py https://example.com

# Deep scan (increase crawl depth)
python scanner.py https://example.com -d 3

# Scan via Tor (anonymized)
python scanner.py https://example.com -t

# Custom output file
python scanner.py https://example.com -o results.json

# Run the web interface
python app.py
```

---

## 📁 Project Structure

```
ThreatLensX/
├── app.py              # Web interface / Flask dashboard
├── scanner.py          # Core scanning engine
├── config.py           # Configuration and API keys
├── requirements.txt    # Python dependencies
└── README.md
```

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Tor](https://img.shields.io/badge/Tor-7D4698?style=for-the-badge&logo=torproject&logoColor=white)
![JSON](https://img.shields.io/badge/JSON_Export-000000?style=for-the-badge&logo=json&logoColor=white)

</div>

---

## 📊 Capabilities Map

```
ThreatLensX
├── Passive Reconnaissance
│   ├── WHOIS / DNS Enumeration
│   ├── SSL/TLS Certificate Analysis
│   └── OSINT Gathering
├── Active Scanning
│   ├── Web Crawling (configurable depth)
│   ├── WAF Detection
│   ├── Security Headers Audit
│   └── Vulnerability Detection (CVE/CVSS)
├── Threat Intelligence
│   ├── IP Geolocation & ASN Lookup
│   └── Dark Web Scanning (Tor)
└── Reporting
    └── JSON Export → SIEM Integration
```

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 👤 Author

**Mohamed Rilwan S** — CEH Certified Cybersecurity Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohamed-rilwan-507337221)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rilwan26)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:smohamedrilwan33@gmail.com)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00ff41,100:0d1117&height=100&section=footer&text=Hack+Responsibly.+Secure+Everything.&fontSize=16&fontColor=00ff41&fontAlignY=65" width="100%"/>

</div>
