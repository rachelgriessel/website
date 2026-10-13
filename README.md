# Rachel Griessel — website

A single-page static site. No build step: plain HTML, Tailwind CSS (v4 browser build via CDN) and Alpine.js for the interactive bits.

## Run locally

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Contact form

The form posts to [Web3Forms](https://web3forms.com) (free, no server needed).

1. Go to web3forms.com, enter the email address that should receive enquiries, and copy the access key they email you.
2. In `index.html`, replace `YOUR_ACCESS_KEY_HERE` with that key.

The key is safe to commit — it only allows sending to the registered address.

## Deploy to GitHub Pages

Repo **Settings → Pages → Build and deployment → Deploy from a branch → `main` / root**. The site will be live at `https://rachelgriessel.github.io/website/` (or a custom domain set in the same screen).
