### A Local Search UI for Cloudflare.tv

Currently, searching for previous videos on Cloudflare.tv is difficult. This project is a proof of concept which uses [lunr.js](https://lunrjs.com/) to index and search previously uploaded videos. The data was fetched using the API from Schedule page and deduplicated on title + description.

The site's code is ~~copied~~ heavily adapted from [VectorLogoZone](https://github.com/VectorLogoZone/vectorlogozone/blob/gh-pages/www/index.html) but with JQuery dependency removed.

#### TODO:
- ~~Work correctly on mobile devices~~ (Fixed by using replace instead of replaceAll for formatting markdown)
- ~~Make responsive~~ (No longer horribly undersized on mobile)
- Improve aesthetic (slightly) -> For most purposes it is ok. Can probably add a background color??
- ~~Reduce static JSON size~~ -> From 4MB to 330KB with deduplication
