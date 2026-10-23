# MCU Watch Tracker

A responsive, fan-made MCU watch tracker for browsing Marvel films, series, specials, release order, story timeline, and universes.

## Features

- Overview dashboard with watched count, completion percentage, average rating, and phase progress
- Release-order catalogue with search and filters
- Story timeline with Blip and multiverse markers
- Universe explorer
- Watch status, watch date, and rating controls
- CSV export for watch progress and timeline
- Light/dark appearance based on the visitor's browser/operating-system preference
- Progress stored locally in the current browser using local storage

## Run locally

Open `index.html` in a modern browser. An internet connection is only needed for the externally hosted Poppins font.

## Deploy to Vercel from GitHub

1. Create a GitHub repository named `mcu-watch-tracker`.
2. Upload `index.html` to the repository root, along with this README and `.gitignore`.
3. Import the repository into Vercel.
4. Select **Other** as the Framework Preset.
5. Leave Build Command and Install Command empty.
6. Set Output Directory to `.` if Vercel asks for it.
7. Deploy.

This is a static site; it does not require a server, database, environment variables, or build step. The catalogue data is embedded in `index.html`; no separate `data.json` file is required.

## Data and privacy

Watch progress is saved in local storage in the visitor's browser. It is not uploaded to a server and does not sync across browsers or devices. Clearing browser storage can erase saved progress. The CSV export can be used to keep a separate copy.

## Disclaimer

This is an unofficial fan-made project and is not affiliated with, endorsed by, or sponsored by Marvel, Marvel Studios, Disney, or Sony. Names and trademarks belong to their respective owners. Release dates, universe labels, and continuity notes are provided for informational purposes and may change or be disputed.
