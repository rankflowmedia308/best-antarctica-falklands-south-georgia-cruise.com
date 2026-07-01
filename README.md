# best-antarctica-falklands-south-georgia-cruise.com

Independent ranking site for Antarctica + Falklands + South Georgia cruise operators.

## File structure

```
├── index.html                  ← Main ranking page
├── methodology.html            ← Rating criteria
├── about.html                  ← About the site
├── editorial-policy.html       ← Editorial independence
├── contact.html                ← Contact form
├── submit-operator.html        ← Operator submission form
├── faq.html                    ← 15 FAQs + JSON-LD
├── terms-and-conditions.html   ← Terms
├── css/
│   ├── global.css              ← Reset, typography, header, footer
│   └── index.css               ← Main page styles
├── images/                     ← All images (ships + hero + logo)
├── sitemap.xml
├── robots.txt
└── .nojekyll                   ← Required for GitHub Pages
```

## Editing content

- Edit HTML files directly — no build step required
- All pages are self-contained with shared CSS
- All asset paths are relative (works on GitHub Pages)

## Deploying to GitHub Pages

```bash
git add -A
git commit -m "Update content"
git push
```

GitHub Pages redeploys automatically within ~1 minute.

## Adding a new page

1. Copy any existing page as a template
2. Update `<title>`, `<meta description>`, `<link rel="canonical">`
3. Set `class="active"` on the correct nav link
4. Add the page URL to `sitemap.xml`
