# Orbit Academy — Space Quiz

Orbit Academy is a single-page space exploration quiz. Answer ten questions about
the Solar System, get immediate feedback and facts, and see your score when the
mission is complete.

## Run locally

No build tools or dependencies are required. Open `index.html` in a browser, or
serve the repository directory over HTTP:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deployment

The GitHub Actions workflow in `.github/workflows/pages.yml` packages
`index.html` and deploys it to GitHub Pages whenever changes are pushed to
`main`. Pull requests run the same packaging check without deploying.
