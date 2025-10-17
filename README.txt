DEPLOYMENT NOTES

Files included:
- index.html  — main landing page
- privacy.html — privacy policy page

Lightweight analytics:
- The head of index.html includes a Plausible snippet.
- Replace `yourdomain.com` in the `data-domain` attribute with your actual domain before deploying.

Static hosting (Netlify or GitHub Pages):
1) Upload both files to a new repo (or drag-drop to Netlify).
2) Ensure index.html is at the project root.
3) Publish — that's it.

Framer:
1) Create a new site > Add a Code Override page or use the HTML Embed.
2) Paste the contents of index.html into a custom code section (or rebuild with Framer blocks using the same copy).
3) Publish and point your domain.

Webflow:
1) Create a new project > Add a blank page.
2) Rebuild the sections (Hero, Benefits, Ingredients, Reviews, FAQ, Footer) using the same text.
3) Or use "Page Settings > Custom Code" to embed styles/head elements if doing a quick import.
4) Publish, then update the Plausible data-domain in your custom code settings.

Compliance reminders:
- Keep claims benefit-focused and experience-based.
- Avoid medical guarantees or disease treatment language.
- Maintain the affiliate disclosure and privacy policy link in the footer.
