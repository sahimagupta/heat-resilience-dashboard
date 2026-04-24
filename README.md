# Heat Resilience Force — Globe From Home

A single-page pitch site for **Globe From Home (GFH) Heat Resilience Force** — an AI-assisted programme that helps schools in climate-vulnerable regions become heat-resilient institutions and unlock international climate finance.

🌐 **Live site:** Enable GitHub Pages in repo settings → it serves from `index.html` automatically.

---

## What this is

`index.html` is a self-contained, zero-dependency landing page (~52 KB) that presents:

- **The problem** — heat mortality, school closures, learning loss, and the disproportionate impact on girls' education in the Global South.
- **The 6-module programme (M1 → M6)** — pairing human operational work (audit, training, protocols, planning) with four AI agents (Heat Monitor, Alert Engine, Vulnerability Scorer, Plan Generator) built on Claude Haiku.
- **Climate finance pathway** — how a completed Heat Action Plan converts into a GCF / Adaptation Fund / FCDO / GIZ-ready application, targeting the $70M GCF BRACE facility (Project FP274).
- **Interactive alert demo** — drag-to-adjust temperature + humidity sliders that trigger the same research-backed thresholds the platform uses (38°C, 45°C, 54°C), using the NOAA Rothfusz heat-index equation.

## Tech

- One HTML file. No build step, no bundler, no framework.
- Inline CSS (design tokens via CSS custom properties) + vanilla JS for scroll reveal, nav highlighting, and the live demo.
- Google Fonts: DM Serif Display, DM Sans, DM Mono.
- Data sources referenced in-page: Open-Meteo, WAQI, Google Earth Engine.

## Run locally

```bash
git clone https://github.com/sahimagupta/heat-resilience-dashboard.git
cd heat-resilience-dashboard
# open index.html in a browser, or:
python -m http.server 8000
# then visit http://localhost:8000
```

## Partners referenced

Columbia Climate School · British Council · UN SDSN · Prof. Carlos Nobre (Nobel Laureate) · Ban Ki-Moon Centre · AFT

## License

All rights reserved — pitch material for Globe From Home.
