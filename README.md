# CAD Engineer — interactive 3D hero website

A static, responsive website for GitHub Pages. The 3D hero is rendered in the browser with Three.js and can be rotated, zoomed and switched between assembled and exploded views.

## Before publishing
1. Open `index.html`.
2. Find `const CONTACT_EMAIL='replace-with-your-email@example.com';`
3. Replace the placeholder with the email address that should receive enquiries.
4. Review the service descriptions and make sure they match the services and delivery capacity you actually offer.
5. Replace the illustrative 3D machine with a representative model of your own work when available.

## Publish free with GitHub Pages
1. Create a GitHub repository, for example `cadengineer-website`.
2. Upload `index.html` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. GitHub will provide a public `https://YOUR-USERNAME.github.io/cadengineer-website/` address.
7. To use `cadengineer.co.uk`, add the custom domain in the Pages settings and configure the DNS records at your domain provider. Enable HTTPS once DNS has propagated.

## Google Sites
Google Sites does not directly host a custom HTML/CSS/JavaScript site as a native website. Host this folder on GitHub Pages, then use **Insert → Embed → By URL** in Google Sites to embed the hosted page. For the full-screen, responsive design and 3D interaction, GitHub Pages is the better option.

## Technical notes
- Static hosting only; no server or paid hosting required.
- Three.js and Google Fonts load from public CDNs, so visitors need an internet connection.
- The enquiry form opens the visitor's email application. It does not store or send form submissions itself.
- The 3D conveyor-like assembly is a procedural illustrative model, not a dimensionally accurate client deliverable.
