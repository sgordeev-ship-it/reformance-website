# Reformance website

Static draft of the Reformance website, built from the MECLABS website framework and the Reformance design system (Dark theme, Inter, core red #A5000A).

- Single file: `index.html`. No build step. Open it in a browser or deploy to any static host (GitHub Pages, Netlify, Vercel).
- Pages are hash routes: `#home`, `#services`, `#tracking`, `#google-ads`, `#meta-ads`, `#linkedin-ads`, `#seo`, `#data`, `#design`, `#about`.
- Service page copy lives in the `SERVICES` array at the bottom of `index.html`.
- The audit form is not connected yet. Wire its `submit` handler to your CRM or form endpoint before launch.

Before launch: confirm client name and logo permissions, and the Google Premier Partner claim (see the framework doc, Decisions).
