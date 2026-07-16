
<div align="center">

# 🛡️ OMNISCIENT V3

### The Ultimate Reconnaissance & Adversary Simulation Framework

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-3.0.0-brightgreen)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]()
[![Bash](https://img.shields.io/badge/made%20with-bash-1f425f.svg)](https://www.gnu.org/software/bash/)
[![AI Powered](https://img.shields.io/badge/AI%2FML-Powered-orange)]()
[![Platform](https://img.shields.io/badge/platform-linux%20%7C%20WSL-lightgrey)]()
[![Post-Quantum](https://img.shields.io/badge/Post--Quantum-Ready-9cf)]()
[![Docker](https://img.shields.io/badge/docker-ready-2496ED?logo=docker)]()
[![Kubernetes](https://img.shields.io/badge/kubernetes-ready-326CE5?logo=kubernetes)]()
[![GitHub stars](https://img.shields.io/github/stars/your-org/omniscient?style=social)]()

</div>

---

> ⚠️ **CRITICAL DISCLAIMER**  
> This tool is provided **exclusively** for **authorised security assessments**, **educational use**, and **bug bounty engagements** where you have **explicit written permission** to test.  
> Unauthorised scanning, exploitation, or data exfiltration violates the **Computer Fraud and Abuse Act (CFAA)**, **GDPR**, and similar laws worldwide.  
> **The developers assume zero liability for misuse. Always obtain proper approval before targeting any system.**

---

## 📖 Table of Contents

- [🌟 Why Omniscient?](#-why-omniscient)
- [🚀 Key Features](#-key-features)
- [📸 Visual Pipeline](#-visual-pipeline)
- [⚡ Quick Start](#-quick-start)
- [📦 Requirements](#-requirements)
- [🔧 Installation](#-installation)
- [⚙️ Configuration](#️-configuration)
- [📘 Usage & Examples](#-usage--examples)
- [🔄 Reconnaissance Phases](#-reconnaissance-phases)
- [🧠 AI & Machine Learning](#-ai--machine-learning)
- [🌐 Distributed Execution](#-distributed-execution)
- [📊 Reporting & Visualisation](#-reporting--visualisation)
- [📂 Output Structure](#-output-structure)
- [🔐 Security, Privacy & Compliance](#-security-privacy--compliance)
- [❓ Troubleshooting](#-troubleshooting)
- [🤝 Contributing & Support](#-contributing--support)
- [📜 License](#-license)
- [❗ Final Disclaimer](#-final-disclaimer)

---

## 🌟 Why Omniscient?

Modern attack surfaces are **massive**, **dynamic**, and **increasingly complex**. Traditional reconnaissance workflows are:

- **Fragmented** – juggling dozens of tools, each with its own output format.
- **Slow** – sequential execution wastes time and resources.
- **Incomplete** – blind spots in cloud, IoT, supply chain, and dark web.
- **Non‑auditable** – no immutable record of actions for compliance or red‑team reporting.

**Omniscient V3** solves these challenges by:

- **Unifying 130+ best‑of‑breed security tools** into a single, cohesive pipeline.
- **Augmenting results with AI** – using GANs, reinforcement learning, and deep neural networks to predict subdomains, endpoints, vulnerabilities, and exploit chains.
- **Distributing workloads** across Kubernetes, AWS Lambda, Docker Swarm, or Slurm for **massive parallelisation**.
- **Embedding advanced stealth** – Tor, proxy chaining, post‑quantum encryption (Kyber‑1024), and steganography to emulate sophisticated adversaries.
- **Providing immutable audit trails** via blockchain‑anchored logs (Ethereum smart contracts) – essential for red‑team engagements and regulatory compliance.
- **Self‑healing orchestration** with dynamic thread scaling, eBPF kernel monitoring, and Apache Airflow integration.

Whether you're a **bug bounty hunter**, **red teamer**, **security researcher**, or **DevSecOps engineer**, Omniscient gives you the edge to discover vulnerabilities faster, deeper, and more reliably than ever before.

---

## 🚀 Key Features

<table>
<tr>
<td width="50%">

#### 🔍 **Hyper‑Deep Reconnaissance**
- **Subdomain enumeration** – 20+ tools (Amass, Subfinder, Chaos, Shodan, Censys…)
- **URL/endpoint discovery** – GAU, Katana, Wayback, ParamSpider, Arjun, API‑Scout…
- **Network scanning** – Nmap, Masscan, Rustscan, Zmap, DNSRecon, WAFW00F…
- **Vulnerability scanning** – Nuclei (60+ templates), Dalfox, Nikto, ZAP, Xray, Arachni…
- **Cloud & container** – CloudSploit, Trivy, ScoutSuite, Kube‑Hunter, Docker Bench…
- **IoT/OT discovery** – Shodan, Censys, Fingerprintx, SCADA scripts
- **Dark web & deep web** – Tor‑enabled scraping of .onion leak sites and marketplaces
- **Supply chain analysis** – SBOM generation (Grype, Syft), dependency risk scoring
- **Blockchain intelligence** – Bitcoin/Ethereum address tracking, transaction analysis

</td>
<td width="50%">

#### 🧠 **AI‑Augmented Analysis**
- **GAN‑powered subdomain permutations** – generate realistic, unseen subdomains
- **Endpoint prediction** – ML‑based API path and parameter guessing
- **Zero‑day prioritisation** – reinforcement learning models that predict exploitability
- **Automated exploit chaining** – AI correlates vulnerabilities for multi‑step attacks
- **Dynamic risk scoring** – context‑aware scoring combining CVSS, dark web mentions, supply chain risks
- **Deepfake OSINT detection** – identify synthetic media threats
- **Resource optimisation** – real‑time thread/GPU scaling based on system load

</td>
</tr>
<tr>
<td width="50%">

#### 🚀 **Distributed & High‑Performance**
- **Orchestration backends**: Kubernetes, Slurm, AWS Lambda, Docker Swarm, Airflow
- **GPU/TPU acceleration** – CUDA, TensorRT, Coral for lightning‑fast AI inference
- **Redis‑backed distributed caching** – deduplication and speed
- **eBPF kernel‑level monitoring** – container and network insights
- **Adaptive threading** – automatically scales concurrent tasks without overwhelming the system

</td>
<td width="50%">

#### 🛡️ **Stealth & Evasion**
- **Tor & proxy chaining** – randomised elite proxies with automatic rotation
- **Anti‑WAF & fingerprint obfuscation** – header randomisation, JA3/JARM spoofing
- **Post‑quantum encryption** – Kyber‑1024 for key exchange, AES‑384 for data
- **Steganographic exfiltration** – hide data in images or network traffic
- **Signature obfuscation** – on‑the‑fly payload mutation (educational mode)

</td>
</tr>
<tr>
<td width="50%">

#### 📜 **Blockchain Auditing & Compliance**
- **JSONL structured logging** with chain‑of‑trust hashing (SHA‑512)
- **Ethereum smart contract** – anchor hashes for tamper‑proof audit trails
- **Automatic scope validation** against HackerOne, Bugcrowd, Intigriti, YesWeHack
- **Pre‑built compliance reports** aligned with NIST 800‑53, GDPR, CCPA, ISO 27001

</td>
<td width="50%">

#### 📊 **Multi‑Format Reporting**
- **Exports**: PDF, JSON, CSV, HTML, interactive graphs, VR (Blender)
- **Real‑time dashboards** – web‑based, 3D topology maps
- **SIEM & collaboration**: Slack, Discord, Teams, Splunk, ELK webhooks

</td>
</tr>
</table>

---

## 📸 Visual Pipeline

```

┌─────────────────────────────────────────────────────────────────────┐
│                        OMNISCIENT V3 PIPELINE                       │
├─────────────────────────────────────────────────────────────────────┤
│  [Phase 1]  Setup & Tool Check   →  Install missing tools, load plugins, init cache │
│  [Phase 2]  Compliance Check     →  Validate against bug bounty scopes             │
│  [Phase 3]  Subdomain Enum       →  20+ tools + AI GAN permutations                │
│  [Phase 4]  URL Discovery        →  Live hosts, endpoints, JS analysis, API guessing│
│  [Phase 5]  Network Recon        →  Port scan, service detection, WAF fingerprint   │
│  [Phase 6]  Vulnerability Scan   →  Nuclei, Dalfox, Nikto, ZAP, CVE correlation     │
│  [Phase 7]  Cloud/Container      →  CloudSploit, Trivy, Scout, Kube‑Hunter         │
│  [Phase 8]  Exploit Validation   →  SQLi, RCE, Metasploit, C2 (if enabled)          │
│  [Phase 9]  Threat Intelligence  →  OTX, VT, GreyNoise, Censys, Recorded Future     │
│  [Phase 10] OSINT & Social       →  TheHarvester, Maltego, Deepfake detection       │
│  [Phase 11] Code Repo Scan       →  TruffleHog, Gitleaks, Semgrep, dependency scan  │
│  [Phase 12] Dark Web             →  Tor‑enabled leak and marketplace searches        │
│  [Phase 13] IoT/OT Discovery     →  Shodan/Censys for ICS/SCADA                     │
│  [Phase 14] Supply Chain & Block →  SBOM, dependency risks, crypto tracking          │
│  [Phase 15] Reporting & Stegano  →  Generate encrypted reports, optional exfil      │
└─────────────────────────────────────────────────────────────────────┘

```

All phases run in parallel where possible, with dynamic thread allocation and Redis‑based caching for optimal speed.

---

## ⚡ Quick Start

```bash
# 1. Clone and set permissions
git clone https://github.com/your-org/omniscient.git
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

· Operating System: Linux (Kali, Ubuntu 20.04+, Parrot, Debian) – WSL2 supported with limitations.
· Architecture: x86_64 (ARM64 supported for most tools).
· Dependencies: 130+ external tools – see REQUIRED_TOOLS inside the script. The script auto‑installs missing ones.
· API Keys (optional, but highly recommended for full power):
  · Shodan, ZoomEye, Censys, SecurityTrails, VirusTotal, GreyNoise, OTX, BinaryEdge, Netlas, Recorded Future, ThreatConnect, Dark Web API, etc.
· Hardware Minimum: 8 GB RAM, 4 CPU cores, 50 GB free disk.
· GPU (optional): NVIDIA GPU with CUDA 11+ for AI acceleration.
· Tor (optional): for anonymous routing and dark web modules.
· Wordlists: Place your custom wordlists in /opt/wordlists (subdomain, permutation, directory, user/pass lists).

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
SLACK_WEBHOOK Slack incoming webhook URL (empty)
DISCORD_WEBHOOK Discord webhook URL (empty)
SIEM_WEBHOOK SIEM/Webhook endpoint for real‑time events (empty)
API_KEYS_FILE Path to API keys file /etc/recon_api_keys.conf
VAULT_ADDR HashiCorp Vault address http://127.0.0.1:8200
VAULT_TOKEN Vault authentication token (empty)
KEYBASE_USER Keybase user for key exchange (empty)
YUBIKEY_ID YubiKey OATH ID for TOTP (empty)
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

📘 Usage & Examples

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

Scheduled Scans (Airflow)

If SCHEDULE_MODE=true, the script registers a DAG in Airflow for recurring scans. You can then trigger it via the Airflow UI or API.

---

🔄 Reconnaissance Phases

The script executes a comprehensive 14‑phase pipeline (plus reporting), each with multiple parallel tasks:

Phase Name Description
1 Setup & Tool Check Auto‑install missing tools, load plugins, initialise directories and Redis caching.
2 Compliance Check Validate targets against HackerOne, Bugcrowd, Intigriti, YesWeHack scopes.
3 Subdomain Enumeration 20+ tools including AI‑driven GAN permutations.
4 URL & Endpoint Discovery Live host probing, historical URL extraction, JS analysis, API endpoint guessing.
5 Network Reconnaissance Mass port scanning, service detection, WAF fingerprinting, traceroute.
6 Vulnerability Scanning Multitude of scanners (Nuclei, Dalfox, Nikto, Zap, etc.) with CVE correlation.
7 Cloud & Container Scanning CloudSploit, Trivy, ScoutSuite, Kube‑Hunter, Docker benchmarks.
8 Exploit Validation & Malicious Ops SQLi, RCE verification; C2 beaconing and persistence (if enabled).
9 Threat Intelligence OTX, VirusTotal, GreyNoise, Censys, Recorded Future, ThreatConnect, dark web.
10 OSINT & Social Media Recon TheHarvester, Recon‑NG, Maltego, Deepfake detection.
11 Code Repository Scanning TruffleHog, Gitleaks, Semgrep, dependency scanning.
12 Dark Web Scanning Tor‑enabled search for leaks, marketplace mentions.
13 IoT/OT Discovery Shodan/Censys for ICS/SCADA, Modbus enumeration.
14 Supply Chain & Blockchain Analysis SBOM generation, dependency vulnerability check, crypto address tracking.
15 Reporting & Steganography Generate encrypted reports in multiple formats; optional steganographic exfiltration of findings.

All phases run in parallel where possible, with dynamic thread allocation and Redis‑based caching for optimal speed.

---

🧠 AI & Machine Learning

Omniscient integrates AI/ML at multiple levels:

Module Technology Purpose
Subdomain Permutation Generative Adversarial Networks (GAN) Generate realistic, never‑seen subdomains from seed data.
Endpoint Prediction Neural Networks Predict API endpoints, parameters, and hidden paths.
Vulnerability Prioritisation Reinforcement Learning Rank vulnerabilities by exploitability and business impact.
Exploit Chaining Graph Neural Networks Link vulnerabilities into multi‑step attack paths.
Risk Scoring Ensemble Models Combine CVSS, dark web mentions, and supply chain data.
Deepfake OSINT Convolutional Neural Networks (CNN) Detect manipulated media (images, audio).
Resource Optimisation Regression Models Auto‑scale threads, GPU/TPU usage based on load.

Custom AI models can be dropped into AI_MODEL_DIR and are automatically invoked if they match the expected filenames. GPU/TPU acceleration is enabled via GPU_ENABLED and TPU_ENABLED.

---

🌐 Distributed Execution

Omniscient can scale horizontally across clusters:

· Kubernetes – Helm chart included; spawns parallel pods.
· Slurm – For HPC environments.
· AWS Lambda – Serverless function execution.
· Docker Swarm – Containerised workers.
· Apache Airflow – Orchestrate complex DAGs.

Set DISTRIBUTED_MODE=true and choose a backend via DISTRIBUTED_BACKEND (default: auto‑detect).
Tasks are distributed at the phase level, with each worker handling a subset of targets or tools.

---

📊 Reporting & Visualisation

Omniscient generates rich reports in multiple formats:

· PDF – Professional, printable reports with executive summaries.
· HTML – Interactive dashboards with filters and drill‑downs.
· JSON/CSV – Machine‑readable for SIEM ingestion and further analysis.
· Graph – Network topology maps (Neo4j export).
· VR – Blender‑ready 3D visualisations of attack surfaces.

Real‑time notifications can be pushed to Slack, Discord, Teams, or any SIEM endpoint via webhooks.

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

🔐 Security, Privacy & Compliance

· Encryption at rest: All sensitive outputs (reports, dumps, keys) are encrypted with AES‑384. Quantum‑safe Kyber‑1024 signatures are used for critical exchanges.
· Immutable audit logs: Every action is hashed (SHA‑512) and the chain can be anchored to an Ethereum smart contract, providing tamper‑proof evidence.
· Credential management: API keys are never stored in plaintext. Use HashiCorp Vault, YubiKey TOTP, HSM, or file‑based (mode 600) with optional GPG encryption.
· Key exchange: Securely share session keys via Keybase or HSM‑backed channels.
· Steganographic exfiltration: Results can be hidden in innocent‑looking images and sent to a C2 server (educational).
· No phone‑home: The tool does not transmit any telemetry. All data stays local or within your controlled infrastructure.
· Compliance: Automatic scope validation against bug bounty platforms and built‑in alignment with NIST 800‑53, GDPR, CCPA, ISO 27001.

---

❓ Troubleshooting

Issue Solution
Missing tools The script attempts auto‑install. If a tool fails, install it manually and ensure it’s in $PATH.
Redis connection refused Ensure Redis is running: sudo systemctl start redis-server. If using cluster, check configuration.
Tor not working Verify Tor is installed and running: sudo systemctl start tor. For dark web modules, ensure torify is functional.
GPU not detected Check NVIDIA drivers and CUDA version. Set GPU_ENABLED=false to fallback to CPU.
Out of memory Reduce THREADS or limit concurrency via RATE_LIMIT.
API key errors Verify keys are correctly exported and have necessary permissions. Use log_json to see detailed errors.
Permission denied Ensure script and output directories have proper ownership: sudo chown -R $USER:$USER ..
Slow performance Enable distributed mode, increase Redis cache size, or reduce the number of phases if not needed.

For further assistance, open an issue on GitHub or consult the internal logging (logs/recon.log).

---

🤝 Contributing & Support

We welcome contributions from the community! Whether it's a bug fix, new feature, documentation improvement, or even a new AI model, your help is appreciated.

How to Contribute

1. Fork the repository.
2. Create a feature branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a Pull Request.

Please ensure your code is well‑documented and includes test cases where applicable.

Support

· 📧 Email: aliheydari1381doc@gmail.com 
· 💬 github: Ali-hey-0 
· 🐛 telegram: ali_heyda
· 📚 Documentation: Wiki

Sponsors

If you find Omniscient useful, consider sponsoring the project to support ongoing development and maintenance.

---

📜 License

Distributed under the MIT License. See LICENSE for more information.
This project is intended for educational and authorised research purposes only.

---

❗ Final Disclaimer

```text
THIS TOOL IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.
THE AUTHORS AND CONTRIBUTORS DISCLAIM ALL LIABILITY FOR ANY DAMAGES OR MISUSE.
USAGE OF THIS TOOL FOR UNAUTHORISED ACCESS TO SYSTEMS IS ILLEGAL AND STRICTLY PROHIBITED.
BY USING THIS SOFTWARE, YOU AGREE THAT YOU ARE SOLELY RESPONSIBLE FOR YOUR ACTIONS
AND WILL COMPLY WITH ALL APPLICABLE LAWS AND REGULATIONS.
```

---

<p align="center">
  <b>🧠 Happy (and ethical) hacking!</b>
</p>
