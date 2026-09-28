# CuratorOS Launch

A lightweight, dependency-free launcher for the Ocean Liner Curator / CuratorOS tool suite.

## Purpose

CuratorOS Launch is intentionally not another dashboard. It is a single static page whose only job is to make the full CuratorOS ecosystem easy to see, search, and open—especially from iPad or iPhone.

## Included destinations

- CuratorOS — https://curator.oceanliners.net/
- Curator Intelligence — https://tools.oceanliners.net/
- Curator Ops — https://ops.oceanlinercurator.com/
- Error Bus — https://errors.oceanliners.net/
- Content Opportunity Finder — https://content.oceanliners.net/
- Site Health — https://site-health.oceanliners.net/
- Curator Integrity — https://integrity.oceanliners.net/
- Curator Speed — https://speed.oceanliners.net/
- Search Intelligence — https://search-intelligence.oceanliners.net/
- Analytics — https://analytics.oceanliners.net/
- Link Map — https://link-map.oceanliners.net/
- Curator Indexer — https://curator-indexer.oceanliners.net/
- Page Studio — https://page-studio.oceanliners.net/
- Ocean Liner Curator — https://www.oceanliners.net/

Research Capture and Curator Verify are supporting backend/evidence services rather than standalone operator destinations, so they are intentionally not listed in Launch.

## Design

- one `index.html`
- no framework
- no dependencies
- no build step
- no backend
- no stored account or tool state
- responsive, touch-friendly layout
- built-in client-side search
- keyboard `/` focuses search and `Escape` clears it

## Deployment

The repository can be deployed directly with GitHub Pages from the repository root. It can also be placed behind a custom hostname such as `launch.oceanliners.net` without changing the app itself.
