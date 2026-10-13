# The Reverse Emo Changeling - Architecture Hub (`github.emo-changeling.xyz`)

Official technical one-pager, architecture hub, and machine discovery endpoints for the **The Reverse Emo Changeling** decentralized ecosystem.

## Overview

This repository hosts the static architecture hub served via GitHub Pages at [github.emo-changeling.xyz](https://github.emo-changeling.xyz/). It is designed with a strict zero-bloat philosophy:

- **Bilingual Zero-JS:** Native static English (`index.html`) and Polish (`pl.html`) editions switched through semantic links.
- **Modern MySpace Aesthetic:** Authentic mid-2000s subcultural style paired with modern CSS standards and zero graphic headers.
- **Zero Third-Party Assets:** No external CDNs, no Google Fonts, zero external network calls.
- **Equal Access:** Identical information architecture for human readers, classic search engines, and LLM synthetic agents.
- **Machine Discovery:** Native JSON-LD Schema.org graphs, Agent Resource Discovery (`.well-known/ai-catalog.json`), `.well-known/agent.json`, and `llms.txt`.
- **Cryptographic Provenance:** Public GPG signed commits and OpenPGP Ed25519 detached signatures (`.asc`) for all source files.

## File Hierarchy

```text
.
├── .gitignore
├── .well-known/
│   ├── agent.json
│   └── ai-catalog.json
├── css/
│   └── style.css
├── CNAME
├── index.html
├── pl.html
├── llms.txt
├── robots.txt
├── sitemap.xml
└── README.md
```

## Security & Verification

- **Master PGP Fingerprint:** `55B1F5E9342F388E6F06483C34A85D454D1FD3BC`
- **Signing Key:** Ed25519 detached signatures (`.asc`) verify the integrity of each asset.
- **Hosting:** Static GitHub Pages with Cloudflare Edge proxying.
