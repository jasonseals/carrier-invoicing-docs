Carrier Invoicing API — Stoplight Elements Viewer
================================================

How to run locally
------------------
1) Ensure these two files are in the same folder:
   - index.html
   - carrier-invoicing.yaml

2) Start a simple local server in this folder:
   - Python 3:  python -m http.server 5500
   - Node:      npx http-server -p 5500

3) Open your browser to:
   http://localhost:5500

How to host/share
-----------------
- GitHub Pages: push both files to a repo, enable Pages in Settings.
- Netlify/Cloudflare Pages: drag-and-drop this folder; they will host the static site.
- Internal hosting: drop this folder under any IIS/NGINX/static server path.

Notes
-----
- The viewer uses the open-source Stoplight Elements web component (via CDN).
- Edit 'carrier-invoicing.yaml' in place to update the docs without changing links.