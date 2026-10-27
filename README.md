# László Zoltán — personal academic website

Single-page site (English / Hungarian / Romanian) for GitHub Pages.

## Files
- `index.html` — the whole site (styles and scripts inline)
- `.nojekyll` — tells GitHub Pages to serve the files as they are
- `photo.jpg` — optional portrait; add it next to `index.html` (initials "LZ" show until then)

## Publish on GitHub Pages
1. Create a repository named `<your-username>.github.io` (gives the address `https://<your-username>.github.io`), or any other name (gives `https://<your-username>.github.io/<repo>`).
2. Upload `index.html`, `.nojekyll` and, optionally, `photo.jpg` to the repository root.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)` → Save.
4. The site is live within a minute or two.

## Pages and languages
Layout follows okologiamodell.com: title header, dropdown menu, main column with sidebar.
Pages are sections of the same file, reached by links such as `#cv`, `#publications`, `#teaching`, `#research`, `#students`, `#contact`.
Hungarian is the default; hu / en / ro buttons switch language (remembered in the browser). Direct links: `?lang=en`, `?lang=ro`.
All page texts are in the `T` object in the script at the end of `index.html`.

## Publications
- "Selected publications" is a static list with confirmed DOIs — edit it in the `<ol class="pubs">` block.
- "All publications" loads live from the public ORCID API (ORCID 0000-0001-5064-4785) when the section is opened, so it stays current as you update ORCID.
