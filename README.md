# ACatalyst v3

A static portfolio for ACatalyst, featuring three fictional concept businesses: Sundown Coffee, Edge & Co. barbershop, and Petal House flower studio. Each has a website view and a matching promotional poster. These examples are portfolio concepts, not client projects.

## Preview locally

From this directory, run `python -m http.server 8000`, then open `http://localhost:8000/`. Select any project on the homepage. Each project's poster page has a **Print / save PDF** button.

## Publish through your connected GitHub repository

Copy **all contents** of this directory into the root of your local `acatalyst` repository, replacing the old files. From that repository, run:

```sh
git add .
git commit -m "Add three portfolio concepts"
git push
```

Cloudflare Pages should deploy the new commit automatically. For the existing static setup, keep framework **None**, build command `exit 0`, and output directory `.`. The ChatGPT Sites copy is separate from this GitHub deployment.

The images in `assets/` were generated for these fictional portfolio concepts.
