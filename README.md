# Open Integrity Project: Documentation - `README.md`
> - _did: `did:repo:9bc5422ae37af0e2adfc2f6a202db259734f0a48/blob/main/README.md`_
> - _github: `https://github.com/OpenIntegrityProject/docs/blob/main/README.md`_
> - _updated: 2025-02-26 by Christopher Allen <ChristopherA@LifeWithAlacrity.com>_

## Introduction

_**Cryptographic Roots of Trust for Open Source Development**_

[![License](https://img.shields.io/badge/License-BSD_2--Clause--Patent-blue.svg)](https://spdx.org/licenses/BSD-2-Clause-Patent.html)
[![Project Status: Active](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![Version](https://img.shields.io/badge/version-0.1.0-blue.svg)](CHANGELOG.md)

**Open Integrity** is an initiative by [Blockchain Commons](https://www.blockchaincommons.com) to integrate cryptographic trust mechanisms into Git repositories. By leveraging Git's native SSH signing capabilities and structured verification processes, we ensure transparency, provenance, and immutability for software projects.

Whether you're a developer, security researcher, or open-source maintainer, Open Integrity provides the tools to:
- Provide a **developer-friendly framework** for cryptographic integrity.
- Establish **verifiable proof-of-origin** for commits and code artifacts through direct verification by inception key holder.
- Expand that proof-of-origin through a **chain of trust** that allows delegated verification of authorized signers.
- Detect **tampering or unauthorized modifications** in repository history.
- Enable **cross-platform trust verification** across Git hosting services

## 🎯 Project Goals

- 🛡 **Immutable Proof-of-Origin** – Verify the authenticity of software artifacts
- 🔏 **Signed Commits & Tags** – Ensure authorship integrity through SSH signatures (~128-bit security).
- 🔍 **Tamper Detection** – Maintain verifiable repository history.
- 🔗 **Trust Delegation** – Enable controlled transition from inception key to authorized signers.
- 🌍 **Platform-Agnostic Validation** – Work across GitHub, GitLab, and self-hosted solutions.

## 📚 Repository Structure

### 📖 Core Documentation
- 📜 [Problem Statement](docs/problem-statement.md) – Challenges & proposed solutions
- 🏛 [Architecture](docs/architecture.md) – System design & implementation details
- 🚀 [Getting Started](docs/getting-started.md) – Quick setup guide
- 🤝 [Contributing Guidelines](CONTRIBUTING.md) – How to contribute
- 🔒 [Security Policy](SECURITY.md) – Reporting vulnerabilities

### 🛠 Implementation
- 📂 [`/scripts`](https://github.com/OpenIntegrityProject/scripts) – Core cryptographic tools & automation scripts (proof-of-concept implementations)
- 🏗 [`/examples`](examples/) – Sample implementations & workflows
- 🔬 [`/tests`](tests/) – Unit and integration tests
- 📑 [`/docs`](docs/) – Technical documentation
- 🌍 [`/website`](website/) – Project website source

### 📌 Project Resources
- 📖 [Documentation Website](https://openintegrity.org)
- 💬 [Community Discussions](../../discussions)
- 🐛 [Issue Tracker](../../issues)
- 📋 [Project Roadmap](../../projects/1)

## 🚀 Quick Start

Follow the [Getting Started Guide](docs/getting-started.md) to:
1. Set up your development environment
2. Create a repository with an inception commit establishing your root of trust
3. Choose your trust model:
   - Direct verification using the inception key
   - OR delegated verification through authorized signers
4. Run integrity audits on existing repositories

For a deeper dive, check out our **[Architecture Overview](docs/architecture.md)**.

## 🔑 Key Features

- **Inception Commits** – Immutable starting points that combine:
  - Empty commit for SHA-1 collision resistance
  - Ricardian Contract defining trust rules
  - SSH signature providing strong cryptographic proof
- **Trust Models**:
  - Direct inception key verification
  - Delegated verification through authorized signers
- **Automated Tamper Detection** – Integrity checks throughout history
- **Cross-Platform Trust** – GitHub, GitLab, or self-hosted support
- **Audit Tools** – Comprehensive repository inspection

## 🚦 Project Status & Roadmap

### **Current Phase: Early Research & Proof-of-Concept (v0.1.0)**
🔹 Core concepts & initial implementation complete  
🔹 Seeking community feedback for improvements  
🔹 Developing integration with CI/CD & key management solutions  
🔹 **Not yet production-ready**  

📍 See our [Development Phases](https://github.com/BlockchainCommons/Community/blob/master/release-path.md) for the full roadmap.

## Documentation Repository Contents

This repository contains the core documentation for the Open Integrity Project:

### Root Directory
- `README.md` - This document, providing an overview of the Open Integrity Project
- `Open_Integrity_Problem_Statement.md` - Comprehensive explanation of the challenges Open Integrity addresses and proposed solutions for establishing cryptographic roots of trust in Git repositories
- `Open_Integrity-CLI_One_Liners.md` - Practical command-line CLI one-liner utilities for creating, inspecting, and managing Open Integrity repositories
- `Open_Integrity_Repo_Directory_Structure.md` - Reference guide for the standard directory structure of Open Integrity-compliant repositories

### Additional Resources (Planned)
- `Open_Integrity_Architecture.md` - Technical design and implementation details
- `Open_Integrity_Getting_Started.md` - Step-by-step tutorial guide to Open Integrity

This documentation hub provides both high-level concepts and practical implementation details to guide users in establishing and maintaining cryptographic trust in their Git repositories.

## 🤝 How to Contribute

We welcome contributions from developers, researchers, and security experts!

1. Read our **[Contributing Guide](CONTRIBUTING.md)**
2. Fork the repository & create a feature branch
3. Implement your feature or fix
4. Submit a **Pull Request** for review

📜 All contributors must adhere to our [Code of Conduct](CODE_OF_CONDUCT.md).

## 🛡 Security & Trust

### Reporting Security Issues

🔒 If you discover a security issue, please report it responsibly:
- **Email**: [team@BlockchainCommons.com](mailto:team@BlockchainCommons.com)
- **GPG Encrypted Reports**: See [SECURITY.md](SECURITY.md) for details

### Security Contacts

| Name              | Email                              | GPG Fingerprint                                     |
|-------------------|------------------------------------|-----------------------------------------------------|
| Christopher Allen | ChristopherA@LifeWithAlacrity.com  | FDFE 14A5 4ECB 30FC 5D22  74EF F8D3 6C91 3574 05ED  |

## 📜 License

All files **BSD 2-Clause Plus Patent License** unless otherwise noted – See [LICENSE](LICENSE) for details.

📖 Open Integrity is an open-source project hosted by [Blockchain Commons](https://www.blockchaincommons.com), dedicated to advancing **secure, transparent, and open digital infrastructure**.

## 🌟 Support Open Integrity

If you find this project valuable, consider:
⭐ Starring the repository  
💬 Engaging in discussions  
📢 Sharing with your network  
💰 Supporting [Blockchain Commons via GitHub Sponsors](https://github.com/sponsors/BlockchainCommons)

For commercial support, visit: **[Blockchain Commons Support](https://www.blockchaincommons.com/support/)**.

## 📞 Contact & Support

- **Security Issues**: [team@BlockchainCommons.com](mailto:team@BlockchainCommons.com)
- **General Questions**: [Community Discussions](../../discussions)
- **Bug Reports**: [Issue Tracker](../../issues)

### **Lead Developer**  
**Christopher Allen** ([@ChristopherA](https://github.com/ChristopherA))  

For a full list of contributors, see [CONTRIBUTORS.md](CONTRIBUTORS.md).

---

*Open Integrity is a project of [Blockchain Commons](https://www.blockchaincommons.com), empowering open-source cryptographic security & trust.*
