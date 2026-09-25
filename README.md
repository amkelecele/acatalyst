# ACatalyst

A static website for ACatalyst. The public site currently also exists on ChatGPT Sites.

## Cloudflare Pages (Git integration)

Connect this repository to Cloudflare Pages. Choose **None** as the framework preset, set the build command to `exit 0`, and set the build output directory to the repository root (`.`). The repository root contains `index.html`.

Updates to the production branch deploy automatically after Cloudflare's initial setup.
