# Telecom HTML Dashboard

This is the browser-hosted prototype for the Telecom Operations & Customer Analytics Power BI project.

## Pages
1. Executive Overview
2. Customer & Churn
3. Revenue & Plans
4. Network Performance
5. Service & Complaints

## Data
The dashboard loads the supplied synthetic telecom CSV files directly in the browser.

## Local preview
Browsers may block CSV loading from a `file://` URL. Use one of these methods:

### Python
Open a terminal in this folder and run:
`python -m http.server 8000`

Then open:
`http://localhost:8000`

### GitHub Pages
Upload the entire folder contents to the root of a GitHub repository and enable GitHub Pages.

## Important
Keep the CSV files in the same directory as `index.html`.
