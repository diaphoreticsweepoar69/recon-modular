
<!-- PROJECT SHIELDS -->
<div align="center">

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-3.0.0-brightgreen)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]()
[![Bash](https://img.shields.io/badge/made%20with-bash-1f425f.svg)](https://www.gnu.org/software/bash/)
[![AI Powered](https://img.shields.io/badge/AI%2FML-Powered-orange)]()
[![Platform](https://img.shields.io/badge/platform-linux%20%7C%20WSL-lightgrey)]()

</div>

<br />
<p align="center">
  <img src="assets/omniscient-logo.png" alt="Omniscient Logo" width="200"/> <!-- replace with your own -->
</p>

<h1 align="center">🛡️ OMNISCIENT V3</h1>
<h3 align="center">Next‑Generation Reconnaissance & Adversary Simulation Framework</h3>

<p align="center">
  A unified, AI‑augmented pipeline integrating <b>130+ security tools</b>, <br/>
  <b>distributed orchestration</b>, <b>generative AI models</b>, <b>blockchain audit trails</b>, <br/>
  and <b>post‑quantum stealth</b> – built for red teams, bug bounty hunters, and security researchers.
</p>

<br/>

> ⚠️ **CRITICAL DISCLAIMER**  
> This tool is provided **exclusively** for **authorised security assessments**, **educational use**, and **bug bounty engagements** where you have **explicit written permission** to test.  
> Unauthorised scanning, exploitation, or data exfiltration violates the **Computer Fraud and Abuse Act (CFAA)**, **GDPR**, and similar laws worldwide.  
> **The developers assume zero liability for misuse. Always obtain proper approval before targeting any system.**

---

## 📑 Table of Contents

- [Why Omniscient?](#-why-omniscient)
- [✨ Features](#-features)
- [⚡ Quick Start](#-quick-start)
- [📦 Requirements](#-requirements)
- [🔧 Installation](#-installation)
- [⚙️ Configuration](#️-configuration)
- [🚀 Usage](#-usage)
- [🔄 Reconnaissance Phases](#-reconnaissance-phases)
- [📂 Output Structure](#-output-structure)
- [🧠 AI Modules](#-ai-modules)
- [🔐 Security & Privacy](#-security--privacy)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)
- [❗ Disclaimer](#-disclaimer)

---

## 🧠 Why Omniscient?

Modern attack surfaces are **massive** and constantly shifting. Traditional recon workflows are fragmented, slow, and miss critical blind spots. Omniscient V3 solves this by:

- **Unifying 130+ best-of-breed tools** (Amass, Nuclei, Metasploit, Nmap, SQLMap, etc.) under a single execution graph.
- **Augmenting results with AI** – GANs for subdomain/endpoint generation, reinforcement learning for exploit chaining, and deep‑learning vulnerability scoring.
- **Distributing tasks** across Kubernetes, AWS Lambda, or Docker Swarm for **blazing‑fast parallel scans**.
- **Providing immutable audit trails** via blockchain‑anchored logs (Ethereum), crucial for red‑team engagements and compliance.
- **Embedding advanced stealth** – proxy chaining, post‑quantum encryption, anti‑WAF fingerprinting, and steganography – to emulate real‑world adversaries.
- **Self‑healing orchestration** with Apache Airflow, dynamic thread scaling, and eBPF kernel monitoring.

---

## ✨ Features

<details open>
<summary><b>🔍 Hyper‑Deep Reconnaissance</b></summary>
<br>

- **Subdomain enumeration** – Amass, Subfinder, Chaos, DNSx, Puredns, Assetfinder, Findomain, Shodan, ZoomEye, SecurityTrails, Censys, Netlas, BinaryEdge, etc.
- **URL & endpoint discovery** – GAU, Katana, Gospider, Wayback, ParamSpider, Arjun, API‑Scout, Feroxbuster, Dirsearch, Kiterunner.
- **Network scanning** – Nmap (full scripts), Masscan, Rustscan, Zmap, DNSRecon, Fierce, WAFW00F, Fingerprintx, Cloudflare‑scrape.
- **Vulnerability scanning** – Nuclei (60+ templates), Dalfox XSS, Nikto, Wapiti, TestSSL, SSLyze, WhatWeb, JAWS, WPscan, ZAP, Boofuzz, Xray, Arachni, OWASP Nettacker.
- **Cloud & container security** – CloudSploit, Trivy, ScoutSuite (AWS/GCP/Azure), Clair, Docker Bench, Kube‑Hunter, Deepfence, Lynis.
- **IoT/OT discovery** – Shodan, Censys, Fingerprintx, Nmap SCADA scripts.
- **Dark web monitoring** – Tor‑enabled scraping of .onion leak sites, marketplaces, and dark pools.
- **Supply chain analysis** – Grype, Syft SBOM, Deps.dev, AI‑powered dependency risk scoring.
- **Blockchain intelligence** – Address tracking, transaction analysis on Bitcoin/Ethereum.

</details>

<details>
<summary><b>🧠 AI‑Augmented Analysis</b></summary>
<br>

- **GAN‑powered subdomain permutation** – generate realistic, never‑seen subdomains.
- **Endpoint prediction** – ML‑based API path and parameter guessing.
- **Zero‑day prioritisation** – reinforcement learning models that predict exploitability.
- **Automated exploit chaining** – AI correlates vulnerabilities for multi‑step attacks.
- **Dynamic risk scoring** – context‑aware scoring combining CVSS, dark web mentions, supply chain risks.
- **Deepfake OSINT detection** – identify synthetic media threats.
- **Resource optimization** – real‑time thread/GPU scaling based on system load and model inference.

</details>

<details>
<summary><b>🚀 Distributed & High‑Performance</b></summary>
<br>

- **Orchestration backends**: Kubernetes (Helm chart included), Slurm, AWS Lambda, Docker Swarm, Airflow.
- **GPU/TPU acceleration** for AI models (CUDA, TensorRT, Coral).
- **Redis‑backed distributed caching** with clustering for deduplication and speed.
- **eBPF kernel‑level monitoring** for container and network insights.
- **Adaptive threading** – automatically scales concurrent tasks without overwhelming the system.

</details>

<details>
<summary><b>🛡️ Stealth & Evasion</b></summary>
<br>

- **Tor & proxy chaining** – randomized elite proxies with automatic rotation.
- **Anti‑WAF & fingerprint obfuscation** – header randomization, JA3/JARM spoofing.
- **Post‑quantum encryption** – Kyber‑1024 for key exchange, AES‑384 for data.
- **Steganographic exfiltration** – hide data in images or network traffic.
- **Signature obfuscation** – on‑the‑fly payload mutation (educational mode).

</details>

<details>
<summary><b>📜 Blockchain Auditing & Compliance</b></summary>
<br>

- **JSONL structured logging** with chain‑of‑trust hashing (SHA‑512).
- **Ethereum smart contract** – anchor hashes for tamper‑proof audit trails.
- **Automatic scope validation** against HackerOne, Bugcrowd, Intigriti, YesWeHack.
- **Pre‑built compliance reports** aligned with NIST 800‑53, GDPR, CCPA, ISO 27001.

</details>

<details>
<summary><b>📊 Multi‑Format Reporting</b></summary>
<br>

- **Exports**: PDF, JSON, CSV, HTML, interactive graphs, VR (Blender).
- **Real‑time dashboards** (web‑based, 3D topology maps).
- **SIEM & collaboration**: Slack, Discord, Teams, Splunk, ELK webhooks.

</details>

<details>
<summary><b>⚔️ Simulated Adversary Capabilities <br/><sub>(Educational / Authorized Only)</sub></b></summary>
<br>

All offensive modules are **disabled by default** and require explicit activation.

- Automated exploitation (Metasploit, SQLMap, Nuclei RCE).
- Credential harvesting & lateral movement simulation (Hydra, Medusa, PSExec).
- Persistence mechanisms (scheduled tasks, WMI, cron, Metasploit backdoors).
- C2 beaconing (HTTP/HTTPS/DNS) for red‑team exercises.

</details>

---

## ⚡ Quick Start

```bash
# 1. Clone and set permissions
git clone https://github.com/your-repo/omniscient.git
cd omniscient && chmod +x recon1.sh

# 2. Export your API keys (optional but recommended)
source /path/to/api_keys.conf   # or use Vault/YubiKey

# 3. Run a full scan on one domain
./recon1.sh example.com

# 4. Run on multiple targets with stealth disabled (internal lab)
TOR_ENABLED=false STEALTH_MODE=false ./recon1.sh internal.example.com
```

On first run, the script will attempt to auto‑install missing tools.
For a controlled installation, follow the full steps below.

---

📦 Requirements

<details>
<summary>Click to expand</summary>
<br>

· Operating System: Linux (Kali, Ubuntu 20.04+, Parrot, Debian) – WSL supported with limitations.
· Architecture: x86_64 (ARM64 supported for most tools).
· Dependencies: 130+ external tools – see REQUIRED_TOOLS inside the script. The script auto‑installs missing ones.
· API Keys (optional, but highly recommended for full power):
  · Shodan, ZoomEye, Censys, SecurityTrails, VirusTotal, GreyNoise, OTX, BinaryEdge, Netlas, Recorded Future, ThreatConnect, Dark Web API, etc.
· Hardware Minimum: 8 GB RAM, 4 CPU cores, 50 GB free disk.
· GPU (optional): NVIDIA GPU with CUDA 11+ for AI acceleration.
· Tor (optional): for anonymous routing and dark web modules.
· Wordlists: Place your custom wordlists in /opt/wordlists (subdomain, permutation, directory, user/pass lists).

</details>

---

🔧 Installation

1. System Dependencies

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install -y curl wget git jq nmap masscan whois dnsutils parallel tor proxychains redis-tools
```

2. Install Go (required for many modern security tools)

```bash
wget https://go.dev/dl/go1.22.5.linux-amd64.tar.gz
sudo rm -rf /usr/local/go && sudo tar -C /usr/local -xzf go1.22.5.linux-amd64.tar.gz
echo 'export PATH=$PATH:/usr/local/go/bin:$HOME/go/bin' >> ~/.bashrc
source ~/.bashrc
```

3. Install Core Recon Tools (example subset)

The script auto‑installs most tools, but you can pre‑install essentials:

```bash
# ProjectDiscovery suite
go install -v github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
go install -v github.com/projectdiscovery/httpx/cmd/httpx@latest
go install -v github.com/projectdiscovery/nuclei/v3/cmd/nuclei@latest
go install -v github.com/projectdiscovery/katana/cmd/katana@latest
go install -v github.com/projectdiscovery/naabu/v2/cmd/naabu@latest
go install -v github.com/projectdiscovery/dnsx/cmd/dnsx@latest

# Other essentials
go install -v github.com/tomnomnom/assetfinder@latest
go install -v github.com/lc/gau/v2/cmd/gau@latest
go install -v github.com/hakluke/hakrawler@latest
```

4. Python AI Dependencies

```bash
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118  # if CUDA 11.8
pip3 install numpy pandas scikit-learn tensorflow onnx redis hiredis
```

5. API Key Configuration

Create a secured file (e.g., /etc/recon_api_keys.conf) with permissions 600:

```bash
export SHODAN_API_KEY="your_key"
export ZOOMEYE_API_KEY="your_key"
export OTX_API_KEY="your_key"
export VT_API_KEY="your_key"
export CENSYS_API_ID="id"
export CENSYS_API_SECRET="secret"
export SECURITYTRAILS_API_KEY="..."
export HIBP_API_KEY="..."
export WPSCAN_API_TOKEN="..."
export HACKERONE_API_TOKEN="..."
export BUGCROWD_API_TOKEN="..."
export RECORDEDFUTURE_API_TOKEN="..."
export THREATCONNECT_API_TOKEN="..."
export NETLAS_API_KEY="..."
export BINARYEDGE_API_KEY="..."
export DARKWEB_API_KEY="..."
# ... add more as needed
```

Then source it: source /etc/recon_api_keys.conf.
Alternatively, use HashiCorp Vault (set VAULT_ADDR and VAULT_TOKEN) or YubiKey OATH‑TOTP (set YUBIKEY_ID). The script will attempt to load keys from the chosen source.

---

⚙️ Configuration

All behaviour is controlled via environment variables. Export them before execution or set them inline.

Variable Description Default
THREADS Number of parallel threads 50000
RESOLVERS Comma‑separated DNS resolvers 8.8.8.8,1.1.1.1,9.9.9.9,…
OUTPUT_DIR Base output directory recon-<timestamp>
ENCRYPT_DUMPS AES‑384 encrypt sensitive outputs true
ENCRYPT_KEY AES key (auto‑generated if not set) random 48 bytes
POST_QUANTUM_KEY Kyber‑1024 key for quantum‑safe ops auto‑generated
SLACK_WEBHOOK Slack incoming webhook URL (none)
DISCORD_WEBHOOK Discord webhook URL (none)
SIEM_WEBHOOK SIEM/Webhook endpoint for real‑time events (none)
API_KEYS_FILE Path to API keys file /etc/recon_api_keys.conf
VAULT_ADDR HashiCorp Vault address http://127.0.0.1:8200
VAULT_TOKEN Vault authentication token (none)
KEYBASE_USER Keybase user for key exchange (none)
YUBIKEY_ID YubiKey OATH ID for TOTP (none)
HSM_DEVICE HSM device path /dev/hsm0
TOR_ENABLED Route all traffic through Tor true
STEALTH_MODE Enable anti‑detection (random UA, proxy rotation) true
OBFUSCATE_FINGERPRINT Randomise TLS/JA3 fingerprints true
DISTRIBUTED_MODE Distribute tasks across a cluster true
GPU_ENABLED Use GPU for AI models true
TPU_ENABLED Use TPU (Coral) for AI acceleration false
AI_MODEL_DIR Path to custom AI model scripts /opt/ai_models
C2_SERVER C2 server for beaconing (red‑team) (empty, disabled)
PERSISTENCE_ENABLED Enable persistence mechanisms (educational) false
SUPPLY_CHAIN_SCAN Perform supply chain analysis true
QUANTUM_SIGN Use Kyber‑1024 quantum‑safe signatures true
STEGANOGRAPHY_ENABLED Enable steganographic exfiltration true
CVE_LOOKUP Perform CVE correlation true
COMPLIANCE_CHECK Validate targets against bug bounty scopes true
SIGN_LOGS Cryptographically sign all logs true
SIGN_KEY RSA‑8192 signing key (auto‑generated) auto‑generated
CACHE_DIR Redis cache directory /tmp/recon_cache
REDIS_HOST Redis host localhost
REDIS_PORT Redis port 6379
REDIS_CLUSTER Enable Redis cluster mode true
RATE_LIMIT Rate limit for scanning tools 1000
TIMEOUT Command timeout 60s
RETRY_COUNT Number of retries on failure 10
REPORT_FORMATS Comma‑separated report formats pdf,json,csv,html,graph,vr
BLIND_XSS Blind XSS callback URL https://your.interact.sh
BLOCKCHAIN_NODE Ethereum node RPC URL http://localhost:8545
SMART_CONTRACT_ADDR Smart contract for audit logging (empty)
SCHEDULE_MODE Scheduled scans via Airflow/cron false
AIRFLOW_HOST Apache Airflow host:port localhost:8080
PLUGIN_DIR Custom plugins directory /opt/recon_plugins

📘 A full list of 60+ tunable parameters is documented in the script header.

---

🚀 Usage

Basic Scan

```bash
./recon1.sh example.com
```

Advanced Examples

```bash
# Run with 10k threads, log output to file
THREADS=10000 ./recon1.sh example.com 2>&1 | tee scan.log

# Target multiple domains, disable Tor (internal network)
TOR_ENABLED=false STEALTH_MODE=false ./recon1.sh internal.corp lab.local

# Fully distributed scan on Kubernetes (requires kubectl and helm)
DISTRIBUTED_MODE=true DISTRIBUTED_BACKEND=k8s ./recon1.sh example.com

# Red‑team simulation with C2 (requires explicit authorisation)
C2_SERVER=10.0.0.50 PERSISTENCE_ENABLED=true EXPLOIT_MODE=true ./recon1.sh authorised-target.local
```

🛑 WARNING: The C2_SERVER, PERSISTENCE_ENABLED, and EXPLOIT_MODE variables activate active attack modules. Never use them without written, legal authorisation.

---

🔄 Reconnaissance Phases

The script executes a comprehensive 14‑phase pipeline:

1. Setup & Tool Check – Auto‑install missing tools, load plugins, initialise directories and Redis caching.
2. Compliance Check – Validate targets against HackerOne, Bugcrowd, Intigriti, YesWeHack scopes.
3. Subdomain Enumeration – 20+ tools including AI‑driven GAN permutations.
4. URL & Endpoint Discovery – Live host probing, historical URL extraction, JS analysis, API endpoint guessing.
5. Network Reconnaissance – Mass port scanning, service detection, WAF fingerprinting, traceroute.
6. Vulnerability Scanning – Multitude of scanners (Nuclei, Dalfox, Nikto, Zap, etc.) with CVE correlation.
7. Cloud & Container Scanning – CloudSploit, Trivy, ScoutSuite, Kube‑Hunter, Docker benchmarks.
8. Exploit Validation & Malicious Ops – SQLi, RCE verification; C2 beaconing and persistence (if enabled).
9. Threat Intelligence – OTX, VirusTotal, GreyNoise, Censys, Recorded Future, ThreatConnect, dark web.
10. OSINT & Social Media Recon – TheHarvester, Recon‑NG, Maltego, Deepfake detection.
11. Code Repository Scanning – TruffleHog, Gitleaks, Semgrep, dependency scanning.
12. Dark Web Scanning – Tor‑enabled search for leaks, marketplace mentions.
13. IoT/OT Discovery – Shodan/Censys for ICS/SCADA, Modbus enumeration.
14. Supply Chain & Blockchain Analysis – SBOM generation, dependency vulnerability check, crypto address tracking.
15. Reporting & Steganography – Generate encrypted reports in multiple formats; optional steganographic exfiltration of findings.

All phases run in parallel where possible, with dynamic thread allocation and Redis‑based caching for optimal speed.

---

📂 Output Structure

All results are neatly organised in a timestamped directory:

```
recon-20260116-120000/
├── subdomains/          # Enumerated subdomains, AI-generated permutations
├── urls/                # Live URLs, endpoints, JS files, API paths
├── vulns/               # All vulnerabilities (Nuclei, XSS, Nikto, etc.)
├── network/             # Port scans, service banners, WAF data, traceroutes
├── cloud/               # Cloud misconfigurations (AWS, GCP, Azure)
├── containers/          # Docker/K8s security reports
├── threat_intel/        # OTX, VirusTotal, GreyNoise, etc.
├── exploits/            # Verified exploits, SQLMap dumps, Metasploit sessions
├── osint/               # Emails, social profiles, deepfake reports
├── repos/               # Leaked secrets, dependency vulnerabilities
├── iot/                 # IoT device fingerprints
├── ot/                  # SCADA/ICS discovery
├── darkweb/             # Tor‑scraped mentions
├── supply_chain/        # SBOM, dependency risks
├── blockchain/          # Crypto transaction analysis
├── logs/                # Signed JSONL audit trail, blockchain hashes
├── screenshots/         # Web page screenshots (Aquatone/Gowitness)
├── reports/             # Final reports (PDF, JSON, CSV, HTML, VR)
└── recon.jsonl          # Structured event log with chain‑of‑trust hashing
```

---

🧠 AI Modules

Omniscient expects optional Python scripts inside AI_MODEL_DIR (default /opt/ai_models). If present and GPU_ENABLED=true, they are automatically invoked:

Script Purpose
subdomain_gan.py GAN‑based subdomain generation and validation
endpoint_gan.py Predict likely API endpoints and parameters
vuln_gan.py Correlate vulnerabilities and suggest exploit chains
exploit_gan.py Reinforcement learning for automated exploitation
risk_scorer.py Dynamic, context‑aware vulnerability prioritization
resource_optimizer.py Auto‑scale threads and GPU usage based on load
deepfake_osint.py Detect deepfake content related to the target
supply_chain_analyzer.py Analyse dependencies for malicious packages
blockchain_analyzer.py Trace cryptocurrency transactions

The script detects available hardware (CUDA, TPU) and passes appropriate flags.

---

🔐 Security & Privacy

· Encryption at rest: All sensitive outputs (reports, dumps, keys) are encrypted with AES‑384. Quantum‑safe Kyber‑1024 signatures are used for critical exchanges.
· Immutable audit logs: Every action is hashed (SHA‑512) and the chain can be anchored to an Ethereum smart contract, providing tamper‑proof evidence.
· Credential management: API keys are never stored in plaintext. Use HashiCorp Vault, YubiKey TOTP, HSM, or file‑based (mode 600) with optional GPG encryption.
· Key exchange: Securely share session keys via Keybase or HSM‑backed channels.
· Steganographic exfiltration: Results can be hidden in innocent‑looking images and sent to a C2 server (educational).
· No phone‑home: The tool does not transmit any telemetry. All data stays local or within your controlled infrastructure.

---

🤝 Contributing

Contributions are what make the open‑source community amazing. Any improvements you make are warmly appreciated.

1. Fork the repository
2. Create a feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

Please ensure your code is well‑documented and includes test cases where applicable.

---

📜 License

Distributed under the MIT License. See LICENSE for more information.
This project is intended for educational and authorised research purposes only.

---

❗ Disclaimer

```text
THIS TOOL IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.
THE AUTHORS AND CONTRIBUTORS DISCLAIM ALL LIABILITY FOR ANY DAMAGES OR MISUSE.
USAGE OF THIS TOOL FOR UNAUTHORISED ACCESS TO SYSTEMS IS ILLEGAL AND STRICTLY PROHIBITED.
BY USING THIS SOFTWARE, YOU AGREE THAT YOU ARE SOLELY RESPONSIBLE FOR YOUR ACTIONS
AND WILL COMPLY WITH ALL APPLICABLE LAWS AND REGULATIONS.
```

<br/>
<p align="center">
  <b>Happy (and ethical) hacking! 🧠🔍</b>
</p>
