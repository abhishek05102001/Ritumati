# Ritumati Website — GitHub + Google Sheets

Simple architecture:
- GitHub = website code and photos
- Google Sheets = impact numbers and district numbers
- GitHub Pages = hosting
- No database, SQL, Supabase or secret keys

## Google Sheet
Use the supplied `Ritumati_Google_Sheet_Template.xlsx` and open it in Google Sheets.
Keep these tabs/headers:

Dashboard:
`women_reached | sessions | districts_reached | satisfaction | annual_goal | annual_completed`

Districts:
`name | city_alias | priority | description | active | pads_distributed | people_helped`

Publish the spreadsheet with **File → Share → Publish to web**. Then put the spreadsheet ID in `config.js`.

## GitHub Pages
Settings → Pages → Deploy from branch → main → /(root).

Expected URL: `https://abhishek05102001.github.io/Ritumati/`

## Photos
All photos are kept in GitHub:
- `assets/photos/testimonials/`
- `assets/photos/gallery/`

Replace the starter SVGs with approved JPG/PNG images using the same filenames, or update paths in `app.js`.

## Districts
The homepage shows only the six priority districts first:
Ranchi, East Singhbhum (Jamshedpur), Dhanbad, Bokaro, Hazaribagh and Giridih.

The **View all 24 districts** button reveals the remaining districts. Every district displays pads distributed and people helped.

Do not publish private beneficiary information. Use appropriate consent for real people's photos and quotes.
