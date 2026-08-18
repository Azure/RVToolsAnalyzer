# RVTools Analyzer

A single-file, client-side analyzer for VMware RVTools exports. Upload your RVTools
`.xlsx` and get instant inventory insights, VCF 9 / vSphere 9 compatibility analysis,
Azure migration sizing (Native VMs, AVS, SQL on Azure), and live pricing across 18
currencies — all without sending data anywhere.

## Live site

Hosted via GitHub Pages from this repo: **[https://azure.github.io/RVToolsAnalyzer/](https://azure.github.io/RVToolsAnalyzer/)**

## How it works

`index.html` is a fully self-contained single-page application — everything (HTML,
CSS, JS, pricing snapshots, fonts, logos) is inlined. Open the file directly in a
browser or serve it from any static host. **No data ever leaves your browser.**

## Current build

- **Version**: `vundefined`
- **Last published**: 2026-08-18 07:03 UTC
- **Source**: built and published automatically from
  [shaunjacob/RVTools-Analyzer](https://github.com/shaunjacob/RVTools-Analyzer)

## Features

- VM inventory, host/cluster summaries, storage and snapshot breakdowns
- VCF 9 / vSphere 9 hardware and CPU support analysis
- Azure Native VM sizing & pricing (PAYG, 1y/3y RI, 1y/3y Savings Plan, AHUB)
- Azure VMware Solution (AVS) sizing and pricing
- Azure SQL sizing (MI, Hyperscale, SQL on IaaS) with AHB savings
- Live Azure Retail Prices API integration with weekly snapshot refresh
- 18 currencies, 60+ Azure regions
- Export to Excel / CSV / PDF

## License & source

See the upstream repository for source, issues, and contributions:
[shaunjacob/RVTools-Analyzer](https://github.com/shaunjacob/RVTools-Analyzer).
