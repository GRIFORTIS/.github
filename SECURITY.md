## Security Policy for GRIFORTIS Projects

Many GRIFORTIS repositories, including schemes such as **Schiavinato Sharing**, are intended to help users protect real digital assets and long-term backups.  
We take potential security issues seriously and ask that you follow this policy when reporting vulnerabilities or subtle failure modes.

---

## Scope

This policy applies to:

- Whitepapers and specifications published under the `GRIFORTIS` organization.  
- Reference implementations and tooling (for example, calculators, libraries, or worksheet generators) that live in GRIFORTIS repositories.

It does **not** cover third-party wallets, websites, or services that may independently implement or integrate GRIFORTIS schemes.

Individual repositories may include additional, project-specific security notes. In case of conflict, project-specific instructions take precedence for that repository.

---

## How to Report a Security Issue

If you believe you have found:

- a flaw in a **scheme design** or threat model,  
- an implementation bug that could lead to **loss of funds**, **data corruption**, or **undetected share misuse**, or  
- documentation that could realistically mislead users into unsafe behavior,

please:

1. **Avoid posting full technical details in a public GitHub issue immediately.**  
2. Look for a security contact in the relevant repository’s `SECURITY.md`, `README`, or GitHub profile.  
3. If a dedicated security contact is provided, use that channel and include:
   - A clear, concise description of the issue.  
   - Which components are affected (whitepaper section, tool, workflow, etc.).  
   - Any minimal examples or steps needed to reproduce the problem.

If no dedicated security contact is listed yet:

- You may open a **high-level** GitHub issue describing the area of concern (for example, “Potential workflow that could leak information about passphrases”),  
- and ask for a private communication channel to share details.

---

## Expectations and Responsible Disclosure

We aim to:

- Acknowledge receipt of your report within a reasonable time.  
- Investigate the issue and, where appropriate, prepare fixes, clarifications, or mitigation guidance.  
- Coordinate on timing before publishing detailed information about high-impact vulnerabilities, especially where users may need time to adjust their setups.

We ask reporters to:

- Give maintainers a reasonable window to understand and address the issue before broad public disclosure.  
- Avoid attempting to exploit vulnerabilities on live systems or against real users.  
- Refrain from requesting or accepting custody of real user secrets (mnemonics, shares, passphrases, private keys) as part of any proof-of-concept or testing.

This last point reflects a core principle of GRIFORTIS: **specialists may advise, but users retain control of secrets.**

---

## Non-Security Feedback

For general questions, suggestions, or non-sensitive bug reports (typos, minor formatting issues, unclear explanations), please use the standard GitHub issue tracker of the relevant repository instead of security contacts.

This helps keep security channels focused on time-sensitive and high-impact concerns, while still encouraging broad community feedback and discussion.


