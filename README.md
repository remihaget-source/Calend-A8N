# Calend-A8N

Static demo pages (self-contained HTML, no build step).

- **`ecosystem-mapping.html`** — Macro-allocation demo for investment funds. Define a fund thesis
  (target deep-tech domain, geography, company size, minimum revenue, existing portfolio) and the
  engine maps 8 deep-tech domains × 10 sub-technologies each onto an investment graph:
  **x = relatedness density**, **y = complexity**. Signal is derived from the structure of the
  economy across research papers (250M), patents (80M), capital flow, talent market and policy.
- **`partnership.html`** — One-page A8N × Bodic partnership analysis for the founders' working
  session. A "current situation → how do we build a partnership?" recap on top, then two columns —
  **Tech** (technical convergence) and **Commercial** (business-development convergence) — each with
  bullet points and a one-sentence summary, closing on the single convergence thesis.
- `index.html` — Argos event calendar 2026–2027.
- `survey.html` — survey page.

Open any file directly in a browser, or serve the folder:

```
python3 -m http.server
```
