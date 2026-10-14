# Lola's Morning Board
Static site (no build step). `index.html` holds the page; all daily content lives in the JSON block `<script id="board-data">`. Images are in `pins/` and `covers/`.
Host on GitHub Pages / Netlify / Cloudflare Pages. A scheduled Claude routine refreshes it daily (see ROUTINE_PROMPT.md).
