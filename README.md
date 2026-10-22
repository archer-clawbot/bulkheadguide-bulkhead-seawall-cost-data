# Bulkhead and Seawall Cost Register (US, 2026)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23550684.svg)](https://doi.org/10.5281/zenodo.23550684)

Published by **Bulkhead Guide** (https://www.bulkheadguide.com/). This GitHub repository is a mirror; the canonical, versioned release is on Zenodo.

- **DOI:** [10.5281/zenodo.23550684](https://doi.org/10.5281/zenodo.23550684)
- **Zenodo record:** https://zenodo.org/records/23550684
- **Data page:** https://www.bulkheadguide.com/seawall-cost/
- **License:** CC BY 4.0 (see LICENSE)

## How to cite
Bulkhead Guide. *Bulkhead and Seawall Cost Register (US, 2026)*. Zenodo. https://doi.org/10.5281/zenodo.23550684

---

# Bulkhead and Seawall Cost Register (US, 2026)

Compiled by **Bulkhead Guide** (www.bulkheadguide.com). Version 2026-10-21. **Draft — not yet published.**

A register of individual prices that US contractors and consumer cost guides publish on public web pages for bulkhead and seawall construction, replacement and repair. Each row is one published figure with its unit, scope, geography, publisher, source URL, source date, retrieval date and a short verbatim quote of the figure.

- **File:** `bulkhead-seawall-cost-register.csv` (50 rows)
- **Coverage:** 50 rows from 13 source URLs and 8 independent businesses; 34 primary-tier rows and 16 secondary-tier rows; local rows cover FL, MD, NJ, SC, TX, VA.
- **Build:** `python3 src/build.py` re-verifies every quote against the raw snapshots and fails if any quote or number is missing.
- **Docs:** METHODS.md, DATA-DICTIONARY.md, FINDINGS.md, raw/SOURCES.md
- **License:** CC BY 4.0 for the compilation (see LICENSE). Underlying figures belong to their publishers and are cited, not relicensed.

Not a quote, survey or representative sample. Do not average rows across different units, scopes or geographies.

Cite as: Bulkhead Guide (2026). *Bulkhead and Seawall Cost Register (US, 2026)* (Version 2026-10-21) [Data set].
