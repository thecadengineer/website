# CAD Engineer website

Static, fast, SEO-focused single-page site for a mechanical design / CAD engineer in Yorkshire.

## Publish on GitHub Pages
1. Upload the contents of this folder to the root of a public GitHub repository.
2. In Settings → Pages, select Deploy from a branch, `main`, and `/ (root)`.
3. Configure `cadengineer.co.uk` as the custom domain and add the DNS records GitHub specifies.
4. Enable Enforce HTTPS when available.

## What changed (performance & SEO)
- Removed the heavy procedural Three.js turbine (large JS, WebGL, continuous animation). The page is now static-image based and loads far faster, especially on mobile.
- Hero and project section use the supplied biomass elevator / inclined cleated belt conveyor image.
- STEP model (`biomass_elevator.main_design.step`) is offered for download as a portfolio deliverable example.
- Meta description, title, Open Graph, Twitter card and JSON-LD `ProfessionalService` schema updated.
- Natural keyword coverage retained and extended: mechanical design engineer Yorkshire, CAD design services UK, 3D CAD modelling, industrial conveyor design, biomass elevator, SolidWorks, sketch to prototype, engineering drawings, 3D printing prototype Yorkshire.
- Clean heading hierarchy, descriptive alt text, canonical URL, robots.txt and sitemap.xml.
- Minimal JS (year + mailto form only). No external script dependencies beyond Google Fonts.
- Responsive layout retained; images use `loading` attributes.

## Contact
The enquiry form still uses `mailto:contact@contact.com`. Replace with a real business inbox before going live.

## Assets included
- `index.html` — optimised page
- `biomass-elevator.jpg` — product photograph
- `biomass_elevator.main_design.step` — 3D model (≈1.3 MB)
- `robots.txt`, `sitemap.xml`
