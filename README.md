# Tender Summary Web App

## Run locally

```powershell
python app.py
```

Open `http://127.0.0.1:5001` in your browser.

## What it does

- Uploads a tender file (`.pdf`, `.docx`, `.txt`)
- Supports large digital tender PDFs up to 700 pages
- Extracts text from the full document
- Generates a structured tender summary
- Creates downloadable PDF and Word reports

## Notes

- The extractor uses label and pattern matching, so clean digital PDFs will work better than scanned image PDFs.
- The generated summary is limited to the exact tender summary sections configured in the app.
- Generated files are saved under `outputs/`.
