# ACatalyst v2

A visual portfolio update for ACatalyst with a fictional café website and matching printable poster. This is a static site for Cloudflare Pages.

## Preview locally

From this directory, run:

```sh
python -m http.server 8000
```

Open `http://localhost:8000/`. View the café at `/work/sundown/` and its poster at `/work/sundown/poster.html`. Use the poster's **Print / save PDF** button for a print copy. The café and its copy are fictional concept work.

## Publish through your connected GitHub repository

Copy the contents of this directory into the root of your local `acatalyst` repository, replacing `index.html`, `README.md`, and `robots.txt`. Then from that repository:

```sh
git add .
git commit -m "Add visual portfolio and Sundown concept"
git push
```

Cloudflare Pages should deploy the new commit automatically. Your existing Pages settings stay: framework None, build command `exit 0`, output directory `.`.

The ChatGPT Sites copy is separate and will not update from GitHub.

## Asset

The café photograph in `assets/sundown-cafe.png` was generated for this fictional portfolio concept. It is used by the portfolio, café website, and poster.
