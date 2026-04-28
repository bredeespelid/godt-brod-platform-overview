# Godt Brød Operations Platform — Architecture Showcase

A single-page GitHub Pages site visualizing the architecture of an internal full-stack web app built for Godt Brød on Replit, consuming Microsoft Fabric SQL Analytics Endpoints.

## Deploy to GitHub Pages

1. Create a new public repository on GitHub (suggested name: `godt-brod-platform` or `operations-platform-overview`).
2. Add `index.html` to the root of the repo and push.
3. In repo **Settings → Pages**, set:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / `(root)`
4. Wait ~30 seconds. Your site will be live at:
   `https://bredeespelid.github.io/<repo-name>/`

## Custom domain (optional)

If you want it under `trendme.no/platform` or similar:

1. Add a `CNAME` file with your domain.
2. Add a CNAME / A record in your DNS provider.
3. Enable "Enforce HTTPS" in the Pages settings.

## What's on the page

- Hero with project framing
- Stats grid (pages, integrations, Fabric endpoints, RBAC roles)
- Architecture SVG diagram (Replit Express server, PostgreSQL, three Fabric SQL endpoints, Object Storage)
- Tech stack split by frontend / backend / data &amp; infrastructure
- 15+ external integrations, with the three Fabric SQL endpoints highlighted
- Domain model (35+ tables grouped by business domain)
- API surface sample
- Operational patterns (scheduled jobs, caching tiers, reliability)

## Editing

It's a single `index.html` with inline CSS — no build step, no dependencies. Open it in any browser to preview locally, or push directly to the GitHub Pages branch.

## Add to your CV

Once deployed, link it from the Projects section:

```latex
\resumeProjectHeading
  {\textbf{Godt Brød Operations Platform — Full-Stack Internal Web App on Replit} $|$ \emph{Work Project} {\href{https://bredeespelid.github.io/<repo-name>}{\color{blue}Architecture}}}{}
```
