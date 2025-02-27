# Open Integrity Project: Documentation - `README.md`
> - _did: `did:repo:9bc5422ae37af0e2adfc2f6a202db259734f0a48/blob/main/README.md`_
> - _github: `https://github.com/OpenIntegrityProject/docs/blob/main/README.md`_
> - _updated: 2025-02-26 by Christopher Allen <ChristopherA@LifeWithAlacrity.com>_

## 📖 Introduction

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

## 🔑 Key Features

- **Inception Commits** – Immutable starting points that combine:
  - Empty commit for SHA-1 collision resistance
  - Ricardian Contract defining trust rules
  - SSH signature providing strong cryptographic proofs
- **Trust Models**:
  - Direct inception key verification
  - Delegated verification through authorized signers
- **Automated Tamper Detection** – Integrity checks throughout history
- **Audit Tools** – Comprehensive repository inspection
- **Cross-Platform Trust** – GitHub, GitLab, P2P, or self-hosted support

## 📚 Repository Structure

This repository contains the documentation for the Open Integrity Project, offering both high-level concepts and practical guidance on establishing and maintaining cryptographic trust using Git repositories.

### 📁 Core Documentation

- 📜 [Problem Statement](Open_Integrity_Problem_Statement.md) – Challenges & solutions for cryptographic roots of trust using Git repositories
- 📟 [CLI One-Liners](Open_Integrity-CLI_One_Liners.md) – Practical command-line shortcuts for Open Integrity
- ├- [Repository Structure](Open_Integrity_Repo_Directory_Structure.md) – Open Integrity repository structure reference
- 🤝 [Contributing Guidelines](CONTRIBUTING.md) – How to contribute
- 🔒 [Security Policy](SECURITY.md) – Reporting vulnerabilities

### 📌 Project Resources

- 📖 [Documentation Website](https://OpenIntegrityProject.info)
- 📋 [Project Roadmap](https://github.com/orgs/OpenIntegrityProject/projects)
- 💬 [Community Discussions](https://github.com/orgs/OpenIntegrityProject/discussions)
- ❗ [Initial Issue Tracker](https://github.com/OpenIntegrityProject/community/issues)

### 📝 Planned Resources

- 🚀 [Getting Started](Open_Integrity_Getting-Started.md) – Learn the concept and set up your first Open Integrity repository
- 🏛 [Architecture](Open_Integrity_Architecture.md) – System design & implementation details
- 🚀 [Getting Started](Open_Integrity_Getting_Started.md) – Understand the concepts by following a step-by-step guide to set up your first Open Integrity repository

### 🛠 Implementation

- ⚙️ [`scripts`](https://github.com/OpenIntegrityProject/scripts) – Essential Open Integrity Project tools & automation scripts
- 📜 [`/requirements`](https://github.com/OpenIntegrityProject/scripts/requirements/) – Requirements documents for Open Integrity Project scripts
- ❗ [`/issues`](https://github.com/OpenIntegrityProject/scripts/issues/) – Tracks known issues and planned improvements
- 🔎 [`/tests`](https://github.com/OpenIntegrityProject/scripts/tests/) – Comprehensive regression tests for inspecting Open Integrity scripts and overall project functionality
- ✂️ [`/snippets`](https://github.com/OpenIntegrityProject/scripts/snippets/) – Small utility scripts (< 200 lines) for specific tasks
  - 📜 [`/snippets/requirements`](https://github.com/OpenIntegrityProject/scripts/snippets/requirements/) – Requirements for individual snippet scripts
  - 🔎 [`/snippets/tests`](https://github.com/OpenIntegrityProject/scripts/snippets/tests/) – Regression test scripts for ensuring snippet functionality

## 🚀 Quick Start

Follow the [Getting Started Guide](Open_Integrity_Getting-Started.md) to:
1. Set up your development environment for signing
2. Create a repository with an inception commit establishing your root of trust
3. Choose your trust model:
   - Direct verification using the inception key
   - OR delegated verification through authorized signers
4. Run Open Integrity audits on your repositories

For a deeper dive, check out our [Problem Statement](Open_Integrity_Problem_Statement.md) and **[Architecture Overview](Open_Integrity_Architecture.md)**.

## 🤝 How to Contribute

We welcome contributions from developers, researchers, and security experts!

1. Read our **[Contributing Guide](CONTRIBUTING.md)**
2. Fork the repository & create a feature branch
3. Implement your feature or fix
4. Submit a **Pull Request** for review

📜 All contributors must adhere to our [Code of Conduct](CODE_OF_CONDUCT.md).

## 🚦 Project Status & Roadmap

### **Current Phase: Early Research & Proof-of-Concept (v0.1.0)**
🔹 Core concepts & initial implementation complete
🔹 Seeking community feedback for improvements
🔹 Developing integration with CI/CD & key management solutions
🔹 **Not yet production-ready**

📍 See our [Development Phases](https://github.com/BlockchainCommons/Community/blob/master/release-path.md) for the full roadmap.

## 🛡 Security & Trust

### 🕵️ Reporting Security Issues

🔒 If you discover a security issue, please report it responsibly:
- **Email**: [team@BlockchainCommons.com](mailto:team@BlockchainCommons.com)
- **GPG Encrypted Reports**: See [SECURITY.md](SECURITY.md) for details

### 👥 Security Contacts

| Name              | Email                              | GPG Fingerprint                                     |
|-------------------|------------------------------------|-----------------------------------------------------|
| Christopher Allen | ChristopherA@LifeWithAlacrity.com  | FDFE 14A5 4ECB 30FC 5D22  74EF F8D3 6C91 3574 05ED  |

## 📞 Contact & Support

- **Security Issues**: [team@BlockchainCommons.com](mailto:team@BlockchainCommons.com)
- **General Questions**: [Community Discussions](https://github.com/orgs/OpenIntegrityProject/discussions)
- **Bug Reports**: [Initial Issue Tracker](https://github.com/OpenIntegrityProject/community/issues)

## ❗ Issue Management

We recommend starting general issues in GitHub's 💬 [Community Discussions](https://github.com/orgs/OpenIntegrityProject/discussions) to encourage open dialogue before they are formally moved to our ❗ [Initial Issue Tracker](https://github.com/OpenIntegrityProject/community/issues) (also on GitHub). However, in alignment with our commitment to decentralized repository management, on our roadmap is to develop GitHub Action scripts that will automatically populate /issues directories within each repository. This will allow issues to be mirrored across multiple Git hosting platforms, ensuring greater resilience and accessibility beyond GitHub.

## 🌟 Support the Open Integrity Project

If you find this project valuable, consider:
⭐ Starring the repository
💬 Engaging in discussions
📢 Sharing with your network
💰 Supporting our host [Blockchain Commons via GitHub Sponsors](https://github.com/sponsors/BlockchainCommons)

For commercial support, visit: **[Blockchain Commons Support](https://www.blockchaincommons.com/support/)**.

### 👨‍💻 **Lead Developer**
**Christopher Allen** ([@ChristopherA](https://github.com/ChristopherA)), [\<ChristopherA@LifeWithAlacrity.com/>](mailto:ChristopherA@LifeWithAlacrity.com)

For a full list of contributors, see [CONTRIBUTORS.md](CONTRIBUTORS.md).

## 📜 Copyright & License

Unless otherwise noted, all files are ©2025 Open Integrity Project / Blockchain Commons LLC., and licensed under the [BSD 2-Clause Pluse Patent License](https://spdx.org/licenses/BSD-2-Clause-Patent.html) – See [LICENSE](LICENSE) for details.

### 🌍 About Us

📖 The **Open Integrity Project** is an [Open Development](https://www.blockchaincommons.com/articles/Open-Development/) initiative hosted by [Blockchain Commons](https://www.BlockchainCommons.com), dedicated to advancing **open, interoperable, secure & compassionate digital infrastructure**, and embracing the [Gordian Principles](https://developer.BlockchainCommons.com/principles/) of **independence, privacy, resilience, and openness**.
