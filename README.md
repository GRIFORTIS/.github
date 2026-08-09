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

DuraShare uses Shamir secret sharing to split a **standard BIP39** recovery phrase into **k-of-n** durable, human-readable shares in an offline, software-assisted experience, **while keeping all the math executable manually on paper**. It also allows **individual geographically distributed shares to be verified** before recovery, without gathering a threshold or revealing the secret.

DuraShare **modifies existing, well-established cryptographic techniques** for human-friendly threshold backup. Reference implementations are thoroughly tested, published in good faith **as is**, and have **not** been independently audited. **Do not use with real funds.**

- **Canonical specification**: [`durashare`](https://github.com/GRIFORTIS/durashare)
- **Whitepaper**: [PDF (latest)](https://github.com/GRIFORTIS/durashare/releases/latest/download/WHITEPAPER.pdf) | [Releases](https://github.com/GRIFORTIS/durashare/releases) | [LaTeX](https://github.com/GRIFORTIS/durashare/blob/main/whitepaper/WHITEPAPER.tex)
- **Implementations**:
  - HTML (single-file, air-gapped): [`durashare-html`](https://github.com/GRIFORTIS/durashare-html)
  - JS/TS: [`durashare-js`](https://github.com/GRIFORTIS/durashare-js)
  - Python: [`durashare-py`](https://github.com/GRIFORTIS/durashare-py)
- **Standing review guide**: [`docs/review`](https://github.com/GRIFORTIS/durashare/blob/main/docs/review.md)

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
