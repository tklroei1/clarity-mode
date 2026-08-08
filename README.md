# Clarity Mode — Product Design Exercise

**An independent product design exercise** exploring a calmer, focus-oriented writing experience —
a concept for translating dense technical language into clearer, audience-ready communication.

> **This is an independent product design exercise. It is not affiliated with, endorsed by, or
> produced by Grammarly.** All names, metrics, and analytics shown are **illustrative demo data**
> created to demonstrate the design — they are not real usage figures or research results.

## What's here

Three self-contained, responsive HTML pages (no build step, no dependencies):

| Page | File | What it is |
|------|------|------------|
| Landing | `index.html` | Concept landing page for the design |
| Onboarding | `onboarding.html` | Onboarding flow with a live "before / after" transformer |
| Dashboard | `dashboard.html` | A mock analytics dashboard (illustrative data only) |

The three pages interlink via a small footer nav.

## Status & scope

- A front-end **prototype / concept**. The interactive pieces (menu, before/after transformer, charts)
  run entirely client-side; there is no backend, account system, or real data.
- Dashboard figures are **hand-authored sample values** for layout demonstration, not measurements.

## Run it

Open any of the HTML files in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

Works fully offline and in a private window — nothing is loaded from local-only files.

## Design system

A light editorial theme on the concept pages and a dark analytics theme on the dashboard, unified by the
Inter typeface and a consistent radius / shadow scale defined via CSS custom properties.
