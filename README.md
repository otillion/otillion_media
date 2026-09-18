# Otillion

Cinematic content. Intelligent systems.

Single-file site (EN/TR). No build step, no dependencies except Google Fonts.

## Deploy on GitHub Pages
1. Create a repo and upload `index.html` (keep the name exactly).
2. Settings > Pages > Source: `Deploy from a branch` > Branch: `main` / root.
3. The site goes live at `https://<user>.github.io/<repo>/` in a minute or two.

Custom domain: add a file named `CNAME` containing your domain, then point an A/CNAME record at GitHub Pages.

## Editing
- All copy lives inline as `<span data-en>` / `<span data-tr>` pairs.
- Brand colors and fonts are CSS variables at the top of the `<style>` block.
- WhatsApp link: search for `wa.me` and replace the number.
