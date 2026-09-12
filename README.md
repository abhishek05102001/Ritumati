# Ritumati V7 — Pink NGO Website

This version follows the approved pink reference layout.

## Simple architecture

- GitHub = website code + all public photos
- Google Sheets = impact numbers and district numbers
- GitHub Pages = hosting
- No SQL, Supabase, Firebase or database server

## Google Sheets

Dashboard columns:
`women_reached | sessions | districts_reached | satisfaction | annual_goal | annual_completed`

Districts columns:
`name | city_alias | priority | description | active | pads_distributed | people_helped`

Publish the spreadsheet to web as CSV, then put the Spreadsheet ID in `config.js`.

## Photos

All current visual assets are local in GitHub:
- `assets/hero.jpg`
- `assets/mission.jpg`
- `assets/photos/districts/`
- `assets/photos/testimonials/`
- `assets/photos/gallery/`

Replace these placeholder/reference images with approved Ritumati photos when available.

## GitHub Pages

Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.

Expected URL:
`https://abhishek05102001.github.io/Ritumati/`
