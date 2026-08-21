# BlackSwampAnalyticsSite

# Black Swamp Analytics

Marketing site for Black Swamp Analytics Ltd, a northwest Ohio GIS and land use analysis practice.

Live at [blackswampanalytics.com](https://blackswampanalytics.com)

## What this is

A single page static site. Everything lives in `index.html`: markup, CSS, and the illustrated SVG scene bands are all inline. There is no build step, no framework, and no dependencies. Open the file in a browser and what you see is what deploys.

This is deliberate. The site changes a few times a year, and a self contained file means no toolchain to maintain and nothing to break between edits.

## Structure

```
index.html     the entire site
README.md      this file
```

## Editing

Open `index.html` in any text editor.

The page is organized top to bottom as hero, services, selected work, about, and contact. Section dividers are inline SVG illustrations rather than images, so they scale cleanly and add no requests. Colors are defined once in a variables block near the top of the stylesheet, so palette changes happen in one place.

To preview locally, open the file directly in a browser. No server required.

## Deploying

Hosted on Cloudflare Pages, connected to this repository. Pushing to the default branch triggers a deploy automatically.

Pages settings:

| Setting | Value |
| --- | --- |
| Framework preset | None |
| Build command | *(empty)* |
| Build output directory | `/` |

The empty build command matters. Setting a framework preset will cause Pages to attempt a build that does not exist here and fail.

## Content notes

Project entries in Selected Work lead with the analytical problem rather than the software used, and name data limitations openly. Keep that pattern when adding work.

Projects tied to counties where the principal has held public employment are intentionally excluded from this site. Do not add them without checking first.

## Contact

David Price, Principal
[email]
