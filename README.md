# Baltimore Backyard Movies

Local landing site for **baltimorebackyardmovies.com** — Baltimore's backyard movie night experts, powered by [Premiere Outdoor Movies](https://www.premiereoutdoormovie.com/).

## About

This is a standalone local-SEO landing site built to rank for Baltimore-metro outdoor movie searches and drive leads to the Maryland team, led by owner-operator Jordon DeSoto. It's part of the Premiere Outdoor Movies network and links back to the main brand throughout.

- **Positioning:** Backyard-first (birthdays, block parties, HOA events, graduations, family nights)
- **Service area:** Baltimore City, Baltimore County, Howard, Anne Arundel, and Harford counties (Towson, Columbia, Ellicott City, Annapolis, Bel Air, and surrounding communities)
- **Contact:** 443-610-4522 · eventsmd@premiereoutdoormovies.com

## Running Locally

```bash
npm install
npm start
```

The site will be served at `http://localhost:3000`.

## Structure

```
Baltimore-Backyard/
├── public/
│   └── index.html     # The full landing page (single-file: HTML + inline CSS + JS)
├── server.js          # Simple Express static server
├── package.json
└── README.md
```

## SEO Notes

- Single H1, proper H2 hierarchy
- Valid LocalBusiness + FAQPage JSON-LD schema
- Canonical URL, Open Graph, Twitter Card meta tags
- 33 diverse backlinks to premiereoutdoormovie.com (varied anchor text)
- Mobile-responsive, all `target="_blank"` links use `rel="noopener"`
