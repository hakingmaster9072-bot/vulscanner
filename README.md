# vulscanner
Python-based vulnerability scanner with port scanning, OS detection, service detection, CVE analysis, and automated security reporting.
# 🔐 Python Vulnerability Scanner

A Python-based network vulnerability scanner built with **Nmap** for authorized security testing, CTFs, and lab environments.

## 🚀 Features

* 🔎 Common TCP port scanning
* 🌐 Full TCP port scanning (`1-65535`)
* 🎯 Custom port-range scanning
* 🧩 Service and version detection
* 🖥️ Operating System detection
* 🛡️ CVE vulnerability checking using the NVD database
* 📊 Vulnerability analysis
* 📝 Automatic TXT reports
* 📦 Automatic JSON reports
* ⚡ Nmap-based scanning with service detection

## 🛠️ Requirements

* Python 3
* Nmap
* `requests` Python package
* Linux / Kali Linux recommended

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/vulnerability-scanner.git
cd vulnerability-scanner
```

Install the required Python package:

```bash
pip3 install requests
```

Make sure Nmap is installed:

```bash
sudo apt update
sudo apt install nmap
```

Check the installation:

```bash
nmap --version
```

## ▶️ Usage

Run the scanner:

```bash
sudo python3 scanner.py
```

The scanner provides three options:

```text
1. Common ports
2. All TCP ports
3. Custom port range
```

### Example

```text
Target IP: 10.48.128.127

1. Common ports
2. All TCP ports
3. Custom port range
```

Select the required scan type and follow the prompts.

## 📋 Reports

After scanning, reports are automatically generated in the `reports/` directory.

Example:

```text
reports/
├── TARGET_report.txt
└── TARGET_report.json
```

The reports can contain:

* Open ports
* Detected services
* Service versions
* Operating system information
* Potential CVE matches
* Scan details

## ⚠️ Disclaimer

This tool is intended **only for authorized security testing, CTFs, and controlled lab environments**.

Do not scan systems or networks without proper authorization. The author is not responsible for misuse or damage caused by this tool.

## 📌 Project Status

This project is currently under development and may receive additional improvements in future versions.

## 👨‍💻 Author

**JUDE JACOB**
