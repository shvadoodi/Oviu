# OVIU Studio website

Source code for the public OVIU Studio website at `https://oviu.ca/`.

The site is a static multilingual landing page for OVIU Studio, OVIU Prints, and OVIU Kids.

## Local preview

Open `index.html` directly in a browser, or run a simple local server:

```powershell
python -m http.server 4173
```

Then visit `http://localhost:4173`.

## Routes

- `/` and `/en-ca` - English
- `/fr-ca` - French
- `/fa` - Persian

The static script also supports direct hash navigation such as `/#pricing`.
