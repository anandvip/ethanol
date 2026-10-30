# Ethanol in India — an open policy baseline

**Live page:** https://ethanol.vipulanand.in/ (once GitHub Pages and DNS are set up)

This repository is an **open baseline for agents and analysts doing crop assessment and policy critique** of India's ethanol programme. It brings together, in one static page:

1. How farmers in 10 states (UP, Maharashtra, Karnataka, Bihar, MP, Rajasthan, Gujarat, TN, Punjab, Haryana) reach the relevant schemes, with official guidelines and websites
2. What is verified about E100 (G.S.R. 911(E), 23 Oct 2026) and the Supreme Court position
3. Feedstocks: sugarcane, maize and grain (FCI rice)
4. Process, plants, investment and policy
5. GST on ethanol and on farm inputs
6. Central and state officials: published contacts only, each with its source and the date it was checked
7. A full source log, split into sources that yielded and sources that did not. Videos and public circulars are marked, and restricted documents are listed as known but not public
8. Open gaps

Baseline date: **30 October 2026 (IST)**.

## Pills used on the page

| Pill | Meaning |
|---|---|
| **Grokcos** | That section or block was researched and written by Grok Bot. It lets a reviewer compare it with other tools' drafts and question each one separately |
| **Link fixed** | The original URL was dead or wrong; the link now points to a working official page |
| **Link revised** | The cited URL redirects; the current address is shown |
| **Unverified** | Seen in only one secondary source; confirm before relying on it |
| **Inference** | A reasoned deduction, not a published statement |

## Rules this baseline follows

- Facts, names, numbers and contacts come only from the cited pages. Nothing is invented.
- Officials' contacts are taken only from official pages. Leads that appear only in the press are kept separate, in a caveat.
- Every external link opens in a new tab with `rel="noopener"`.
- No third-party scripts. The Microsoft Clarity snippet is a commented-out placeholder (`YOUR_CLARITY_ID`) and is **off**.
- The page embeds its own fonts and needs no build step.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole page: self-contained HTML, CSS and fonts, with SEO head and JSON-LD |
| `CNAME` | Custom domain `ethanol.vipulanand.in` for GitHub Pages |
| `robots.txt` | Allows all crawlers and points to the sitemap |
| `sitemap.xml` | Single-URL sitemap |
| `README.md` | This file |

## Publishing (owner to-dos)

1. **GitHub Pages:** Settings → Pages → Source: *Deploy from a branch* → Branch `main`, folder `/ (root)`.
2. **DNS:** at the `vipulanand.in` DNS host, add `CNAME  ethanol  →  anandvip.github.io`.
3. Once the certificate is issued, tick **Enforce HTTPS** in the Pages settings.

## Reuse

You are welcome to read, fork and critique it. If you build on it, please re-check the sources: government pages move, and figures change with each sugar season.
