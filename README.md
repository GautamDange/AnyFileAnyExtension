# Text File Generator (Single-Page HTML)

A tiny, self-contained HTML page that lets you paste text, choose a filename + extension, and **download it as a file** directly from your browser.

## Features

- **Local-only**: runs entirely in your browser (no backend).
- **Filename + extension** inputs with quick extension chips (`.txt`, `.html`, `.js`, `.json`, `.c`, `.css`, `.tex`, `.cpp`).
- **One-click download** using the browser’s download mechanism.

## How to use

1. Open `AnyFileAnyExt.html` in a browser (Chrome / Firefox / Edge).
2. Set **File Name** and **Extension** (or click a chip).
3. Paste content into the big text area.
4. Click **Download File**.

The downloaded file will be named like `filename + extension` (example: `notes` + `.txt` → `notes.txt`).

## Run via a local web server (optional)

Opening the file directly usually works, but if your browser has restrictions, serve it locally:

```bash
cd AnyFileAnyExtension
python3 -m http.server 8000
```

Then open `http://localhost:8000/AnyFileAnyExt.html`.

## Project structure

```text
AnyFileAnyExtension/
  AnyFileAnyExt.html   # The full app (HTML + CSS + JS)
  README.md
  LICENSE
```

## License

MIT — see `LICENSE`.

