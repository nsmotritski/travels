# travels

Bilingual seasonal travel pages. English is the default. The EN / RU switch remembers your choice in this browser.

- `index.html`: seasonal collection
- `winter/solden/`: seven nights / eight calendar days in Austria, with five ski days and travel by car
- `summer/`, `mid-season/`: future trips
- `assets/`: shared styles and scripts

All new names use lowercase and hyphens. Tentative dates: 30 January – 6 February 2027 (subject to change). Departure: Wrocław. Four travellers: two skiers, two non-skiers. Target accommodation: two bedrooms, a living room and kitchen. Nine property options are listed in the accommodation section. Published tariffs, source links, assumptions and unconfirmed availability are recorded in winter/solden/housing-research.json. The alpine SVG is an illustration, not a photograph of the resort. Piste map image: Sölden / Ötztal, sourced from https://skitrips24.co.uk/piste-map-solden/ ; edition unconfirmed, with links to the official live map and download portal. Resort information links to official sources.

## preview

Run `python3 -m http.server 8765` in the repository, then open http://localhost:8765/ . No build needed. Static hosting is supported; deployment has not been configured.

## github pages

In repository Settings > Pages, choose Deploy from a branch, branch `develop`, folder `/ (root)`, then Save. The site uses relative links and needs no build. Expected URLs:

- https://nsmotritski.github.io/travels/
- https://nsmotritski.github.io/travels/winter/solden/
