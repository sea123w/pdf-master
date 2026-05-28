<h1 align="center">📑 PDF Master</h1>
<p align="center"><strong>Free, private, browser-based PDF toolkit. No uploads, no ads, no tracking.</strong></p>
<p align="center">
  <img src="https://img.shields.io/badge/privacy-first-green" alt="Privacy First">
  <img src="https://img.shields.io/badge/no-uploads-blue" alt="No Uploads">
  <img src="https://img.shields.io/badge/license-MIT-brightgreen" alt="MIT License">
  <img src="https://img.shields.io/badge/processing-client--side-purple" alt="Client-Side">
</p>

---

## Why PDF Master?

Every other "free PDF tool" uploads your files to a server. Tax returns, contracts, business plans — they all pass through some random company's servers. **PDF Master processes everything locally in your browser.** Your files never leave your device. Period.

## Features

| Tool | Description |
|------|-------------|
| 📑 **Merge** | Combine multiple PDFs into one. Drag & drop to reorder. |
| ✂️ **Split** | Extract page ranges or split into individual pages. |
| 📦 **Compress** | Reduce PDF file size. Three compression levels. |
| 💧 **Watermark** | Add diagonal text watermarks. Customize opacity, size, color. |
| 📄 **Extract** | Pull specific pages from a PDF into a new file. |
| 🔄 **Rotate** | Rotate pages 90°/180°/270°. Apply to all, odd, or even pages. |

## How It Works

```
Your Browser (PDF-lib WebAssembly)
    ↓
Load PDF → Process Locally → Save Result
    ↓
Zero bytes sent to any server ✓
```

Uses [pdf-lib](https://github.com/Hopding/pdf-lib) for all PDF manipulation — compiled to WebAssembly, running entirely client-side.

## Pro Version ($19 Lifetime)

- Unlimited batch processing
- Advanced compression engine
- Custom watermark templates
- Priority support
- Free updates forever

**[Buy PDF Master Pro →](https://gumroad.com)**

## Self-Host / Run Locally

```bash
git clone https://github.com/weeklab/pdf-master.git
cd pdf-master
npx serve .
# Open http://localhost:3000
```

No build step. No dependencies to install. Just an HTML file and two CDN scripts.

## Tech Stack

- **PDF Processing**: [pdf-lib](https://github.com/Hopding/pdf-lib) (WebAssembly)
- **File Export**: [FileSaver.js](https://github.com/eligrey/FileSaver.js/)
- **Zero server dependencies** — single static HTML file

## Privacy

- ✅ Files processed entirely in your browser
- ✅ No analytics, no tracking, no cookies
- ✅ No file ever transmitted to any server
- ✅ Works offline after first load
- ✅ Open source — verify the code yourself

## License

MIT © WeekLab Ventures

---

<p align="center">
  <sub>Built with ❤️ by <a href="https://github.com/weeklab">WeekLab Ventures</a></sub>
</p>
