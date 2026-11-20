# Le Duc Chinh — Portfolio

Personal portfolio of **Le Duc Chinh**, Java Backend Developer and Computer Science student at HUST.

🌐 Live: **https://9hdzprovip.bbroot.com**

## Stack
Single static page: HTML, Tailwind CSS (CDN) and vanilla JavaScript, deployed with GitHub Pages under a custom domain (`CNAME`).

## Updating personal info
Open `index.html`, find `SITE_CONFIG` near the bottom and fill in:

| Key | Example | Used for |
|---|---|---|
| `email` | `chinh@example.com` | "Send an Email" button and copy-email box |
| `linkedin` | `https://www.linkedin.com/in/...` | LinkedIn buttons |
| `cv` | `cv/LeDucChinh_CV.pdf` | All "Download CV" buttons (upload the PDF to the repo) |
| `libraryRepo` | `https://github.com/...` | GitHub button of the Library Management project |

Any empty value hides the related button, so the page never shows broken links or placeholders.

## Structure
```
index.html   # the website
CNAME        # custom domain for GitHub Pages
design/      # original Stitch prompt, design tokens and reference screenshot
```
