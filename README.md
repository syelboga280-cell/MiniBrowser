# MiniBrowser

A lightweight, simulated web browser interface built with pure **HTML, CSS, and Vanilla JavaScript** in a single `index.html` file—no frameworks, build tools, or dependencies required.

## ✨ Features

- **Multi-Tab Support:** Open, switch, and close tabs dynamically.
- **Navigation Controls:** Working Back, Forward, Reload, Home, and smart Omnibox (URL + search detection).
- **Bookmarks Bar:** Star/unstar pages and access them from the toolbar (saved in `localStorage`).
- **Built-in Internal Pages:**
  - `browser://home` — Start page with search bar and quick shortcuts.
  - `browser://notes` — Persistent scratchpad saved automatically to `localStorage`.
  - `browser://history` — View and clear your recent browsing history.
- **Dark & Light Mode:** Toggle themes with persistent preference saving.

## 🚀 How to Run

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.

*(Or host it directly via GitHub Pages!)*

## ⚠️ Note on External Websites

MiniBrowser loads external websites inside an `<iframe>`. Because many major sites (like Google or YouTube) enforce `X-Frame-Options` or Content Security Policy (`CSP`) headers for security, they cannot be embedded inside frames. A quick **"Open in real tab ↗"** link is included in the viewport bar for those sites.

## 🛠️ Built With

- HTML5
- CSS3 (CSS Variables for theming)
- Vanilla JavaScript (`localStorage` API)