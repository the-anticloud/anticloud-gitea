# GITEA

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-software_development-lightgrey)

> Anticloud-hardened packaging of the upstream project `GITEA` in category **SOFTWARE DEVELOPMENT**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SOFTWARE DEVELOPMENT · **Upstream:** https://github.com/go-gitea/gitea · **Upstream pin:** `871d29553b02a97f9a170c30f6076c6c8e618d27` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# Gitea

[![](https://github.com/go-gitea/gitea/actions/workflows/release-nightly.yml/badge.svg?branch=main)](https://github.com/go-gitea/gitea/actions/workflows/release-nightly.yml?query=branch%3Amain "Release Nightly")
[![](https://img.shields.io/discord/322538954119184384.svg?logo=discord&logoColor=white&label=Discord&color=5865F2)](https://discord.gg/Gitea "Join the Discord chat at https://discord.gg/Gitea")
[![](https://pkg.go.dev/badge/gitea.dev?status.svg)](https://pkg.go.dev/gitea.dev "GoDoc")
[![](https://img.shields.io/github/release/go-gitea/gitea.svg)](https://github.com/go-gitea/gitea/releases/latest "GitHub release")
[![](https://www.codetriage.com/go-gitea/gitea/badges/users.svg)](https://www.codetriage.com/go-gitea/gitea "Help Contribute to Open Source")
[![](https://opencollective.com/gitea/tiers/backers/badge.svg?label=backers&color=brightgreen)](https://opencollective.com/gitea "Become a backer/sponsor of gitea")
[![](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT "License: MIT")
[![](https://badges.crowdin.net/gitea/localized.svg)](https://translate.gitea.com "Crowdin")

[繁體中文](./README.zh-tw.md) | [简体中文](./README.zh-cn.md)

## Purpose

The goal of Gitea is to make the easiest, fastest, and most painless way of
setting up a self-hosted all-in-one software development service,
including Git hosting, code management, code review, issue tracking, project kanban, wiki,
team collaboration, package registry and CI/CD which can reuse GitHub Actions.

As Gitea is written in Go, it works across **all** the platforms and
architectures that are supported by Go, including Linux, macOS, FreeBSD/OpenBSD and Windows
on x86, amd64, ARM, RISC-V 64 and PowerPC architectures.

For online demonstrations, you can visit [demo.gitea.com](https://demo.gitea.com).

For accessing free Gitea service (with a limited number of projects), you can visit [gitea.com](https://gitea.com/user/login).

To quickly deploy your own dedicated Gitea instance on Gitea Cloud, you can start a free trial at [cloud.gitea.com](https://cloud.gitea.com),
or use container (docker/podman/etc) to deploy on your own server with the [official image](https://hub.docker.com/r/gitea/gitea).

## Documentation

You can find comprehensive documentation on our official [documentation website](https://docs.gitea.com/).

It includes installation, administration, usage, development, contributing guides, and more to help you get started and explore all features effectively.

If you have any suggestions or would like to contribute to it, you can visit the [documentation project](https://gitea.com/gitea/docs)

## Building

See [docs/build-setup.md](docs/build-setup.md) for prerequisites
and [docs/development.md](docs/development.md) for setting up a local development environment, linting, and testing.

If you'd like to build from source or make a distribution package, see [docs/build-source.md](docs/build-source.md) for more information.

After building, you can run `./gitea web` to start the server, or `./gitea help` to see all available commands.

## Contributing

Expected workflow is: Fork -> Patch -> Push -> Pull Request

> [!NOTE]
>
> 1. **YOU MUST READ THE [CONTRIBUTORS GUIDE](CONTRIBUTING.md) BEFORE STARTING TO WORK ON A PULL REQUEST.**
> 2. New to the codebase? The [development guide](docs/development.md) walks through setting up a local environment and building from source.
> 3. If you have found a vulnerability in the project, please write privately to **security@gitea.io**. Thanks!

## Translating

[![Crowdin](https://badges.crowdin.net/gitea/localized.svg)](https://translate.gitea.com)

Translations are done through [Crowdin](https://translate.gitea.com). If you want to translate to a new language, ask one of the managers in the Crowdin project to add a new language there.

You can also just create an issue for adding a language or ask on Discord on the #translation channel. If you need context or find some translation issues, you can leave a comment on the string or ask on Discord.

Get more information from [the translation section of our contributing guide](CONTRIBUTING.md#translation).

## Official and Third-Party Projects

We provide an official [go-sdk](https://gitea.com/gitea/go-sdk), a CLI tool called [tea](https://gitea.com/gitea/tea) and an [action runner](https://gitea.com/gitea/runner) for Gitea Action.

We maintain a list of Gitea-related projects at [gitea/awesome-gitea](https://gitea.com/gitea/awesome-gitea), where you can discover more third-party projects, including SDKs, plugins, themes, and more.

## Communication

[![](https://img.shields.io/discord/322538954119184384.svg?logo=discord&logoColor=white&label=Discord&color=5865F2)](https://discord.gg/Gitea "Join the Discord chat at https://discord.gg/Gitea")

If you have questions that are not covered by the [documentation](https://docs.gitea.com/), you can get in contact with us on our [Discord server](https://discord.gg/Gitea) or create a post in the [discourse forum](https://forum.gitea.com/).

## Authors

- [Maintainers](https://github.com/orgs/go-gitea/people)
- [Contributors](https://github.com/go-gitea/gitea/graphs/contributors)
- [Translators](options/locale/TRANSLATORS)

## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/gitea#backer)]

<a href="https://opencollective.com/gitea#backers" target="_blank"><img src="https://opencollective.com/gitea/backers.svg?width=890"></a>

## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/gitea#sponsor)]

<a href="https://opencollective.com/gitea/sponsor/0/website" target="_blank"><img src="https://opencollective.com/gitea/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/gitea/sponsor/1/website" target="_blank"><img src="https://opencollective.com/gitea/sponsor/1/avatar.svg"></a>
<a href="https://opencolle

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, pnpm-lock.yaml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `assets/`, `build/`, `cmd/`, `contrib/`, `custom/`, `docker/`, `modelmigration/`, `models/`, `modules/`, `options/`, `public/`, `routers/`
- Snapshot size: **6289 files**, **528698 lines of code** (measured; see Benchmarks)
- Primary languages: `.go` (3119), `(none)` (1264), `.tmpl` (590), `.svg` (536), `.ts` (267), `.yml` (134)
- Upstream commit pinned for this packaging: `871d29553b02a97f9a170c30f6076c6c8e618d27`

---

## Installation

If you have any suggestions or would like to contribute to it, you can visit the [documentation project](https://gitea.com/gitea/docs)

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

As Gitea is written in Go, it works across **all** the platforms and
architectures that are supported by Go, including Linux, macOS, FreeBSD/OpenBSD and Windows
on x86, amd64, ARM, RISC-V 64 and PowerPC architectures.

For online demonstrations, you can visit [demo.gitea.com](https://demo.gitea.com).

For accessing free Gitea service (with a limited number of projects), you can visit [gitea.com](https://gitea.com/user/login).

To quickly deploy your own dedicated Gitea instance on Gitea Cloud, you can start a free trial at [cloud.gitea.com](https://cloud.gitea.com),
or use container (docker/podman/etc) to deploy on your own server with the [official image](https://hub.docker.com/r/gitea/gitea).

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

You can find comprehensive documentation on our official [documentation website](https://docs.gitea.com/).

It includes installation, administration, usage, development, contributing guides, and more to help you get started and explore all features effectively.

If you have any suggestions or would like to contribute to it, you can visit the [documentation project](https://gitea.com/gitea/docs)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, pnpm-lock.yaml |
| Files in snapshot | 6289 |
| Lines of code | 528698 |
| Dependency references | 314 |
| Dependencies by ecosystem | go: 215, npm: 99 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| go | connectrpc.com/connect | v1.21.0 | go.mod |
| go | gitea.com/lunny/levelqueue | v0.4.2-0.20230414023320-3c0159fe0fe4 | go.mod |
| go | gitea.dev/actionslib | v1.3.0 | go.mod |
| go | gitea.dev/sdk | v1.2.0 | go.mod |
| go | github.com/42wim/httpsig | v1.2.4 | go.mod |
| go | github.com/42wim/sshsig | v0.0.0-20260317195500-b9f38cf0d432 | go.mod |
| go | github.com/alecthomas/chroma/v2 | v2.27.0 | go.mod |
| go | github.com/blakesmith/ar | v0.0.0-20190502131153-809d4375e1fb | go.mod |
| go | github.com/blevesearch/bleve/v2 | v2.6.1 | go.mod |
| go | github.com/bohde/codel | v0.2.0 | go.mod |
| go | github.com/bradfitz/gomemcache | v0.0.0-20260422231931-4d751bb6e37c | go.mod |
| go | github.com/buildkite/terminal-to-html/v3 | v3.17.1 | go.mod |
| go | github.com/caddyserver/certmagic | v0.25.4 | go.mod |
| go | github.com/charmbracelet/git-lfs-transfer | v0.1.1-0.20260812203852-971c0284dc33 | go.mod |
| go | github.com/chi-middleware/proxy | v1.1.1 | go.mod |
| ... | (299 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

If you'd like to build from source or make a distribution package, see [docs/build-source.md](docs/build-source.md) for more information.

After building, you can run `./gitea web` to start the server, or `./gitea help` to see all available commands.

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contribution Guidelines

This document explains how to contribute changes to the Gitea project. Topic-specific guides live in separate files so the essentials are easier to find.

| Topic                  | Document                                                         |
|:-----------------------|:-----------------------------------------------------------------|
| Setup and requirements | [docs/build-setup.md](docs/build-setup.md)                       |
| Development workflow   | [docs/development.md](docs/development.md)                       |
| Build from source      | [docs/build-source.md](docs/build-source.md)                     |
| Running the tests      | [docs/testing.md](docs/testing.md)                               |
| Frontend guidelines    | [docs/guidelines-frontend.md](docs/guidelines-frontend.md)       |
| Backend guidelines     | [docs/guidelines-backend.md](docs/guidelines-backend.md)         |
| Refactoring            | [docs/guidelines-refactoring.md](docs/guidelines-refactoring.md) |
| Community Governance   | [docs/community-governance.md](docs/community-governance.md)     |
| Release management     | [docs/release-management.md](docs/release-management.md)         |

<details><summary>Table of Contents</summary>

- [Contribution Guidelines](#contribution-guidelines)
  - [Introduction](#introduction)
  - [AI Contribution Policy](#ai-contribution-policy)
  - [Issues](#issues)
    - [How to report issues](#how-to-report-issues)
    - [Types of issues](#types-of-issues)
    - [Discuss your design before the implementation](#discuss-your-design-before-the-implementation)
    - [Issue locking](#issue-locking)
  - [Building Gitea](#building-gitea)
  - [Styleguide](#styleguide)
  - [Copyright](#copyright)
  - [Testing](#testing)
  - [Translation](#translation)
  - [Code review](#code-review)
    - [Pull request format](#pull-request-format)
    - [PR title and summary](#pr-title-and-summary)
    - [Breaking PRs](#breaking-prs)
      - [What is a breaking PR?](#what-is-a-breaking-pr)
      - [How to handle breaking PRs?](#how-to-handle-breaking-prs)
    - [Maintaining open PRs](#maintaining-open-prs)
    - [Reviewing PRs](#reviewing-prs)
      - [For PR authors](#for-pr-authors)
  - [Documentation](#documentation)
  - [Developer Certificate of Origin (DCO)](#developer-certificate-of-origin-dco)

</details>

## Introduction

It assumes you have followed the [installation instructions](https://docs.gitea.com/category/installation). \
Se

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
Copyright (c) 2016 The Gitea Authors
Copyright (c) 2015 The Gogs Authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `GITEA` (category: SOFTWARE DEVELOPMENT)
- **Upstream URL:** https://github.com/go-gitea/gitea
- **Pinned commit (SHA):** `871d29553b02a97f9a170c30f6076c6c8e618d27`
- **Branch:** main
- **Pin provenance:** GitHub API commits/main. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`17f56711986b1bcea7e2888c418bcb8ab7dbaa70b8be6db4e25f81b5667e38c3`.

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
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

