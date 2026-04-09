# GCP Sec Scripts

![Security](https://img.shields.io/badge/Security-Tool-red)
![Bash](https://img.shields.io/badge/Bash-Script-green)
![GCP](https://img.shields.io/badge/GCP-Cloud-yellow)
![License](https://img.shields.io/badge/License-MIT-blue)

A collection of Bash scripts for automating security hardening and compliance checks on Google Cloud Platform (GCP) instances. Keeps your GCP infrastructure patched, updated, and aligned with security best practices.

## Description

GCP Sec Scripts automates routine security tasks for GCP compute instances, including system updates, package upgrades, and baseline hardening. Built to run as part of provisioning pipelines or scheduled maintenance windows.

## Features

- Automated system package updates and security patches
- GCP instance hardening automation
- Baseline security configuration enforcement
- Lightweight Bash-based tooling with no external dependencies
- Makefile integration for CI/CD workflows
- Idempotent and safe for repeated execution

## Tech Stack

- **Language:** Bash
- **Platform:** Google Cloud Platform (GCP)
- **Target OS:** Ubuntu / Debian-based Linux
- **Build Tool:** GNU Make

## Quick Start

```bash
# Clone the repository
git clone https://github.com/razinahmed/gcp-sec-scripts.git
cd gcp-sec-scripts

# Review the security script before running
cat scripts/security_core.sh

# Run the security hardening script (requires root privileges)
sudo bash scripts/security_core.sh
```

## Usage

```bash
# Build and test
make build
make test

# Run security hardening
sudo bash scripts/security_core.sh
```

## Project Structure

```
gcp-sec-scripts/
  scripts/
    security_core.sh  # Core security hardening script
  Makefile             # Build and test automation
  SECURITY.md          # Security policy
  LICENSE              # MIT License
```

## Contributing

Contributions are welcome. Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
