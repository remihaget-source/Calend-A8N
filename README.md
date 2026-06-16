# Calend-A8N

Static demo pages (self-contained HTML, no build step).

- **`ecosystem-mapping.html`** — Macro-allocation demo for investment funds. Define a fund thesis
  (target deep-tech domain, geography, company size, minimum revenue, existing portfolio) and the
  engine maps 8 deep-tech domains × 10 sub-technologies each onto an investment graph:
  **x = relatedness density**, **y = complexity**. Signal is derived from the structure of the
  economy across research papers (250M), patents (80M), capital flow, talent market and policy.
- `index.html` — Argos event calendar 2026–2027.
- `survey.html` — survey page.

Open any file directly in a browser, or serve the folder:

```
python3 -m http.server
```
