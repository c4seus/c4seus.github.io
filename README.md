# c4seus.github.io

Personal site of [c4seus](https://github.com/c4seus), published with GitHub Pages.

## What is here

- `index.html`: home page listing public projects.
- `mon-suivi-candidature/privacy.html`: privacy policy for the Mon Suivi Candidature app, linked from the Play Store listing.

## Structure

```
.
├── index.html
├── mon-suivi-candidature/
│   └── privacy.html
└── README.md
```

Each app that needs a public page gets its own folder, so its URL stays stable (for example `https://c4seus.github.io/mon-suivi-candidature/privacy.html`). Please keep existing paths unchanged: other places, including store listings, link to them.

## Preview locally

The site is plain static HTML and CSS, with no build step. Open `index.html` directly in a browser, or serve the folder:

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deployment

GitHub Pages serves the `main` branch, from the root folder. Any push to `main` is published automatically within a few minutes.

## Licence

The projects linked from this site have their own licences. The content of this repository (HTML and CSS) is provided as is, without warranty.
