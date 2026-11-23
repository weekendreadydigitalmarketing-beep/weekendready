# WeekendReady

**Timed one-day walking routes for city breaks.** WeekendReady is a single-file web app that plans a day on foot in six cities: Wrocław, Kraków, Warsaw, Gdańsk, Poznań and Prague.

> Student project for the DMSM (Digital Marketing & Social Media) course. Walking times are estimates until a route has been walked and timed.

## Features

- **City picker** – six cities, each with its own link (e.g. `#city-krakow`)
- **One-day guide** per city – map, time at every stop, downloadable PDF
- **Free short walk** – 3 stops
- **Lunch stop** – 4–5 real places to choose from, your pick is saved and added to the PDF
- **Plan my day** – enter your time and interests, get a route in walking order with lunch between 11:30 and 14:30
- **Create your route** – ~20 places per city, filters, search, “Put stops in walking order”
- **Events** – Christmas markets 2026 with countdown, “Add to calendar” (.ics) and an evening route
- **Saved** – your routes, lunch picks, events and blog posts (stored in your browser only)
- **Photos** – loaded from Wikimedia Commons (free licences only), author and licence shown on each photo
- **Light / dark / auto theme**, Poppins font, traffic-light loading screen

## Run it

No build, no install, no server.

- **Locally:** download `index.html` and open it in a browser.
- **Online:** see GitHub Pages below.

Photos need an internet connection. For an offline copy, use **“Save a copy with photos”** in the footer or in *About*.

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under *Build and deployment* choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After about a minute the app is live at `https://<your-username>.github.io/<repo-name>/`.

The `.nojekyll` file tells GitHub Pages to serve the files as they are.

## Repository structure

```
.
├── index.html          # the whole app (HTML + CSS + JS in one file)
├── assets/
│   └── brand/          # logo (SVG/PNG) and brand kit
├── docs/
│   └── BRAND.md        # colours, fonts, brand personality
├── CREDITS.md          # data and photo sources
├── LICENSE
├── .nojekyll
└── .gitignore
```

## Data and privacy

- City data (sights, lunch places, Christmas markets) was checked in October 2026 against Wikipedia, OpenStreetMap and official city and organiser websites. Opening hours change – check them on the day.
- Where a fact could not be confirmed, the app says so (e.g. “Dates not announced yet”).
- The app has no account, no analytics and no ad cookies. Saved routes stay in the browser’s local storage on your device.

## Tech

Plain HTML, CSS and JavaScript in one file. Photos via the Wikipedia/Wikimedia API. PDFs and `.ics` calendar files are generated in the browser.

## Licence

Code: MIT (see `LICENSE`). Photos remain under their own Wikimedia Commons licences, credited in the app and in `CREDITS.md`. The WeekendReady name and logo belong to the project team.
