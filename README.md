# Open Integrity: Cryptographic Trust for Git Repositories

**Open Integrity** integrates cryptographic trust mechanisms into Git repositories. It empowers a repo to act as a cryptographic root of trust and offer a continuing chain of trust, ensuring integrity, transparency, and accountability in software development. Open Integrity does so by leveraging Git's native SSH signing capabilities and structured verification processes. It requires no modifications to Git itself, remaining fully compatible with existing Git hosting platforms, without the need for proprietary tools or external dependencies.

**Key Benefits:**

Whether you're a developer, security researcher, or open-source maintainer, Open Integrity provides the tools to:
- Provide a **developer-friendly framework** for cryptographic integrity.
- Establish **verifiable proof-of-origin** for commits and code artifacts through direct verification by inception key holder.
- Expand that proof-of-origin through a **chain of trust** that allows delegated verification of authorized signers.
- Detect **tampering or unauthorized modifications** in repository history.
- Enable **cross-platform trust verification** across Git hosting services

## Learn More

- 📖 [**Documents**](https://github.com/BlockchainCommons/OpenIntegrityProject/docs/) — Problem statement and HOW-TO guides for using Open Integrity.
- 🛠️ [**Scripts**](https://github.com/BlockchainCommons/OpenIntegrityProject/scripts/) — Open Integrity scripts for creating and maintaining trust.
- 💬 [**Community**](https://github.com/BlockchainCommons/OpenIntegrityProject/community/) — Discussions on the continued development of Open Integrity.

## Get Involved
We welcome contributions and discussions from developers, security experts, and open-source enthusiasts.

- ⭐ **Star** this repository and join us in building a more secure and verifiable open-source future!
- 🏗️ Check out our **[Contribution Guide](https://github.com/OpenIntegrityProject/.github/blob/main/CONTRIBUTING.md)**.
- ✍️ Report issues or suggest improvements in our [Issue Tracker](https://github.com/BlockchainCommons/OpenIntegrityProject/community/issues).
- 🔎 Browse our **Good First Issues** for ways to contribute: [Good First Issues](https://github.com/BlockchainCommons/OpenIntegrityProject/community/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

### 🌍 About Us
The **Open Integrity Project** is an [Open Developement](https://www.blockchaincommons.com/articles/Open-Development/) initiative hosted by [Blockchain Commons](https://www.blockchaincommons.com), focused on the [Gordian Principles](https://developer.blockchaincommons.com/principles/) of independence, privacy, resilience, and openness.

© 2025 Open Integrity Project / Blockchain Commons LLC. Licensed [BSD-3-Clause](https://github.com/OpenIntegrityProject/.github/blob/main/LICENSE.md).
 
---

/* Docs/README.md */

# Open Integrity

> Cryptographic Roots of Trust for Open Source Development

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
- 📂 [`/scripts`](scripts/) – Core cryptographic tools & automation
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

| Name              | Email                                  | GPG Fingerprint                                    |
|------------------|----------------------------------------|--------------------------------------------------|
| Christopher Allen | ChristopherA@LifeWithAlacrity.com     | FDFE 14A5 4ECB 30FC 5D22  74EF F8D3 6C91 3574 05ED |

## 📜 License

**BSD 2-Clause Plus Patent License** – See [LICENSE](LICENSE) for details.

📖 Open Integrity is an open-source project by [Blockchain Commons](https://www.blockchaincommons.com), dedicated to advancing **secure, transparent, and open digital infrastructure**.

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