An-Nisa Mission website: deployment notes
1. Upload everything in this folder (index.html, assets/, robots.txt, sitemap.xml) to the web root of annisamission.org. No build step is needed.
2. Language: English is the default. Visitors can switch to Bengali with the toggle in the top bar; the choice is remembered. Add ?lang=bn to a link to open the Bengali version.
3. Admission enquiry form currently opens the visitor's email app. For direct delivery, connect it to a form service (e.g. Formspree) or a backend.
4. Update yearly: fees, "Board results" figures, and the prospectus PDF (assets/An-Nisa-Mission-Prospectus.pdf).
5. Replace photos by overwriting files in assets/ with the same names. Better-quality originals are recommended.
6. If the domain differs from annisamission.org, update the canonical, og:image, sitemap and robots.txt URLs in index.html.
