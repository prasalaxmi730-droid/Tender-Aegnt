# Tender Summary Web App

## Run locally

```powershell
python app.py
```

Open `http://127.0.0.1:5000` in your browser.

## What it does

- Uploads a tender file (`.pdf`, `.docx`, `.txt`)
- Extracts text from the full document
- Generates a structured tender summary
- Creates downloadable PDF and Word reports

## Notes

- The extractor uses label and pattern matching, so clean digital PDFs will work better than scanned image PDFs.
- Generated files are saved under `outputs/`.
