
<!-- PROJECT SHIELDS -->
<div align="center">

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-3.0.0-brightgreen)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]()
[![Made with Bash](https://img.shields.io/badge/made%20with-bash-1f425f.svg)](https://www.gnu.org/software/bash/)
[![Powered by AI](https://img.shields.io/badge/powered%20by-AI%2FML-orange)]()
[![Platform](https://img.shields.io/badge/platform-linux%20%7C%20macOS%20%7C%20WSL-lightgrey)]()

</div>

<br />
<p align="center">
  <img src="assets/omniscient-logo.png" alt="Omniscient Logo" width="200"/> <!-- replace with actual logo -->
</p>

<h1 align="center">🛡️ OMNISCIENT V3</h1>
<h3 align="center">Next‑Generation Reconnaissance & Adversary Simulation Framework</h3>

<p align="center">
  A unified, AI‑augmented pipeline that integrates <b>100+ security tools</b>, <br/>
  <b>distributed orchestration</b>, <b>machine learning models</b>, <b>blockchain audit trails</b>, <br/>
  and <b>advanced stealth techniques</b> – built for red teams, bug bounty hunters, and security researchers.
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
- [📂 Output Structure](#-output-structure)
- [🧠 AI Modules](#-ai-modules)
- [🔐 Security & Privacy](#-security--privacy)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)
- [❗ Disclaimer](#-disclaimer)

---

## 🧠 Why Omniscient?

Modern attack surfaces are **massive** and constantly shifting. Traditional recon workflows are fragmented, slow, and miss critical blind spots. Omniscient V3 solves this by:

- **Unifying 100+ best-of-breed tools** (Amass, Nuclei, Metasploit, Nmap, SQLMap, etc.) under a single execution graph.
- **Augmenting results with AI** – GANs for subdomain/endpoint generation, reinforcement learning for exploit chaining, and deep‑learning vulnerability scoring.
- **Distributing tasks** across Kubernetes, AWS Lambda, or Docker Swarm for **blazing‑fast parallel scans**.
- **Providing immutable audit trails** via blockchain‑anchored logs (Ethereum), crucial for red‑team engagements and compliance.
- **Embedding advanced stealth** – proxy chaining, post‑quantum encryption, anti‑WAF fingerprinting, and traffic mimicry – to emulate real‑world adversaries.

---

## ✨ Features

<details open>
<summary><b>🔍 Reconnaissance & Discovery</b></summary>
<br>

- **Subdomain enumeration** – Amass, Subfinder, Chaos, DNSx, Puredns  
- **URL & endpoint discovery** – GAU, Katana, Gospider, Wayback, ParamSpider  
- **Network scanning** – Nmap, Masscan, Rustscan, Zmap, DNSRecon  
- **Cloud & container security** – CloudSploit, Trivy, Scout, Kube‑Hunter  
- **IoT/OT fingerprinting** – Shodan, Censys, Fingerprintx  
- **Dark web monitoring** (Tor‑enabled scraping)  
- **Supply chain analysis** – Grype, Syft, Deps.dev, SBOM generation  
- **Blockchain & Web3 intelligence**

</details>

<details>
<summary><b>🧠 AI‑Augmented Analysis</b></summary>
<br>

- **GAN‑powered subdomain permutation** – generate realistic, never‑seen subdomains  
- **Endpoint prediction** – ML‑based API path and parameter guessing  
- **Zero‑day prioritization** – reinforcement learning models that predict exploitability  
- **Exploit chaining** – automated correlation of vulnerabilities for multi‑step attacks  
- **Dynamic risk scoring** – context‑aware vulnerability scoring (CVSS + custom AI models)  
- **Resource optimization** – real‑time thread/GPU scaling based on system load and model inference

</details>

<details>
<summary><b>🚀 Distributed & High‑Performance</b></summary>
<br>

- **Orchestration backends**: Kubernetes (Helm chart included), Slurm, AWS Lambda, Docker Swarm  
- **GPU/TPU acceleration** for AI models (CUDA, TensorRT, Coral)  
- **Redis‑backed distributed caching** for deduplication and speed  
- **eBPF kernel‑level monitoring** for container and network insights  
- **Adaptive threading** – automatically scales concurrent tasks without overwhelming the system

</details>

<details>
<summary><b>🛡️ Stealth & Evasion</b></summary>
<br>

- **Tor & proxy chaining** – randomized elite proxies with automatic rotation  
- **Anti‑WAF & fingerprint obfuscation** – header randomization, JA3/JARM spoofing  
- **Post‑quantum encryption** – Kyber‑1024 for key exchange, AES‑384 for data  
- **Steganographic exfiltration** – hide data in images or network traffic  
- **Signature obfuscation** – on‑the‑fly payload mutation (educational mode)

</details>

<details>
<summary><b>📜 Logging & Compliance</b></summary>
<br>

- **JSONL structured logging** with chain‑of‑trust hashing (SHA‑256)  
- **Blockchain tamper‑proof auditing** – anchor hashes to Ethereum smart contracts  
- **Automatic scope validation** against HackerOne, Bugcrowd, Intigriti, YesWeHack  
- **Pre‑built compliance reports** aligned with NIST 800‑53, GDPR, CCPA, ISO 27001

</details>

<details>
<summary><b>📊 Reporting & Integration</b></summary>
<br>

- **Multi‑format exports**: PDF, JSON, CSV, HTML, interactive graphs, VR (Blender)  
- **Real‑time dashboards** (web‑based, 3D topology maps)  
- **SIEM & SOAR integration**: Slack, Discord, Teams, Splunk, ELK webhooks

</details>

<details>
<summary><b>⚔️ Simulated Adversary Capabilities (Educational / Authorized Only)</b></summary>
<br>

All offensive modules are **disabled by default** and require explicit activation.

- Automated exploitation (Metasploit, SQLMap, Nuclei templates with RCE)  
- Credential harvesting & lateral movement simulation  
- Persistence mechanisms (scheduled tasks, WMI, cron)  
- C2 beaconing (HTTP/HTTPS/DNS) for red‑team exercises  

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

· Operating System: Linux (Kali, Ubuntu 20.04+, Parrot, Debian) – macOS/WSL supported with limitations
· Architecture: x86_64 (ARM64 supported for most tools)
· Dependencies: 100+ external tools – see REQUIRED_TOOLS array inside the script
· API Keys (optional, but highly recommended for full power):
  · Shodan, ZoomEye, Censys, SecurityTrails, VirusTotal, GreyNoise, OTX, BinaryEdge, Netlas, etc.
· Hardware Minimum: 8 GB RAM, 4 CPU cores, 50 GB free disk
· GPU (optional): NVIDIA GPU with CUDA 11+ for AI acceleration
· Tor (optional): for anonymous routing and dark web modules

</details>

---

🔧 Installation

1. System Dependencies

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install -y curl wget git jq nmap masscan whois dnsutils parallel tor proxychains
```

2. Install Go (required for many modern security tools)

```bash
wget https://go.dev/dl/go1.22.5.linux-amd64.tar.gz
sudo rm -rf /usr/local/go && sudo tar -C /usr/local -xzf go1.22.5.linux-amd64.tar.gz
echo 'export PATH=$PATH:/usr/local/go/bin:$HOME/go/bin' >> ~/.bashrc
source ~/.bashrc
```

3. Install Core Recon Tools (example subset)

```bash
# ProjectDiscovery suite
go install -v github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
go install -v github.com/projectdiscovery/httpx/cmd/httpx@latest
go install -v github.com/projectdiscovery/nuclei/v3/cmd/nuclei@latest
go install -v github.com/projectdiscovery/katana/cmd/katana@latest
go install -v github.com/projectdiscovery/naabu/v2/cmd/naabu@latest

# Other essentials
go install -v github.com/tomnomnom/assetfinder@latest
go install -v github.com/lc/gau/v2/cmd/gau@latest
go install -v github.com/hakluke/hakrawler@latest
```

💡 Full tool list and auto‑installation – the script will install missing tools automatically using apt, go install, or pip.
Some commercial tools (Burp Suite, Metasploit Pro) must be installed manually.

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
# ... add more as needed
```

Then source it before running the tool: source /etc/recon_api_keys.conf.

Advanced Key Storage: HashiCorp Vault, YubiKey OATH‑TOTP, or HSM integration is also supported (see Configuration).

---

⚙️ Configuration

All behaviour is controlled via environment variables. Export them before execution or set them inline.

Variable Description Default
THREADS Number of parallel threads 5000
RESOLVERS Comma‑separated DNS resolvers 8.8.8.8,1.1.1.1,9.9.9.9
OUTPUT_DIR Base output directory recon-<timestamp>
ENCRYPT_DUMPS AES‑384 encrypt sensitive outputs true
SLACK_WEBHOOK Slack incoming webhook URL (none)
DISCORD_WEBHOOK Discord webhook URL (none)
VAULT_ADDR HashiCorp Vault address http://127.0.0.1:8200
VAULT_TOKEN Vault authentication token (none)
KEYBASE_USER Keybase user for key exchange (none)
YUBIKEY_ID YubiKey OATH ID for TOTP (none)
HSM_DEVICE HSM device path /dev/hsm0
TOR_ENABLED Route all traffic through Tor true
STEALTH_MODE Enable anti‑detection (random UA, proxy rotation) true
DISTRIBUTED_MODE Distribute tasks across a cluster true
GPU_ENABLED Use GPU for AI models true
AI_MODEL_DIR Path to custom AI model scripts /opt/ai_models
C2_SERVER C2 server for beaconing (red‑team) (empty, disabled)
PERSISTENCE_ENABLED Enable persistence mechanisms (educational) false
SUPPLY_CHAIN_SCAN Perform supply chain analysis true
QUANTUM_SIGN Use Kyber‑1024 quantum‑safe signatures true

📘 Full list of over 60 tunable parameters is documented in the script header.

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

📂 Output Structure

All results are neatly organised in a timestamped directory:

```
recon-20260116-120000/
├── subdomains/          # Live subdomains, permutations, resolved IPs
├── urls/                # Live URLs, historical endpoints, parameterized URLs
├── vulns/               # Nuclei results, custom AI risk scores (JSON, HTML)
├── network/             # Nmap/Masscan XML, service banners, OS detection
├── cloud/               # Misconfigurations, IAM policy issues
├── containers/          # Docker/K8s vulnerabilities (Trivy, Kube‑Hunter)
├── iot_ot/              # IoT/OT device fingerprints and known CVEs
├── darkweb/             # Mentions on Tor sites (requires Tor)
├── supply_chain/        # SBOM (CycloneDX/SPDX), dependency vulnerabilities
├── blockchain/          # Wallet analysis, smart contract interactions
├── osint/               # Email addresses, employees, social media profiles
├── repos/               # GitHub/GitLab leaks, secrets, keys
├── exploits/            # Verified exploit chains, C2 logs (if enabled)
├── logs/                # Audit trail (JSONL), signature chains
├── screenshots/         # Web page screenshots (Aquatone/Gowitness)
├── reports/             # Final reports (PDF, JSON, CSV, HTML, interactive)
└── recon.jsonl          # Structured event log with chain‑of‑trust hashing
```

---

🧠 AI Modules

Omniscient expects optional Python scripts inside AI_MODEL_DIR (default /opt/ai_models):

Script Purpose
subdomain_gan.py GAN‑based subdomain generation and validation
endpoint_gan.py Predict likely API endpoints and parameters
vuln_gan.py Correlate vulnerabilities and suggest exploit chains
exploit_gan.py Reinforcement learning for automated exploitation
risk_scorer.py Dynamic, context‑aware vulnerability prioritization
resource_optimizer.py Auto‑scale threads and GPU usage based on load

If GPU_ENABLED=true and a CUDA‑capable device is detected, these models will automatically leverage hardware acceleration.

🧪 Custom Models: You can drop your own .py files in the directory – they will be imported and called at the appropriate pipeline stages.

---

🔐 Security & Privacy

· Encryption at rest: All sensitive outputs (reports, dumps, keys) can be encrypted with AES‑384 and signed with Kyber‑1024 quantum‑safe algorithms.
· Immutable audit logs: Every action is hashed (SHA‑256) and the chain of hashes can be anchored to an Ethereum smart contract, providing tamper‑proof evidence for engagements.
· Credential management: API keys are never stored in plaintext. Use HashiCorp Vault, YubiKey TOTP, HSM, or file‑based (mode 600) with optional GPG encryption.
· Key exchange: Securely share session keys via Keybase or HSM‑backed channels.
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
