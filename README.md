# CaseCraft demo

## Run
Open `index.html` in a browser, or upload it to a GitHub repository and enable GitHub Pages.

## Features
- Responsive Create / Emails / Notes / Server / About tabs
- Random letter-case variants (digits and punctuation unchanged)
- Copy one or all, TXT/CSV export
- Browser-local saved emails and notes using localStorage
- Demo profile UI

## Important limitations
- This is a static front-end demo. Login is NOT secure authentication; it only saves a demo username locally. Do not enter real passwords.
- No server, API, or temporary mailbox is included. A real login requires a backend with password hashing, sessions or secure tokens, HTTPS, rate limiting, and database storage.
- Email case variants do not create separate inboxes. Most email providers treat address case as equivalent.
- Data is stored in this browser and may be lost when site data is cleared.
