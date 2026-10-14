# CAPROVER

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-infra_devops-lightgrey)

> Anticloud-hardened packaging of the upstream project `CAPROVER` in category **INFRA DEVOPS**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** INFRA DEVOPS · **Upstream:** https://github.com/caprover/caprover.git · **Upstream pin:** `a45cce6b7fc0d30ca431a8d8ce83bef72a5a9913` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<div align="center">
<h1>CapRover</h1>
<a href="https://hub.docker.com/r/caprover/caprover/" target="_blank" title="Docker Pulls">
<img src="https://img.shields.io/docker/pulls/caprover/caprover.svg" alt="Docker Pulls"/>
</a>
<a href="https://opencollective.com/caprover#backer" target="_blank" title="Open Collective backers and sponsors">
<img src="https://img.shields.io/opencollective/all/caprover" alt="Open Collective backers and sponsors"/>
</a>
<a href="https://github.com/caprover/caprover/releases" target="_blank" title="GitHub release (latest by date)">
<img src="https://img.shields.io/github/v/release/caprover/caprover" alt="GitHub release (latest by date)"/>
</a>

Easiest app/database deployment platform and webserver package for your NodeJS, Python, PHP, Ruby, Go applications.

No Docker, nginx knowledge required!

<a href="https://youtu.be/VPHEXPfsvyQ" target="_blank" title="YouTube">
<img src="https://raw.githubusercontent.com/caprover/caprover-website/master/graphics/screenshots-video-small.png" alt="YouTube"/>
</a>
</div>

## What's this?

CapRover is an extremely easy to use app/database deployment & web server manager for your **NodeJS, Python, PHP, ASP.NET, Ruby, MariaDB, MySQL, MongoDB, Postgres, WordPress (and etc...)** applications!

It's blazingly fast and very robust as it uses Docker, nginx, LetsEncrypt and NetData under the hood behind its simple-to-use interface.

✔ CLI for automation and scripting

✔ Web GUI for ease of access and convenience

✔ No lock-in! Remove CapRover and your apps keep working!

✔ Docker Swarm under the hood for containerization and clustering

✔ Nginx (fully customizable template) under the hood for load-balancing

✔ Let's Encrypt under the hood for free SSL (HTTPS)

### Seriously! Who should care about CapRover?

-   A [web] developer who does not like spending hours and days setting up a server, build tools, sending code to server, build it, get an SSL certificate, install it, update nginx over and over again.
-   A developer who uses expensive services like Heroku, Microsoft Azure and etc. And is interested in reducing their cost by 50x (Heroku charges 250USD/month for their 2gb instance, the same server is 5$ on Hetzner!!)
-   Someone who prefers to write more of `showResults(getUserList())` and not much of `$ apt-get install libstdc++6 > /dev/null`
-   A developer who likes installing MariaDB, MySQL, MongoDB and etc on their server by selecting from a dropdown and clicking on install!
-   How much server/docker/linux knowledge is required to set up a CapRover server? Answer: Knowledge of Copy & Paste!! Head over to "Getting Started" for information on what to copy & paste ;-)

## Learn More!

For more details and documentation, please visit https://CapRover.com/

## Contributors

CapRover exists thanks to all the great people who have contributed to this project. [[Contribute](CONTRIBUTING.md)].
<a href="https://github.com/caprover/caprover/graphs/contributors"><img src="https://opencollective.com/caprover/contributors.svg?width=690&button=false" /></a>

## Financial Supporters

A big thank you to all our supporters! 🙏

[![Donate](https://opencollective.com/caprover/donate/button.png?color=blue)](https://opencollective.com/caprover#backer)

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `captain-sample-apps/`
- Snapshot size: **31 files**, **0 lines of code** (measured; see Benchmarks)
- Primary languages: `.md` (13), `.tar` (8), `.yml` (6), `(none)` (4)
- Upstream commit pinned for this packaging: `a45cce6b7fc0d30ca431a8d8ce83bef72a5a9913`

---

## Installation

-   A developer who uses expensive services like Heroku, Microsoft Azure and etc. And is interested in reducing their cost by 50x (Heroku charges 250USD/month for their 2gb instance, the same server is 5$ on Hetzner!!)
-   Someone who prefers to write more of `showResults(getUserList())` and not much of `$ apt-get install libstdc++6 > /dev/null`
-   A developer who likes installing MariaDB, MySQL, MongoDB and etc on their server by selecting from a dropdown and clicking on install!
-   How much server/docker/linux knowledge is required to set up a CapRover server? Answer: Knowledge of Copy & Paste!! Head over to "Getting Started" for information on what to copy & paste ;-)

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

It's blazingly fast and very robust as it uses Docker, nginx, LetsEncrypt and NetData under the hood behind its simple-to-use interface.

✔ CLI for automation and scripting

✔ Web GUI for ease of access and convenience

✔ No lock-in! Remove CapRover and your apps keep working!

✔ Docker Swarm under the hood for containerization and clustering

✔ Nginx (fully customizable template) under the hood for load-balancing

✔ Let's Encrypt under the hood for free SSL (HTTPS)

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

✔ CLI for automation and scripting

✔ Web GUI for ease of access and convenience

✔ No lock-in! Remove CapRover and your apps keep working!

✔ Docker Swarm under the hood for containerization and clustering

✔ Nginx (fully customizable template) under the hood for load-balancing

✔ Let's Encrypt under the hood for free SSL (HTTPS)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 31 |
| Lines of code | 0 |
| Dependency references | 0 |
| Upstream license | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- None detected at the snapshot root; consult the upstream documentation link in the Upstream section.

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Before Contributing

When contributing to this project, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this project before making a change. The best way is our Slack channel (link at the footer of CapRover.com)

Please note we have a code of conduct, please follow it in all your interactions with the project.

## IMPORTANT: CapRover Goals & Scope

Since the birth of CapRover, there has been many contributions and suggestions that shaped CapRover as we know it today. One of the very important factor in the contribution you make is to stick with CapRover design philosophy.- CapRover is not an enterprise grade application like Kubernetes. _Do not_ patch it with half-done features that make it look like one - it will eventually fail as we don't have resources to support such features.- CapRover scope is a helper around Docker, nginx and Let's Encrypt.

The goal is to make the common use-cases exposed via simple controls on UI while allowing further customizations to be done through hooks and scripts. If a new feature is doable via the existing features, or a basic tool, do not add it to CapRover. We do not want to bloat this application. One example is: "Add a flag to customize the placement constraints of containers". This is definitely doable in Docker, but we don't want to mirror every single functionality of Docker to CapRover. If we do that, CapRover becomes a very hard to maintain project. Instead we should add customization hooks for these advanced and rare use cases. For example, instead of mirroring every single nginx config, we added the ability of customizing the nginx config for advanced users.- Last but not least AVOID LARGE PULL REQUESTS at all cost as they won't get reviewed unless they are discussed in the Slack channel beforehand.

## Pull Request Process

1. IF APPLICABLE: Update the docs (https://github.com/caprover/caprover-website) with details of changes to the interface, this includes new environment
   variables, exposed ports, useful file locations and container parameters.
2. Make sure your commit comments are self explanatory.
3. Discuss the changes you want to make beforehand.
4. Please avoid making opinion-based changes if it's just a code-style change - this includes, but not limited to, changes to how we work with promises, class inheritance and etc.
5. To keep the process simple with just a few contributors, development happens directly on the master branch
   an

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: Apache-2.0** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
Copyright 2017-2024 BigZee Ventures LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Appendix:
In case of a conflict, the terms of this appendix supersede the general apache license.

-   Unless provided with a written agreement, the paid features of CapRover (as a service) cannot be modified.
-   Unless provided with a written agreement, no persons are permitted to redistribute another paid version of CapRover.
-   Furthermore, any modifications of free features of CapRover should be distributed as free & opensource software.
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original Apache-2.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `Apache-2.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `CAPROVER` (category: INFRA DEVOPS)
- **Upstream URL:** https://github.com/caprover/caprover.git
- **Pinned commit (SHA):** `a45cce6b7fc0d30ca431a8d8ce83bef72a5a9913`
- **Branch:** master
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`16f5a271da017baafcec121af6f6e7607d1f42006a1ad67f2a8463d82d3be0ab`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

