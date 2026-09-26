# Marcos Skowronek Santos — personal website

A complete static academic website, ready for GitHub Pages. There is no build step, package installation, or JavaScript dependency. All content is in `index.html`, and all visual styling is in `styles.css`.

## Open the website

Double-click `index.html` to view it locally. The photo, PDF, navigation, and styling also work without an internet connection; external research links need internet access.

## Put it online with GitHub Pages

1. Sign in to [GitHub](https://github.com/login) as `MarcosSko`.
2. Create a **public** repository named `marcossko.github.io`.
3. Upload the **contents** of this folder to the repository. `index.html` must be at the repository's top level, alongside `styles.css` and the `assets` folder. Do not upload the ZIP itself or an extra enclosing folder. Include the empty `.nojekyll` file when possible.
4. In the repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, then select **main** and **/(root)** and save.
5. GitHub will show the published address in that panel, usually after a few minutes: `https://marcossko.github.io/`.

If that repository already exists, preserve its contents and review changes before replacing any files. This site also works in a project repository because all local asset paths are relative.

GitHub's instructions: [Create a Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) and [Configure the publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Update the site

- **Text and publications:** edit `index.html`. Each paper has its own `<li class="paper">` entry, grouped by the year the preprint first appeared. Update the footer's date when revising the content.
- **CV:** replace `assets/Marcos_Skowronek_CV.pdf`, retaining the filename.
- **Portrait:** replace `assets/marcos-skowronek.jpg`, retaining the filename. The original supplied photo is included unchanged; CSS controls how it fits the page.
- **Colors and spacing:** edit `styles.css`. The main color values are at the top.

The website contains no analytics, cookies, external fonts, forms, or embedded services. Publication data is intentionally static; INSPIRE remains linked for the current record.

## Content sources

Prepared on September 26, 2026 from the supplied CV, portrait, [INSPIRE author profile](https://inspirehep.net/authors/2696058?ui-citation-summary=true), and abstracts for all ten papers linked on the page. Journal information was cross-checked against INSPIRE. The academic record comes from the supplied CV. The research-interest headings and descriptions use Marcos’s supplied wording. No advisor was inferred from coauthorship.

The supplied CV is included unchanged. An isolated “June 2005 – Aug 2007” line in its appointments section had no associated position and was not reproduced in the webpage.

Design references: [Sérgio Carrôlo](https://scarrolo.github.io), [Ben Hollering](https://sites.google.com/view/benhollering), [Xavier Kervyn](https://xavierkervyn.github.io), and [Adolfo Hilario-Garcia](https://adolfo-hilario-garcia.xitxarra-7724.chatgpt.site). The site uses an original implementation inspired by their readable academic layouts.
