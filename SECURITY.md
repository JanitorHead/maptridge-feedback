# Security

If you find a security problem in Maptridge, please report it privately through [GitHub's private vulnerability reporting](https://github.com/JanitorHead/maptridge-feedback/security/advisories/new) instead of opening a public issue. I'll reply as soon as I can and fix it.

## How Maptridge handles your data

- There are no accounts, no sign-up, no cookies and no analytics.
- Your map, notes and passwords stay in your browser, or in the files you save yourself.
- The only thing that leaves your browser is your RetroAchievements username, and only if you link it. A small server function passes it on to RetroAchievements to read your public progress, keeps the answer for 30 seconds and stores nothing else. It exists so the API key stays on the server and never reaches the page.
- The site sends a Content-Security-Policy: the browser runs only Maptridge's own scripts and loads images only from Maptridge and RetroAchievements.

## Worth reporting

- A way to run code or inject content into the page.
- A way to get the RetroAchievements API key, or to misuse the server function.
- Anything that sends your data somewhere it shouldn't go.
