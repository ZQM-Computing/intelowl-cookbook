# IntelOwl Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **IntelOwl cookbook** — API-driven threat-intelligence enrichment. Queued in wave-11 (Node-3 hub set). Patterns are planned from the design, not yet from fleet runs. It is intended for Threat-intelligence teams who enrich observables through one API. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** IntelOwl patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Threat-intelligence teams who enrich observables through one API.

## Prerequisites

- IntelOwl via Docker
- Analyzer API keys, kept out of repos
- Observables you own or are authorized to analyze

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-analysis` | A first observable analysis through the API |
| 02 | `02-analyzers` | Choosing and configuring analyzers |
| 03 | `03-jobs` | Job polling, reports, and verdicts |
| 04 | `04-misp-pairing` | Pairing enrichment with MISP events (see misp-cookbook) |

## Repository layout

```text
intelowl-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [misp-cookbook](https://github.com/ZQM-Computing/misp-cookbook) — Threat-intelligence sharing platform, localhost-only deployment
- [spiderfoot-cookbook](https://github.com/ZQM-Computing/spiderfoot-cookbook) — Passive OSINT automation as a service
- [theharvester-cookbook](https://github.com/ZQM-Computing/theharvester-cookbook) — Passive reconnaissance: domains, emails, and hosts from public sources
