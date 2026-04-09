[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)
[![Research](https://img.shields.io/badge/Status-Active%20Research-orange.svg)]()
[![Publications](https://img.shields.io/badge/Publications-6-green.svg)]()

# CURE RPKI TOOLKIT
The **CURE RPKI toolkit** is a collection of RPKI related tooling to support offensive research into RPKI software security and deployments.
The toolkit consists of multiple different repositories that implement different functionality for security research, including a fuzzer, an RPKI publication libarary and an ASN.1 parsing library. 
The fuzzing code is based on the CAT fuzzing tool, while auxilarily tools are based on CURE libraries. 

> [!WARNING]
> All tools are offered on a **best-effort basis**. As part of active research, tools may break unexpectedly and are **not intended for production systems**.

---

## Repositories

| Repository | Description |
|---|---|
| [`cure_asn1`](https://github.com/niklbird/cure_asn1) | Fast, efficient ASN.1 parsing and encoding library, optimized for fuzzing speed |
| [`cure_coverage`](https://github.com/niklbird/cure_coverage) | Continuous coverage sampling library for instrumented binaries |
| [`cure_pp`](https://github.com/niklbird/cure_pp) | RPKI publication library for creating repositories and signing objects |
| [`cure_web`](https://github.com/niklbird/cure_web) | Graphical ASN.1 editor built on `cure_asn1` |
| [`cure` (cat)](https://github.com/niklbird/cure) | Coverage-guided fuzzer for RPKI relying party implementations — *temporarily unavailable pending vulnerability disclosure* |


---


## Publications
CURE has contributed to peer-reviewed research at top security venues:
- **[S&P 2026]** *Batch me if you can: Coverage-guided RPKI Fuzzing at Scale* — Not yet published
- **[NDSS 2026]** [Pruning the Tree: Rethinking RPKI Architecture From The Ground Up](https://www.ndss-symposium.org/wp-content/uploads/2026-s823-paper.pdf)
- **[CCS 2025]** [Stopping Production Testing: A Graphical RPKI Test-Suite](https://dl.acm.org/doi/abs/10.1145/3719027.3760705)
- **[CCS 2025]** [Poster: We must talk about RPKI Repositories](https://dl.acm.org/doi/abs/10.1145/3719027.3760715)
- **[NDSS 2024]** [The CURE To Vulnerabilities in RPKI Validation](https://arxiv.org/abs/2312.01872)
- **[CCS 2024]** [Poster: From Fort to Foe: The Threat of RCE in RPKI](https://dl.acm.org/doi/abs/10.1145/3658644.3691387)
---

## Acknowledgments
CURE was developed with support from:
- **German Federal Ministry of Education and Research**
- **Hessen State Ministry for Higher Education, Research and Arts**
- **German National Research Center for Applied Cybersecurity (ATHENE)**
- **Deutsche Forschungsgemeinschaft (DFG, German Research Foundation)**

---

## License
All CURE projects are released under the **GNU General Public License v3.0**. See [`LICENSE`](LICENSE) for details.

<div align="center">
  <sub>Made with ❤️ for RPKI</sub>
</div>
