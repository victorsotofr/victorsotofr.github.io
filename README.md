# Victor Soto — personal website

A small, static personal website inspired by the typography and composition of [pierre.computer](https://pierre.computer/). Original HTML and CSS; no framework, dependencies, analytics, or build step.

## Preview

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open http://127.0.0.1:4173. Content is in `index.html`; appearance is in `style.css`. The site follows the device's light/dark setting. Reduced-motion preferences disable the cursor animation.

## Publishing

1. Create the public GitHub repository `victorsotofr/victorsotofr.github.io` and push these files to `main`.
2. In the repository's **Settings → Pages**, choose **Deploy from a branch**, then **main / (root)** and save.
3. Wait for the Pages deployment to complete and check https://victorsotofr.github.io/.

`.nojekyll` keeps publication buildless. No custom domain is configured. Future changes publish when pushed to `main`. Preview content and check links before pushing.

The canonical and Open Graph URLs target https://victorsotofr.github.io/. The public site is hosted by GitHub Pages.

## Content notes

Experience titles and dates follow Victor's supplied LinkedIn content and corrections; the résumé supplies short descriptions. INY World and Databird show years only. Technical lines describe the relevant product stack, not ownership of every component. Chess is a local project mention only: no book content, exercises, diagrams, or private project assets are included.
