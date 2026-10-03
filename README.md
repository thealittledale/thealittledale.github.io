# Thea Littledale — Portfolio

A single-file, no-build-tools portfolio website for Thea, a third-year graphic design student in Bristol, UK. Open `index.html` in any browser to view it, or host it anywhere (GitHub Pages, Netlify, Vercel — just drag and drop the file).

## Design direction

Editorial, risograph-print inspired: a cool stone-paper background, a bold display serif (Fraunces) paired with a grotesk sans (Archivo) and a mono accent (Space Mono), and a two-color "riso overprint" motif — flat cobalt blue and magenta ink, echoed in the halftone-dot textures, project thumbnails, and hero name. Plus a scrolling ticker marquee, a custom cursor, and scroll-triggered reveals.

## How to customize

Name, location, tagline, and bio are already filled in. What's still placeholder is marked with `EDIT:` comments in `index.html`:

1. **Projects** — six `<article class="project">` blocks in the "Selected Work" section. Each has a title, category/index label, year, and one-line description. To use real project photos instead of the generated halftone placeholders, add `<img src="your-image.jpg" alt="Project name">` as the first element inside `.project-art` — it will fill the frame automatically.
2. **About** — the pull-quote (currently a generic line about honest design — worth swapping for something more Thea) and the skills tags.
3. **Contact** — the email address (`hello@example.com`) and social links (currently `#` placeholders — Instagram, LinkedIn, Behance).
4. **Colors** — all defined once as CSS variables at the top of the `<style>` block (`--ink`, `--paper`, `--accent`, `--pink`, `--moss`). Change those to re-theme the whole site.

No build step, no dependencies beyond Google Fonts (loaded via `<link>` in the `<head>`).
