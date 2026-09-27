# SDUMLA-HMT

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FSDUMLA--HMT-181717?logo=github)](https://github.com/biometric-community/SDUMLA-HMT)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://mla.sdu.edu.cn/sdumla-hmt.html)

**SDUMLA-HMT** — tbiom catalog packaging for `sdumla` (vein; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/SDUMLA-HMT
- **Upstream source**: http://mla.sdu.edu.cn/sdumla-hmt.html
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `sdumla` |
| Category | `vein` |
| Access | `register` |
| Upstream homepage | http://mla.sdu.edu.cn/sdumla-hmt.html |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Shandong University multi-modal (includes finger vein).

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/SDUMLA-HMT.git
cd SDUMLA-HMT
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_sdumla.sh
```

Place licensed archives under `projects/datasets/sdumla/` (gitignored).

## Dataset structure

```text
SDUMLA-HMT/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://mla.sdu.edu.cn/sdumla-hmt.html
- Packaging: https://github.com/biometric-community/SDUMLA-HMT/issues
