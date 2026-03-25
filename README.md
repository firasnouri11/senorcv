# 🎩 SenorCV — Professional CV Builder

> A beautiful, fully offline CV builder that runs entirely in your browser. No account, no server, no data collection — just open and build.

**Live demo:** [firasnouri11.github.io/senorcv](https://firasnouri11.github.io/senorcv)

---

## ✨ Features

### 10 Professional Templates
Classic, European, Modern, Tabular, Minimal, Creative, Executive, Sidebar, Compact, and Elegant — each with its own typography, layout, and color identity. Switch between them instantly with a live preview.

### Live Preview
Every keystroke updates the CV preview in real time. No refresh needed — what you type appears immediately on the page.

### Multi-Page Support
Content automatically flows to a second (and third, fourth…) page when it overflows. Each page is displayed as a clean A4 sheet in the preview with a proper "Page 2" header. Export always produces a correctly paginated PDF.

### Draft System (Auto-save)
- Your work is saved automatically every 3 seconds as you type
- Press **Ctrl+S** to save manually with a custom name
- All drafts are stored locally in your browser — they persist between sessions
- Open multiple drafts and switch between them from the Drafts panel
- Rename or delete drafts at any time

### PDF Export
One-click export to a multi-page PDF. The exported file uses the same layout and pagination as the live preview, with page headers on pages 2+.

### Sections
- **Personal Info** — name, title, email, phone, location, LinkedIn, website, summary
- **Experience** — job title, company, dates, description (supports bullet points with `-` or `•`)
- **Education** — degree, institution, dates, notes
- **Skills** — tag chips, type and press Enter to add
- **Languages** — dropdown for CEFR level (Native, C1, B2…), multiple display styles
- **Certifications** — name, issuer, date
- **Projects** — name, URL, date, description
- **Custom Sections** — add any section with any name (Publications, Awards, Volunteering…)

### Design Controls
- 12 accent color swatches + custom color picker
- 7 font families (Playfair Display, DM Mono, Fraunces, Lora, Raleway…)
- Font size slider (85–115%)
- Line height slider
- Margin width selector (narrow / normal / wide)
- Language display style: Inline, Stacked, Progress bars, Dots, Pill tags

### Photo
- Upload a profile photo
- Resize with a slider (48px → 160px)
- Toggle between **round** and **square** shape

### Section Management
- Drag to reorder sections in any order
- Toggle section visibility on/off
- Click a section title in the CV preview to jump directly to that section in the editor
- Highlight any text in the preview to jump to its section

### Compare All Templates
Side-by-side thumbnail grid of all 10 templates rendered with your actual content — click any to apply it instantly.

### ATS Score
A 12-point scoring rubric that estimates how well your CV will perform with Applicant Tracking Systems.

### Import CV
Upload an existing PDF or TXT file — the app extracts the text and pre-fills the form fields as best it can.

---

## 🔒 Privacy

SenorCV is **100% client-side**. Everything runs in your browser:

- No server, no database, no backend
- No data is ever sent anywhere
- Your CV content, photo, and drafts never leave your device
- Drafts are stored in your browser's `localStorage`
- No tracking, no analytics, no ads

The only external requests are loading fonts and PDF libraries from public CDNs (Google Fonts, cdnjs).

> ⚠️ **Note:** Drafts are tied to your browser. If you clear your browser data, drafts will be lost. Always download your PDF to keep a permanent copy.

---

## 🚀 Getting Started

No installation needed. Just open the HTML file:

```bash
# Option 1: Open directly in browser
open index.html

# Option 2: Serve locally
npx serve .
# or
python3 -m http.server 8000
```

Or visit the live version at [firasnouri11.github.io/senorcv](https://firasnouri11.github.io/senorcv)

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| Vanilla HTML/CSS/JS | Everything — no framework |
| [jsPDF](https://github.com/parallax/jsPDF) | PDF generation |
| [html2canvas](https://html2canvas.hertzen.com/) | Canvas snapshot for pagination |
| [PDF.js](https://mozilla.github.io/pdf.js/) | PDF text extraction on import |
| Google Fonts | Typography |
| localStorage | Draft persistence |

No build step. No npm. No dependencies to install. One file.

---

## 📁 Project Structure

```
index.html    ← The entire app (HTML + CSS + JS, self-contained)
README.md     ← This file
```

---

## 🤝 Contributing

Contributions are welcome! Some ideas for improvements:

- Additional templates
- More export formats (DOCX, Markdown)
- Cloud sync option (with user consent)
- Spell check integration
- More language level presets

Feel free to open an issue or submit a pull request.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 👤 Author

**Firas Nouri**
- GitHub: [@firasnouri11](https://github.com/firasnouri11)
- Email: [firasnouri111@gmail.com](mailto:firasnouri111@gmail.com)

---

*Made with ❤️ — because every professional deserves a great CV.*
