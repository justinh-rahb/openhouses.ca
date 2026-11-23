# OpenHouses.ca

Static retirement notice for OpenHouses.ca. Visitors are redirected to
[REALTOR.ca](https://www.realtor.ca/) after 30 seconds, with a direct link also
available. The redirect uses an HTML refresh and works without JavaScript.

## Development

Edit `index.html` and `styles.css`. Open `index.html` in a browser, or serve this
directory with any static web server. There are no packages to install and no
build step. The logo and favicon are served locally.

## Deployment

Publish this directory as a static site. Only `index.html`, `styles.css`,
`rahb-logo.png`, and `favicon.ico` are needed by the web server.

`vercel.json` explicitly disables framework detection, installation, and builds
so the existing Vercel project can serve the page directly after merging.
For other hosts, select static-site hosting with the repository root as the
publish directory and remove the previous `npm` build/start commands. No Node.js
or Next.js server is required.
