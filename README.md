# Forking CV Template (Fork)

![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Fork](https://img.shields.io/badge/Fork-CV_Template-blue?style=for-the-badge)

> **CV/Resume template fork** â€” A fork of a markdown/HTML CV template for personal customization.

---

## âš ï¸ **This is a Fork**

**Original Repository:** Not identified (likely a popular CV template like `nicksherefkin/ns.markdown.cv` or similar)

This fork exists for:
- Personal CV customization
- Learning markdown-to-HTML CV workflows
- Template experimentation

---

## ðŸŒŸ Overview

A curriculum vitae template designed to be written in Markdown (or HTML) and rendered as a professional PDF/web page. The original template likely provides:
- Clean, printable layout
- Markdown source for easy editing
- CSS for styling (print + screen)
- Build script for PDF generation

---

## âœ¨ Features (Inferred)

| Feature | Description |
|---------|-------------|
| **Markdown Source** | Write CV in readable markdown |
| **HTML Output** | Rendered web version |
| **PDF Generation** | Print-optimized CSS â†’ PDF |
| **Responsive Design** | Works on screen and paper |
| **Sections** | Education, Experience, Skills, Projects, Publications |
| **Theming** | Color schemes, fonts customizable |

---

## ðŸ›  Tech Stack (Inferred)

| Layer | Technology |
|-------|------------|
| **Source** | Markdown / HTML |
| **Styling** | CSS3 (Print + Screen media queries) |
| **Build** | Pandoc / WeasyPrint / Puppeteer / wkhtmltopdf |
| **Deployment** | GitHub Pages / Netlify / Vercel |

---

## ðŸ“ Project Structure (Typical)

```text
forking-cv/
â”œâ”€â”€ cv.md                 # Source content (Markdown)
â”œâ”€â”€ index.html            # Rendered HTML (or generated)
â”œâ”€â”€ css/
â”‚   â”œâ”€â”€ screen.css        # Screen styles
â”‚   â”œâ”€â”€ print.css         # Print/PDF styles
â”‚   â””â”€â”€ themes/
â”‚       â”œâ”€â”€ default.css
â”‚       â””â”€â”€ dark.css
â”œâ”€â”€ scripts/
â”‚   â”œâ”€â”€ build-pdf.sh      # Pandoc/WeasyPrint command
â”‚   â””â”€â”€ watch.js          # Live reload during editing
â”œâ”€â”€ assets/
â”‚   â”œâ”€â”€ fonts/
â”‚   â””â”€â”€ images/
â”œâ”€â”€ package.json          # If Node-based build
â””â”€â”€ README.md             # This file
```

---

## ðŸš€ Quick Start

```bash
# Clone this fork
git clone https://github.com/orange-05/forking-cv.git
cd forking-cv

# Edit your CV
# Option 1: Edit cv.md directly
# Option 2: Edit index.html if HTML-based

# Build PDF (if build script exists)
./scripts/build-pdf.sh
# or
npm run build:pdf
# or
pandoc cv.md -o cv.pdf --css=css/print.css

# Preview HTML
open index.html
# or
npx serve .
```

---

## âœï¸ Customization

### Content
Edit `cv.md` (or `index.html`) with your:
- Personal info
- Education
- Work experience
- Projects
- Skills
- Publications/Awards
- Links (GitHub, LinkedIn, Portfolio)

### Styling
Modify CSS variables in `css/themes/default.css`:
```css
:root {
  --font-main: 'Inter', system-ui, sans-serif;
  --font-mono: 'JetBrains Mono', monospace;
  --color-primary: #1e3a8a;
  --color-text: #1f2937;
  --spacing: 1.5rem;
  --page-margin: 2cm;
}
```

### PDF Output
Adjust `css/print.css` for:
- Page size (A4/Letter)
- Margins
- Page breaks (`page-break-before: always`)
- Header/footer (page numbers)

---

## ðŸ”§ Build Tools Comparison

| Tool | Command | Pros |
|------|---------|------|
| **Pandoc** | `pandoc cv.md -o cv.pdf --css=print.css` | Mature, flexible, markdown-native |
| **WeasyPrint** | `weasyprint index.html cv.pdf` | Excellent CSS support, Python |
| **Puppeteer** | `node scripts/pdf.js` | Full Chrome engine, JS support |
| **wkhtmltopdf** | `wkhtmltopdf index.html cv.pdf` | Fast, Qt WebKit based |

---

## ðŸ¤ Contributing

**This is a personal fork â€” not open for contributions.**

To improve the template, contribute to the original repository.

---

## ðŸ” Finding the Original

```bash
# Check git history
git log --oneline --all --graph | head -30

# Check remote
git remote -v
```

Popular CV templates to check:
- `nicksherefkin/ns.markdown.cv`
- `sb2nov/resume`
- `jsonresume/resume-cli`
- `there4/markdown-resume`

---

## ðŸ“„ License

**Unknown** â€” Check original repository. Common: MIT, CC0, or CC-BY.

---

## ðŸ‘¤ Fork Owner

**Karthikeyan K** (BCA Analytics)
- GitHub: [@orange-05](https://github.com/orange-05)
- Location: Bengaluru, India

---

*Forked for personal CV â€” original template author unknown.* â€” Documented July 2026