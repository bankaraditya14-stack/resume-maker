# Smart ATS Resume Builder

This is a single-page resume builder that lets you:

- Build an ATS-friendly resume step-by-step
- Preview it live
- Download as **PDF** or **PNG**

## ✅ How to run

### Option 1 (recommended): Run a local web server
Many browser features (clipboard, downloads, etc.) work best when the page is served over HTTP.

From the project folder, run:

```powershell
python -m http.server 8000
```

Then open:

```
http://localhost:8000
```

### Option 2: Open directly (file://)
You can also open `index.html` directly in your browser, but some features may behave differently (clipboard, downloads).

---

## 🛠️ How to use

1. Click **Get Started**
2. Complete the wizard steps
3. Fill in your details in the builder
4. Download as PDF or image

---

## Notes

- The page relies on external CDNs (Tailwind, html2pdf.js). If you're offline, you may not see the styling or download functionality.
- If you want to customize templates or keywords, edit the JavaScript objects near the bottom of `index.html`.
