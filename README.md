# AI Path — complete website source

Your personal Python, SQL and AI engineering learning website.

## Included files
- index.html — page structure and navigation
- style.css — responsive design and dark theme
- app.js — lesson navigation, knowledge checks, progress, notes and backups
- content.json — all 36 lessons, worked examples, exercises, solutions and links

## Run on Windows
1. Extract this ZIP into a folder, such as Documents/ai-path.
2. Install Python 3 from https://www.python.org/downloads/ if needed.
3. Open the extracted folder in File Explorer. Click its address bar, type cmd and press Enter.
4. Run: py -m http.server 8000 --bind 127.0.0.1
5. Open http://localhost:8000 in your browser.
6. Keep the terminal open while studying. Press Ctrl+C in the terminal to stop.

On macOS/Linux, use: python3 -m http.server 8000 --bind 127.0.0.1

Do not simply double-click index.html: browsers may block loading content.json from a file URL. Use the local server above or VS Code Live Server.

## Edit the website
Open the folder in VS Code. Edit lesson text in content.json, layout in index.html, design in style.css and behavior in app.js. Keep JSON valid: preserve quotation marks, commas and square brackets. Reload the browser after changes.

## Hosting
This is a static website: no npm installation, build step, paid API key or backend is required. Upload these files together to a static host, with index.html at the site root. Access control on the ChatGPT-hosted version is provided by its hosting service, not this source code. Configure access separately if hosting elsewhere; static hosts may publish publicly by default.

## Progress and notes
Saved locally in the current browser, not synchronized between devices. Use the sidebar download button to export a JSON backup. Use Import backup in the footer to restore it. Localhost and the hosted site have separate storage: export from the hosted site and import on localhost to transfer your progress. Keep the same hostname/port for stable local storage.

## Learning code
The website does not execute Python or SQL. Run lesson examples in your own environment or use the linked practice tools. Install learning packages only as their lessons require. Architecture sketches and release checklists are labelled as non-executable.

## External resources
Tutorial links require internet. Google Fonts are optional; system fonts are used if unavailable. Course content is included directly in content.json.
