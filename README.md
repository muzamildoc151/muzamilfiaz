# Muzamil Fiaz Portfolio

A responsive static portfolio designed for GitHub Pages.

## GitHub Pages + HTTPS

This site is intentionally built as a static website: `index.html`, `style.css`, and `script.js`.

1. Create a GitHub repository.
2. Upload these three files (and this README if desired).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your branch (usually `main`) and folder `/ (root)`, then save.
6. GitHub will provide a `github.io` address. Open **Settings → Pages** again after deployment and enable **Enforce HTTPS** when GitHub makes it available.

### Custom domain

If you use a custom domain:
- Enter the domain under **Settings → Pages → Custom domain**.
- Configure the DNS records at your domain provider as GitHub recommends.
- Wait for DNS/HTTPS verification.
- Then enable **Enforce HTTPS**.

**Important:** HTTPS cannot be enabled by HTML/CSS/JavaScript code. It is provided by GitHub Pages. This package is configured to work correctly as a static GitHub Pages site; the HTTPS switch is controlled by GitHub.

## Files

- `index.html` — website structure
- `style.css` — design and responsive layout
- `script.js` — mobile navigation and dynamic copyright year

No backend or build process is required.
