### A Local Search UI for Cloudflare.tv

Currently, searching for previous videos on Cloudflare.tv is difficult. This project is a proof of concept which uses [lunr.js](https://lunrjs.com/) to index and search previously uploaded videos. The data was fetched using the API from Schedule page.

The site's code is ~~copied~~ heavily adapted from [VectorLogoZone](https://github.com/VectorLogoZone/vectorlogozone/blob/gh-pages/www/index.html) but with JQuery dependency removed.

#### TODO:
- Work correctly on mobile devices
- Make responsive
- Improve aesthetic (slightly)
- Reduce static JSON size
