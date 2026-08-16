# GRIFORTIS organization defaults (`.github`)

[![Security: Unaudited](https://img.shields.io/badge/Security-Unaudited-orange)](https://github.com/GRIFORTIS/.github/blob/main/SECURITY.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Organization-wide GitHub community health defaults for the `GRIFORTIS` org.

GitHub automatically applies these files to repositories in the organization (unless a repo overrides them with stricter or more specific policies).

---

## What’s in this repository

- **Security policy**: [`SECURITY.md`](./SECURITY.md)
- **Contributing guide**: [`CONTRIBUTING.md`](./CONTRIBUTING.md)
- **Code of Conduct**: [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md)
- **PR template**: [`PULL_REQUEST_TEMPLATE.md`](./PULL_REQUEST_TEMPLATE.md)
- **Issue templates + config**: [`ISSUE_TEMPLATE/`](./ISSUE_TEMPLATE/)
- **Organization profile README**: published from the [`grifortis`](https://github.com/GRIFORTIS/grifortis) profile path (see that repo)

## DuraShare

**DuraShare: BIP39-Native Threshold Backup over GF(2053) with Full Manual Fallback and Per-Share Audit**

DuraShare is a human-first, software-assisted **k-of-n** threshold secret sharing protocol for BIP39 mnemonics with one arithmetic layer and two operational paths: a recommended computational deployment and a **full manual fallback**. It applies Shamir Secret Sharing over the prime field GF(2053) directly to the 1-indexed BIP39 word indices (1..2048), word by word, producing durable, human-readable shares that can be validated and recovered either by hand (modular arithmetic + precomputed Lagrange coefficients) or via an air-gapped tool (with a digital envelope). It also allows **individual geographically distributed shares to be verified** before recovery, without gathering a threshold or revealing the secret.

Key features:
- One math, two paths: software or fully manual (no black box, no lock-in)
- BIP39-native: split the seed you already have (no new word list, no moving funds)
- Flexible k-of-n (up to 256-of-256); fewer than k shares reveal nothing
- Optional nesting: groups of groups with individual k-of-n each (up to 4 layers)
- Human-readable shares: print locally (USB/air-gapped printer only) or copy by hand
- Built-in error detection: guarantee to catch any copy mistakes or damage (up to 3 cells per share)
- Per-share audit: check one share where it lives, without gathering the others or revealing the secret (catches substitution, not just damage)
- Post-recovery checks including wallet derivation and BIP39 passphrase (passphrase is not stored and demands its own backup)

DuraShare **modifies existing, well-established cryptographic techniques** for human-friendly threshold backup. Reference implementations are thoroughly tested, published in good faith **as is**, and have **not** been independently audited. See [Disclaimer](#disclaimer).

## Links

- **Canonical specification**: [`durashare`](https://github.com/GRIFORTIS/durashare)
  - Standing review guide: [`docs/review`](https://github.com/GRIFORTIS/durashare/blob/main/docs/review.md)
- **Whitepaper**: [PDF (latest)](https://github.com/GRIFORTIS/durashare/releases/latest/download/WHITEPAPER.pdf) | [Releases](https://github.com/GRIFORTIS/durashare/releases) | [LaTeX](https://github.com/GRIFORTIS/durashare/blob/main/whitepaper/WHITEPAPER.tex)
- **Implementations**:
  - HTML (single-file, air-gapped): [`durashare-html`](https://github.com/GRIFORTIS/durashare-html)
  - JavaScript/TypeScript: [`durashare-js`](https://github.com/GRIFORTIS/durashare-js)
  - Python: [`durashare-py`](https://github.com/GRIFORTIS/durashare-py)

## People

### Renato Schiavinato Lopez — Founder & Protocol Author
- Creator of DuraShare.
- [LinkedIn](https://www.linkedin.com/in/renato-agile-coach/) · [GitHub](https://github.com/renatoslopes)

### Jeroen van de Graaf — Chief Scientist; Advisory Board
- Professor, DCC–UFMG. Cryptographer (ZK, MPC, privacy, applied protocols); PhD, Université de Montréal (1997).
- [DCC/UFMG](https://dcc.ufmg.br/professor/jeroen-van-de-graaf/) · [DBLP](https://dblp.org/pid/27/6925.html) · [Lattes](http://lattes.cnpq.br/0069989873499216) · [Google Scholar](https://scholar.google.com.br/citations?user=-w8olWwAAAAJ)

## License
- This repository: [MIT License](LICENSE)

## Disclaimer

Software has been thoroughly tested and is not known to contain errors. It is made available in good faith, as is, so use at your own risk. The author does not assume any responsibility for any damage, financial or other, that may result from using this software. Reference implementations have not been independently audited. **Do not use with real funds.** See [SECURITY](./SECURITY.md).

---

**Maintained by**: [GRIFORTIS](https://github.com/GRIFORTIS)
