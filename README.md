# Rajeev Manick — personal research website

A responsive, static academic/research portfolio built with HTML, CSS and a small amount of JavaScript. No build step or framework is required.

## Preview locally
1. Unzip this folder.
2. Open `index.html` in a browser. For a local server, run `python3 -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Personalise before publishing
Search the project for `TODO` and replace the following:
- `YOUR.EMAIL@EXAMPLE.COM` in `index.html` with your public professional email.
- The generic GitHub link with the exact BICEPs repository URL (or remove the link until the repository is public).
- Add your verified Google Scholar, ORCID, GitHub and LinkedIn profile URLs.
- Add a `cv.pdf` file and a CV link if you want the CV hosted here.
- Replace the publication placeholder with verified publication titles, DOI links and status.
- Review the biography and project descriptions for accuracy and preferred wording.

## Publish for free, then attach your domain
Recommended: GitHub Pages or Cloudflare Pages for this static site. Vercel is also suitable.
1. Create a GitHub repository, e.g. `rajeev-manick-website`.
2. Upload the contents of this folder to the repository root.
3. Enable GitHub Pages in repository Settings → Pages (deploy from the `main` branch / root).
4. Buy a domain from a registrar and add it in the hosting provider's custom-domain settings.
5. Follow the provider's DNS instructions exactly. DNS records vary by provider; do not copy records from an unrelated tutorial.

## Domain / identity
`rajeev.manick` works well as a compact visual identity or username. For a conventional public website, a domain such as `rajeevmanick.com` or another available extension may be easier to communicate. Domain availability and trademark conflicts have not been checked.

## Design notes
- Dark scientific palette with cyan accents and abstract orbital geometry drawn in CSS.
- Responsive layout and mobile navigation.
- Sections: About, Research, Projects, Publications, Contact.
- Fonts load from Google Fonts; system fallbacks remain available.
