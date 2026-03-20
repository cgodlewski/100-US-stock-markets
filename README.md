# One Hundred Years in the U.S. Stock Markets

**A research companion website for:**

> Bessembinder, H. (2026). *One Hundred Years in the U.S. Stock Markets.*
> W. P. Carey School of Business, Arizona State University. Initial draft: March 18, 2026.
> Available at SSRN: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6438198

---

## About

This is a static, single-page research companion site built around the data and results of the working paper above. It is intended as a scholarly exhibit for researchers, doctoral students, and advanced readers in finance and asset pricing.

The site has no affiliation with the author or Arizona State University. It does not represent an official publication. All numerical claims are drawn directly from the paper as cited; no figure is approximated without explicit labeling.

---

## What the site covers

| Section | Content |
|---------|---------|
| Abstract | Verbatim from the paper |
| Key Results | Six primary empirical findings (source-exact) |
| Return Distribution | Mean–median gap; positive skewness visualization |
| The Power of Compounding | Altria vs. Vulcan Materials comparison (Table 1) |
| Wealth Tiers | Three-tier decomposition of 29,081 firms (Section 3) |
| Concentration of SWC | Firms needed for 50% of wealth, by period (Table 7) |
| Top Wealth Creators | Full Table 5 — top 30 firms by SWC, 1926–2025 |
| Top Cumulative Returns | Full Table 1 — top 30 stocks by buy-and-hold return |
| By Decade | Table 3 — % beating T-bills each decade + median BHR |
| Citation & Access | Full reference and SSRN link |

---

## Data sources

All data displayed on the site are sourced from the following tables and sections of the paper:

- **Section 2** — buy-and-hold return statistics, proportion of stocks exceeding benchmarks
- **Section 3** — shareholder wealth creation (SWC) decomposition
- **Table 1** — top 30 stocks by cumulative buy-and-hold return
- **Table 3** — decade-horizon buy-and-hold returns
- **Table 5** — top 30 firms by SWC, 1926–2025
- **Table 7** — concentration of net SWC by period

Underlying data: CRSP monthly stock return database, CIZ version, January 1926 – December 2025. Treasury-bill data supplement Professor Kenneth French's series with SBBI historical data for January–June 1926.

---

## Design

- Single HTML file — no framework, no build step, no dependencies beyond Google Fonts and Chart.js (CDN)
- Typography: Libre Baskerville (headings), EB Garamond (body), Source Code Pro (data labels)
- Color palette: cream background, deep navy and dark red accents
- Charts: Chart.js 4.4.1
- Fully self-contained: rename `index.html` and serve from any static host

---

## Live site

Hosted via GitHub Pages:
**https://[your-username].github.io/bessembinder2026-site/**

---

## Deploying your own copy

```bash
# 1. Clone
git clone https://github.com/[your-username]/bessembinder2026-site.git
cd bessembinder2026-site

# 2. Edit index.html as needed

# 3. Push
git add .
git commit -m "update"
git push
```

GitHub Pages will serve the `index.html` from the `main` branch automatically once Pages is enabled in the repository settings (Settings → Pages → Source: Deploy from branch → main → / (root)).

---

## Citation

```
Bessembinder, H. (2026). One Hundred Years in the U.S. Stock Markets.
W. P. Carey School of Business, Arizona State University.
Initial draft: March 18, 2026.
SSRN: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6438198
```

Related earlier study:

```
Bessembinder, H. (2018). Do stocks outperform Treasury bills?
Journal of Financial Economics, 129, 440–457.
```

---

*This repository is a research communication project. No endorsement by the author or Arizona State University is implied.*
