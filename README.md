# Juan Bentancour

**Infrastructure & Network Architect**  
Linux · Network Automation · Cybersecurity · Python · IaC · Edge Computing

I design, operate and automate infrastructure, with a focus on
**reproducible systems, networking, observability and security**.

Most of the projects here started with a real infrastructure problem
and evolved into code, automation or a documented lab.

---

## Selected Projects

### 🐧 [fedora_atomic](https://github.com/jnbntc/fedora_atomic)

OCI-native Fedora Atomic workstation used as a lab for immutable
infrastructure, CI/CD and software supply-chain security.

- Fedora Silverblue / rpm-ostree
- OCI image builds with Podman and Buildah
- functional smoke tests
- SPDX and CycloneDX SBOMs
- Fedora-native security gate
- keyless Cosign signatures with GitHub Actions OIDC
- SLSA provenance and SBOM attestations
- `candidate → stable` promotion flow
- local verified updates pinned by OCI digest
- rollback and periodic disaster-recovery drills

The goal is simple: make the workstation reproducible and make every
important stage produce verifiable evidence.

---

### 🌐 [re-aruba](https://github.com/jnbntc/re-aruba)

Experimental Python management client for **Aruba Instant On 1830**
switches, built by reverse-engineering undocumented HTTP/XML management
endpoints.

The project explores how the switch web interface handles sessions,
authentication and internal management calls, and turns that knowledge
into a usable automation client.

Current capabilities include:

- authenticated session discovery
- querying internal management tables
- system-state changes through the management backend
- JSON exports
- configuration backups
- integration with network automation workflows

This is an experimental client, not an official Aruba/HPE API.

---

### 📦 [distrobox-stack](https://github.com/jnbntc/distrobox-stack)

Declarative technical workspaces for Fedora Atomic using
**Podman, Distrobox and GHCR**.

Instead of installing development and operations toolchains directly on
the host, specialized environments are built and maintained as OCI images.

Current workspaces cover:

- systems administration
- network operations
- security tooling
- reverse engineering
- IoT development
- local AI development
- GNS3 / packet analysis
- ebook and device workflows

The host stays small; technical toolchains live in reproducible containers.

---

### 🔎 [go-netlab](https://github.com/jnbntc/go-netlab)

Lightweight network diagnostics and troubleshooting lab written in Go.

It includes tools for:

- ARP and local network discovery
- TCP/UDP port scanning
- ping and traceroute
- DNS inspection
- DHCP diagnostics
- HTTP header analysis
- Whois / ASN queries

The backend uses Go concurrency while keeping deployment simple:
a single static binary and a server-side rendered web interface.

---

### 📊 [traffic-accident-analysis](https://github.com/jnbntc/traffic-accident-analysis)

Exploratory data analysis and machine-learning work using traffic
accident datasets.

This project belongs to my Data Science learning path and includes work
with Python, Pandas, Jupyter and Scikit-learn.

---

## Current Focus

My current technical interests are mostly around the intersection of
infrastructure, security and software:

- **Immutable and image-based Linux**
- **Network automation and troubleshooting**
- **Infrastructure as Code**
- **Software supply-chain security**
- **Observability and operational tooling**
- **Containers and reproducible workspaces**
- **Edge computing and telemetry**
- **Local AI when data locality or privacy actually matters**

---

## Toolbox

### Infrastructure

`Linux` · `Fedora Atomic` · `Windows Server` · `Proxmox` · `Podman` · `Distrobox`

### Networking & Security

`Aruba` · `Cisco` · `FortiGate` · `MikroTik` · `SNMP` · `LLDP` · `Nmap` · `Tailscale`

### Automation & Development

`Python` · `Bash` · `PowerShell` · `Go` · `Git` · `GitHub Actions`

### Infrastructure & Supply Chain

`OCI` · `rpm-ostree` · `Cosign` · `Sigstore` · `SLSA` · `SBOM`

### Edge & IoT

`ESP32` · `C++` · `MQTT` · `Raspberry Pi`

---

## How I Like to Work

I tend to approach infrastructure with the same questions I would ask
about software:

- Can it be reproduced?
- Can it be versioned?
- Can it be tested?
- Can it be observed?
- Can I verify what is running?
- Can I recover when something goes wrong?

If an operational process is repetitive enough, I usually try to turn it
into code.

---

## Background

I've been working with infrastructure, systems and networking for more
than 20 years across logistics, manufacturing, industrial and energy
environments.

My background ranges from traditional Windows/Linux administration,
routing, switching and security to more recent work around immutable
Linux, containers, automation, edge computing and software supply-chain
security.

I also have a parallel interest in Data Science, Machine Learning and
local LLMs, mainly where they intersect with infrastructure and
automation.

---

## Elsewhere

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Juan_Bentancour-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juanbentancour/)
[![Kaggle](https://img.shields.io/badge/Kaggle-juanbent-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/juanbent)

---

<sub>
When I'm not breaking, rebuilding or automating infrastructure,
I'm probably brewing beer, baking sourdough or playing Argentine folklore on guitar.
</sub>
