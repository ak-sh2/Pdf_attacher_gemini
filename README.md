# PDF Sequential Attacher (`Pdf_attacher_gemini`)

A 100% client-side web application to attach and merge multiple PDF files in the exact chronological order they are uploaded.

## Features

- **Strict Upload Order Queue**: Automatically locks and attaches PDFs in the exact sequence they are uploaded (`Upload #1` → `Upload #2` → `Upload #3`).
- **Live Attachment Blueprint**: Shows the exact output page ranges each uploaded PDF will occupy in the combined file.
- **Per-File Page Range Selection**: Attach all pages or filter specific page ranges (e.g., `1-3, 5`) per document.
- **Section Cover Sheets & Continuous Page Numbering**: Optional toggle to stamp `Page X of Y` footers or insert clean section divider pages between attached PDFs.
- **Built-In PDF Viewer & Print-to-PDF**: Preview combined pages directly and save via standard download or native `Save as PDF`.

## Live Deployment (GitHub Pages)

1. Go to **Settings** → **Pages** in [`ak-sh2/Pdf_attacher_gemini`](https://github.com/ak-sh2/Pdf_attacher_gemini).
2. Under **Build and deployment**, select **Deploy from a branch** and choose `main` / `/ (root)`.
3. Your live app will be available at `https://ak-sh2.github.io/Pdf_attacher_gemini/`.
