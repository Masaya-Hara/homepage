# Masaya Hara — Personal Website

Personal academic website for Masaya Hara (原 誠弥), Assistant Professor at NIT, Anan College.

## Files

```
masaya-hara-site/
├── index.html        # English version
├── index-ja.html     # Japanese version (日本語版)
├── shared.css        # Shared stylesheet
├── favicon.svg       # Site icon (original geometric motif)
└── README.md
```

## Hosting on GitHub Pages

1. Create a new GitHub repository (e.g. `masayahara.github.io` or any name)
2. Upload all files in this folder to the repository root
3. Go to **Settings → Pages → Source: main branch / root**
4. Your site will be live at `https://username.github.io/repo-name/`

For a custom domain (e.g. `masayahara.net`):
- Add a `CNAME` file containing your domain name
- Configure DNS with your domain registrar

## Updating content

- **New paper**: add a `<div class="pub-item">` block in both `index.html` and `index-ja.html`
- **New talk**: add a `<div class="pres-item">` block in both files
- **Surfaces**: replace the base64 image data with new images

## Notes on surface images

The two surface images (Bonnet-type, Enneper-type) are embedded as base64-encoded PNG 
directly in the HTML, so no separate image files are needed.
To update images, convert your new images to base64 and replace the data strings.
