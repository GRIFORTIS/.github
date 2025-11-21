# .github

# GRIFORTIS

A collection of open-source tools for secure, long-term digital inheritance and self-sovereignty.

This project was founded by [Renato Schiavinato Lopez](https://github.com/renatoslopes) with the mission of creating resilient, humane, and transparent tools to help individuals and families protect their digital legacy across generations.

---

### Core Philosophy

Our work is guided by three core principles:

1.  **Security Through Simplicity:** Complexity is the enemy of security. Our tools are designed to be as simple as possible, both in their code and their user experience, to minimize the risk of catastrophic user error.
2.  **Radical Transparency:** All our tools are, and will always be, 100% free and open source under the MIT license. We believe that security tools must be fully auditable by anyone, at any time.
3.  **Humane Design:** We recognize that these tools will often be used during times of immense stress. Our primary focus is on creating calm, clear, and forgiving user experiences that empower non-technical users to succeed.

### ⚠️ Project Status: EXPERIMENTAL

**THIS IS A PRE-RELEASE, RESEARCH-LEVEL PROJECT.**

The cryptographic methods and code within our repositories have **NOT** been professionally audited. While we are committed to following best practices, this software should be considered a public prototype.

**DO NOT USE THESE TOOLS TO SECURE REAL FUNDS.** Use them for learning, experimentation, and to contribute to the development process.

---

### Our Projects

The GRIFORTIS ecosystem is composed of several distinct projects, each with a specific goal.

#### Applications

*   **[Grifortis-Guardian](https://github.com/GRIFORTIS/Grifortis-Guardian)** (In Development)  
    Our flagship tool for mainstream users. A self-contained HTML application that provides a guided, humane interface for creating and recovering sharded backups using the industry-standard **SLIP39** and **SSKR** schemes. It is designed to be the safest and simplest entry point into distributed backups.

*   **Schiavinato Sharing Tools** (Pre-Alpha / Planned)  
    A set of HTML/JavaScript and Python tools that implement the Schiavinato Sharing scheme for BIP39 mnemonic splitting and recovery, based on the whitepaper and reference materials in the `Schiavinato_Sharing` repository.

#### Foundational Schemes & Whitepapers

*   **[Schiavinato Sharing](https://github.com/GRIFORTIS/Schiavinato_Sharing)** (Whitepaper & Reference Material)  
    A human-executable BIP39 mnemonic sharing scheme based on arithmetic in `GF(2053)`. This repository hosts the whitepaper **“Schiavinato Sharing: Human-Executable Secret Sharing for BIP39 Mnemonics”** and related reference materials, including test vectors.

#### Core Libraries

*   **Schiavinato Sharing Libraries (Python & JavaScript)** (Planned)  
    Clean, standalone libraries that serve as reference implementations of the Schiavinato Sharing scheme, designed for easy integration into other projects and for security auditing.

*   **[grifortis-sss-libs](https://github.com/GRIFORTIS/grifortis-sss-libs)** (Planned)  
    A future repository for the JavaScript and Python libraries that will power the Grifortis Guardian, providing clean implementations of SLIP39 and SSKR.

### How to Contribute

We welcome contributions of all kinds, from documentation improvements to bug reports to deep security analysis. This project will only succeed with the help of the open-source community.

Please see our `CONTRIBUTING.md` guide for more details on our development process. The best way to start is by opening an issue in the relevant repository to discuss your ideas.

All feedback is welcome, especially critical security analysis.

### License

Unless otherwise noted in a specific repository:

- **Software** under the GRIFORTIS organization is released under the **[MIT License](LICENSE)**.  
- **Documentation and whitepapers** are generally MIT as well, but some projects (for example, the `Schiavinato_Sharing` whitepaper) may use **Creative Commons** licenses such as **CC BY 4.0**.

Always refer to the `LICENSE` files within each repository for the exact terms.
