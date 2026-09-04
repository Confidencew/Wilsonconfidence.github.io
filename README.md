# SnapAI

This is the complete SnapAI starter project.

## What is included
- `index.html` — website
- `style.css` — design
- `app.js` — button and AI connection
- `worker/worker.js` — secure server-side AI proxy

## Important
GitHub Pages can host the website files, but it does not run server-side code. Do NOT put an AI API key in `index.html` or `app.js`.

To make the button produce real AI answers, the worker must be deployed separately and given an `OPENAI_API_KEY` secret. Then replace `YOUR-WORKER-URL.workers.dev` in `app.js` with the worker URL.

GitHub Pages: https://docs.github.com/en/pages
