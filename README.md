# Cyber Toolkit

A beginner-friendly PowerShell toolkit focused on Windows system administration, network diagnostics, and automation.

This project was built to practice real-world scripting, troubleshooting, and administrative workflows using PowerShell.

---

## Features

### Network & Port Scanning

* Scan common ports on selected targets
* Test connectivity using `Test-NetConnection`
* Resolve DNS records automatically
* Display open/closed ports clearly in the terminal

### LAN Scanner

* Scan devices on the local network
* Detect active hosts
* Resolve hostnames
* Retrieve MAC addresses using ARP
* Generate scan logs automatically

### Logging

* Stores scan activity into log files
* Useful for diagnostics and monitoring

---

## Technologies Used

* PowerShell
* Windows Networking Tools
* DNS Resolution
* ARP Table Parsing
* TCP Connectivity Testing

---

## Current Functions

### `Invoke-Portscan`

Scans selected targets for common ports such as:

* 80 (HTTP)
* 443 (HTTPS)
* 53 (DNS)

Example targets:

* Google
* YouTube
* Microsoft

### `Invoke-LANscan`

Scans the local network (`192.168.1.x`) to:

* Detect online devices
* Resolve hostnames
* Retrieve MAC addresses
* Save results into a log file

---

## Example Usage

# Run a port scan
Invoke-Portscan

# Run LAN scanner
Invoke-LANscan
```

---

## Goals of This Project

This repository is part of my learning journey into:

* System Administration
* Cybersecurity Fundamentals
* Automation
* PowerShell Scripting
* Network Troubleshooting

The toolkit will continue expanding with:

* Better logging
* Remote administration features
* Monitoring tools
* Automation utilities
* Security-focused scripts

---

## Disclaimer

This project is intended for:

* Educational use
* Defensive administration
* Authorized environments only

Do not use these tools on systems or networks without permission.

---

## Future Improvements

* Configurable IP ranges
* Multi-threaded scanning
* Better error handling
* Export results to CSV/JSON
* Service monitoring
* Scheduled automation tasks
* Remote management utilities

---

## Author

Built by Eliraz as part of a hands-on learning journey in IT, automation, and cybersecurity.

