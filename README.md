# ODEV

Office of Geothermal Strategy Management. Org development companion to [The Thermal Underground](https://thermalunderground.org).

Live: [odev.thermalunderground.org](https://odev.thermalunderground.org)

Source outline: `source/OG-Strategy-Management-2026.pptx` (Commercial Scale-Up redesign, 2026 strategy cycle, operating model, SWGs and initiatives).

## Serve this site

Requires Node 20 or later.

```
npm run dev
```

Opens at `http://localhost:5176`.

## Pages

- `/` Home
- `/organization/` Commercial Scale-Up structure
- `/cycle/` Six-stage strategy management
- `/model/` Operating model
- `/groups/` Strategy Working Groups and Strategic Initiatives

## Deploy

Pushes to `main` deploy via GitHub Actions Pages.

### DNS

At the `thermalunderground.org` registrar, add:

```
odev    CNAME    adlerarcher.github.io
```

In this repo, GitHub Pages should use the custom domain `odev.thermalunderground.org` with Enforce HTTPS. The `CNAME` file in the root is that domain.
