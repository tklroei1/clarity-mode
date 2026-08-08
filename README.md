# Clarity Mode

A concept marketing & product experience for **Clarity Mode** — an AI writing layer that
translates dense technical language into precise, audience-ready communication for engineering,
sales-engineering, and customer-success teams.

Three self-contained, responsive HTML pages (no build step, no dependencies):

| Page | File | What it is |
|------|------|------------|
| Landing | `index.html` | Product landing page for the flagship *Technical Clarity Mode* feature |
| Onboarding | `onboarding.html` | Post-signup onboarding flow with a live "before / after" transformer |
| Dashboard | `dashboard.html` | Performance analytics dashboard (funnel, adoption, insights) |

## Highlights

- **Fully responsive** — mobile, tablet, and wide-desktop breakpoints across every page,
  including a mobile hamburger menu on the landing page and adaptive grids on the dashboard.
- **Zero dependencies** — pure HTML/CSS/vanilla JS. All styles are inline; charts on the
  dashboard are rendered with hand-written JS.
- **Accessible interactions** — keyboard-reachable nav, `aria-expanded` state on the menu
  toggle, and semantic structure.

## Run it

Just open any of the HTML files in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Design system

A light editorial theme (`#F9F9F7` canvas, `#11EE91` accent) on the marketing pages and a
dark analytics theme on the dashboard, unified by the Inter typeface and a&�onsistent radius /
shadow scale defined via CSS custom properties.
