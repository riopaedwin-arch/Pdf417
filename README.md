# Canada VR — Synthetic Test Generator

A self-contained front-end replica-style interface for synthetic PDF417/AAMVA software testing.

## Repository structure

```text
canada-vr-clone/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── app.js
├── .gitignore
├── LICENSE
└── README.md
```

## Run locally

No build step is required.

Open `index.html` in a browser, or serve the folder with any static web server.

Example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to Vercel

Import this GitHub repository into Vercel as a static site. No framework or build command is required.

## Important

This repository is intended for synthetic software-testing fixtures. It should not be used to create, reproduce, or validate real government identification documents or real personal data.
