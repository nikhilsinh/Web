# localbench

A file-tool workbench (JPG ⇄ PDF, compress to target KB, resize in px/%/cm/inches,
convert, crop, rotate, watermark, grayscale) that runs entirely in your browser.

No upload. No account. No server. Everything happens with the Canvas API and
File API built into your browser — files never leave your device. The badge in
the header counts real network requests live, so you can watch it stay at zero
while you use any tool.

## Use it

Live: `https://YOUR-USERNAME.github.io/localbench/`

Or just download `index.html` and open it directly in any browser — works
fully offline.

## Tools

**PDF ⇄ JPG**
- JPG to PDF (reorder pages, page size, orientation, quality)
- PDF to JPG (extracts embedded JPEG pages)
- Compress PDF to target KB

**Image**
- Compress to target KB or manual quality
- Resize (pixels, %, cm, inches @ DPI, with presets)
- Convert format (JPG/PNG/WebP)
- Crop, rotate/flip, watermark, grayscale/B&W

## Limits

PDF→JPG and Compress PDF work on PDFs made of embedded JPEG images (scans,
photo-PDFs, anything built by this app's own JPG→PDF tool). PDFs with vector
text need a full PDF library — not included here to keep this a zero-dependency,
single-file app.
