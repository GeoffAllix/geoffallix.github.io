# Geoff Allix — Personal CV Website

A single-page personal website / CV built for hosting on GitHub Pages.

## Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `geoff-allix.github.io` or any name)
2. Upload `index.html` to the repository root
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose `main` branch, `/ (root)` folder, and click **Save**
6. Your site will be live at `https://yourusername.github.io/repo-name` within a minute or two

## Custom Domain (optional)

To use a custom domain (e.g. `geoff.allix.net`):

1. In **Settings → Pages**, enter your domain under **Custom domain**
2. Add a `CNAME` file to the repo root containing just your domain:
   ```
   geoff.allix.net
   ```
3. Add a CNAME DNS record pointing your domain to `yourusername.github.io`

## Updating Content

All content is in `index.html`. Key sections to update:

- **Contact details** — search for `geoff@allix.net` and `+44 (0)1454 262482`
- **LinkedIn URL** — replace `https://linkedin.com` with your actual profile URL
- **Stats** — update the four hero numbers if needed
- **Experience bullets** — in the `#experience` section
- **Projects** — in the `#projects` section

## Structure

Single file, no build step required. Uses:
- Google Fonts (DM Serif Display + DM Sans) loaded via CDN
- Pure HTML/CSS/JS — no frameworks, no dependencies
- Fully responsive for mobile
