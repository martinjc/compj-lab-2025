# Libraries per 100,000 people — D3 demo

This small demo renders a horizontal bar chart from `access-to-libraries.csv` using D3.js.

How to view

- Preferred: run a simple HTTP server from the folder and open the page in your browser:

```bash
# macOS / Linux / Windows (with Python)
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

- Opening `index.html` directly (file://) may fail to load the CSV due to browser restrictions. Use the local server if you see no data.

Files

- `index.html` — the D3 page that loads `access-to-libraries.csv` and draws the chart.
- `access-to-libraries.csv` — the data file (must be in the same folder).

Notes

- The chart colours bars by the `Country` column (England / Wales). The page uses D3 v7 from the CDN.
- If you want a subset of rows or sorting controls, say the word and I can add interactive controls.
