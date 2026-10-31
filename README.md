# IEM College Event Management Website

A responsive single-page academic demonstration built with **HTML5, CSS3 and vanilla JavaScript** for the IT Workshop project.

## Run locally
Open `index.html` in a browser, or use VS Code's Live Server extension. No installation or backend is required. Google Fonts require internet; fallback fonts work offline.

## Features
- Home with sticky navigation, mobile menu, next-event countdown and IST clock
- Six sample events rendered from a JavaScript array, with category filtering
- Student registration form with inline validation
- Six locally stored SVG event illustrations with CSS Grid and hover captions
- About and contact sections with feedback form
- Dark/light mode saved with localStorage
- Responsive layouts for desktop, tablet and mobile

## Important limitations
This is a **frontend-only demonstration**. Registration and feedback are saved in the browser's `localStorage` and are **not submitted to a server or visible to event organizers**. Do not use real personal information for testing. Browser data is device-specific and can be cleared. The event dates/venues are **sample data**, not official announcements. Coordinator details are placeholders. Replace these with verified information before submission. Do not publish real student registration details in the repository.

## GitHub Pages
1. Create a public GitHub repository (e.g. `college-event-management`).
2. Upload `index.html`, `css/`, `js/`, `images/`, `README.md` and `REPORT.md` at the repository root.
3. Commit changes.
4. Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
5. Once deployment finishes, visit `https://YOUR-USERNAME.github.io/college-event-management/` (replace the username and repository name).

## Folder structure
```
college-event-management/
  index.html
  css/style.css
  js/script.js
  images/*.svg
  screenshots/ (add your own screenshots)
  README.md
  REPORT.md
```
