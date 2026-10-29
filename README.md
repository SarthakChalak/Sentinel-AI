Sentinel AI — Local Phishing & Threat Detection
Run it
Extract the ZIP.
Open `sentinel_ai_local/index.html` in Chrome, Edge, or Firefox.
It works as a static website. No backend, API key, database, or installation is required.
Optional local server: open a terminal in this folder and run `python -m http.server 8000`, then visit `http://localhost:8000`. This only serves static files; analysis still runs inside the browser.
Includes
URL heuristic scanner and explainable findings
Brand lookalike checks and URL structure checks
Message analyzer for urgency, credentials, financial requests, and suspicious links
Synthetic (not live) threat-monitor feed
Browser-local scan history, deletion, and CSV export
Responsive layout
Limitations
This is an educational prototype, not a commercial security product. Scores are heuristics from 1–10, not probabilities. Scores of 7–10 are High, 4–6 Medium, and 1–3 Low. It does not open URLs, query reputation services, or verify live website content. A low score does not mean a URL is safe. Scan history stays in this browser's localStorage. No external API or backend is used.
