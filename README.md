# Talvex — Digital products, built with intent

A responsive, static website for Talvex Private Limited. The site uses semantic HTML, custom CSS, and a small amount of vanilla JavaScript. It has no build step or framework dependencies.

## Run locally

Open `index.html` in a browser, or run a local static server from this directory:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Contact form

The contact form validates the fields and prepares an email addressed to `talvexpvt@gmail.com` using the visitor's email application. A hosted form endpoint can replace this behavior if server-side submissions are needed.

## Deploy

This site can be deployed as a static site on Netlify, GitHub Pages, or any static web host. No build command is needed; publish the repository root.
