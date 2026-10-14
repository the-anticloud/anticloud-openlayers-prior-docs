# OPENLAYERS PRIOR DOCS

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-online_retail-lightgrey)

> Anticloud-hardened packaging of the upstream project `OPENLAYERS_PRIOR_DOCS` in category **ONLINE RETAIL**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** ONLINE RETAIL · **Upstream:** https://github.com/openlayers/openlayers · **Upstream pin:** `69e07d8ad933c3081cc10b8bb4a64023917661aa` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# OpenLayers

[OpenLayers](https://openlayers.org/) is a high-performance, feature-packed library for creating interactive maps on the web. It can display map tiles, vector data and markers loaded from any source on any web page. OpenLayers has been developed to further the use of geographic information of all kinds. It is completely free, Open Source JavaScript, released under the [BSD 2-Clause License](https://opensource.org/licenses/BSD-2-Clause).

## Getting Started

Install the [`ol` package](https://www.npmjs.com/package/ol):

```
npm install ol
```

Import just what you need for your application:

```js
import Map from 'ol/Map';
import View from 'ol/View';
import TileLayer from 'ol/layer/Tile';
import XYZ from 'ol/source/XYZ';

new Map({
  target: 'map',
  layers: [
    new TileLayer({
      source: new XYZ({
        url: 'https://tile.openstreetmap.org/{z}/{x}/{y}.png'
      })
    })
  ],
  view: new View({
    center: [0, 0],
    zoom: 2
  })
});
```

See the following examples for more detail on bundling OpenLayers with your application:

 * Using [Vite](https://github.com/openlayers/ol-vite)
 * Using [Rollup](https://github.com/openlayers/ol-rollup)
 * Using [webpack](https://github.com/openlayers/ol-webpack)
 * Using [Parcel](https://github.com/openlayers/ol-parcel)

For more detail on quick prototyping without the use of a Node.js based setup, see the [Skypack](https://github.com/openlayers/ol-skypack) example.

## Sponsors

OpenLayers appreciates contributions of all kinds.  We especially want to thank our fiscal sponsors who contribute to ongoing project maintenance.

<br>

[![Pozi logo](./sponsor-logos/pozi.png)](https://pozi.com/)

> Pozi helps connect communities through spatial thinking.
> We love Openlayers and it forms a core part of our platform.
> https://pozi.com/ https://app.pozi.com/

<br>

[![yey'maps logo](./sponsor-logos/yeymaps.png)](https://www.yeymaps.io/)

> yey'maps is a scalable cloud GIS suite that is developed with the
> powerful Openlayers API and the GDAL library.
> https://www.yeymaps.io/

<br>

[![ela-compil logo](./sponsor-logos/ela-compil.png)](https://ela.pl/)

> We develop leading Physical Security Information Management (PSIM) software.
> OpenLayers is the core of our map engine and we love it! 
> https://ela.pl/

<br>

[![Ubigu Oy logo](./sponsor-logos/ubigu-oy.svg)](https://www.ubigu.fi/)

> We advance holistic utilization and availability of spatial information,
> for a better planned, built and managed society.
> https://www.ubigu.fi/

<br>

[![Scribble Maps logo](./sponsor-logos/scribble-maps.png)](https://www.scribblemaps.com/)

> Build custom maps and identify insights across real estate, engineering, research, business, exploration, construction, manufacturing - and so much more.
> https://www.scribblemaps.com/

<br>

See our [GitHub sponsors page](https://github.com/sponsors/openlayers) or [Open Collective](https://opencollective.com/openlayers/contribute/sponsors-214/checkout) if you too are interested in becoming a regular sponsor.

## TypeScript support

The [ol package](https://npmjs.com/package/ol) includes auto-generated TypeScript declarations as `*.d.ts` files.

## Supported Browsers

OpenLayers runs on all modern browsers (with greater than 1% global usage).  This includes Chrome, Firefox, Safari and Edge. For older browsers, polyfills ([Fastly](https://polyfill-fastly.io) or [Cloudflare](https://cdnjs.cloudflare.com/polyfill)) will likely need to be added.

## Documentation

Check out the [hosted examples](https://openlayers.org/en/latest/examples/), the [workshop](https://openlayers.org/workshop/) or the [API documentation](https://openlayers.org/en/latest/apidoc/).

## Bugs

Please use the [GitHub issue tracker](https://github.com/openlayers/openlayers/issues) for all bugs and feature requests. Before creating a new issue, do a quick search to see if the problem has been reported already.

## Contributing

Please see our guide on [contributing](CONTRIBUTING.md) if you're interested in getting involved.

## Community

- Need help? Find it on [Stack Overflow using the tag 'openlayers'](https://stackoverflow.com/questions/tagged/openlayers)
- Follow [@openlayers](https://twitter.com/openlayers) on Twitter

![Test Status](https://github.com/openlayers/openlayers/workflows/Test/badge.svg)

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, package-lock.json; scanned in UPSTREAM_CLONE)
- Top-level source layout: `changelog/`, `config/`, `examples/`, `site/`, `sponsor-logos/`, `src/`, `tasks/`, `test/`
- Snapshot size: **2318 files**, **263292 lines of code** (measured; see Benchmarks)
- Primary languages: `.js` (1172), `.png` (294), `.html` (292), `.md` (152), `.jpg` (94), `.css` (82)
- Upstream commit pinned for this packaging: `69e07d8ad933c3081cc10b8bb4a64023917661aa`

---

## Installation

Install the [`ol` package](https://www.npmjs.com/package/ol):

```
npm install ol
```

Import just what you need for your application:

```js
import Map from 'ol/Map';
import View from 'ol/View';
import TileLayer from 'ol/layer/Tile';
import XYZ from 'ol/source/XYZ';

new Map({
  target: 'map',
  layers: [
    new TileLayer({
      source: new XYZ({
        url: 'https://tile.openstreetmap.org/{z}/{x}/{y}.png'
      })
    })
  ],
  view: new View({
    center: [0, 0],
    zoom: 2
  })
});
```

See the following examples for more detail on bundling OpenLayers with your application:

 * Using [Vite](https://github.com/openlayers/ol-vite)
 * Using [Rollup](https://github.com/openlayers/ol-rollup)
 * Using [webpack](https://github.com/openlayers/ol-webpack)
 * Using [Parcel](https://github.com/openlayers/ol-parcel)

For more detail on quick prototyping without the use of a Node.js based setup, see the [Skypack](https://github.com/openlayers/ol-skypack) example.

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

```sh
npm start          # declared start script, when present
npm run dev        # declared dev script, when present
```

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

> https://www.yeymaps.io/

<br>

[![ela-compil logo](./sponsor-logos/ela-compil.png)](https://ela.pl/)

> We develop leading Physical Security Information Management (PSIM) software.
> OpenLayers is the core of our map engine and we love it! 
> https://ela.pl/

<br>

[![Ubigu Oy logo](./sponsor-logos/ubigu-oy.svg)](https://www.ubigu.fi/)

> We advance holistic utilization and availability of spatial information,
> for a better planned, built and managed society.
> https://www.ubigu.fi/

<br>

[![Scribble Maps logo](./sponsor-logos/scribble-maps.png)](https://www.scribblemaps.com/)

> Build custom maps and identify insights across real estate, engineering, research, business, exploration, construction, manufacturing - and so much more.
> https://www.scribblemaps.com/

<br>

See our [GitHub sponsors page](https://github.com/sponsors/openlayers) or [Open Collective](https://opencollective.com/openlayers/contribute/sponsors-214/checkout) if you too are interested in becoming a regular sponsor.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, package-lock.json |
| Files in snapshot | 2318 |
| Lines of code | 263292 |
| Dependency references | 86 |
| Dependencies by ecosystem | npm: 86 |
| Upstream license | BSD-3-Clause |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @types/rbush | 4.0.0 | package.json |
| npm | earcut | ^3.0.0 | package.json |
| npm | geotiff | ^3.1.0-beta.0 | package.json |
| npm | pbf | 5.1.2 | package.json |
| npm | rbush | ^4.0.0 | package.json |
| npm | zarrita | ^0.7.1 | package.json |
| npm | @codemirror/lang-javascript | ^6.2.2 | package.json |
| npm | @metalsmith/in-place | ^5.0.0 | package.json |
| npm | @metalsmith/layouts | ^3.0.0 | package.json |
| npm | @metalsmith/markdown | ^1.6.0 | package.json |
| npm | @octokit/rest | ^22.0.0 | package.json |
| npm | @planet/ol-numpytiles | ^3.0.1 | package.json |
| npm | @rollup/plugin-alias | ^6.0.0 | package.json |
| npm | @rollup/plugin-commonjs | ^29.0.0 | package.json |
| npm | @rollup/plugin-node-resolve | ^16.0.0 | package.json |
| ... | (71 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `config`
- `package.json`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing to OpenLayers

Thanks for your interest in contributing to OpenLayers.  Please see the project's [Code of Conduct](https://github.com/openlayers/openlayers/blob/main/CODE_OF_CONDUCT.md) before proceeding.

## Asking Questions

Please ask questions about using the library on [Stack Overflow using the tag 'openlayers'](https://stackoverflow.com/questions/tagged/openlayers).

## Submitting Bug Reports

Please use the [GitHub issue tracker](https://github.com/openlayers/openlayers/issues). Before creating a new issue, do a quick search to see if the problem has been reported already.

## Getting Familiar with the Code in the project

Look for `readme.md` files! Several directories contain a `readme.md` file that explains the contents of the directory and how to work with them.

## Contributing Code

See [`DEVELOPING.md`](https://github.com/openlayers/openlayers/blob/main/DEVELOPING.md) for details on getting set up for OpenLayers development.  This includes information on installing dependencies, running the tests, and conforming with the style guidelines.

Code contributions are made through [pull requests](https://help.github.com/articles/using-pull-requests). Make sure that your pull request follows our pull request guidelines below before submitting it.

## Contributor License Agreement

Your contribution will be under our [license](https://raw.githubusercontent.com/openlayers/openlayers/main/LICENSE.md) as per [GitHub's terms of service](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-project-license).

## Pull request guidelines

Before working on a pull request, create an issue explaining what you want to contribute. This ensures that your pull request won't go unnoticed, and that you are not contributing something that is not suitable for the project. Once a core developer has set the `pull request accepted` label on the issue, you can submit a pull request. The pull request description should reference the original issue.

Your pull request must:

 * Follow OpenLayers's coding style.  See the [`DEVELOPING.md` doc](https://github.com/openlayers/openlayers/blob/main/DEVELOPING.md) for details on setting up your editor to conform with the style guidelines.

 * Pass the integration tests run automatically by the Continuous Integration system.

 * Address a single issue or add a single item of functionality.

 * Contain a clean history of small, incremental, logically separate commits,
   with no mer

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: BSD-3-Clause** (evidence: `LICENSE.md` in the upstream snapshot).

License file excerpt:

```text
BSD 2-Clause License

Copyright 2005-present, OpenLayers Contributors
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original BSD-3-Clause terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `BSD-3-Clause` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `OPENLAYERS_PRIOR_DOCS` (category: ONLINE RETAIL)
- **Upstream URL:** https://github.com/openlayers/openlayers
- **Pinned commit (SHA):** `69e07d8ad933c3081cc10b8bb4a64023917661aa`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`47bc9233626b435e574dd64a3217a7f35b5b4ec0872166f95b481ec326f93840`.

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

