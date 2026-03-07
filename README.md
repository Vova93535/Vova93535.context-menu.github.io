# Chat room on GitHub Pages

A simple online chat that works entirely on the client side (HTML, CSS, JavaScript). Messages are stored in the browser's local storage and are synchronized between tabs within the same browser. The project is created to demonstrate the basic capabilities of web development and the publishing of static sites on GitHub Pages.

## Functionality

- Entering a username before starting a conversation.
- Sending text messages.
- Automatically scrolling to the latest message.
- Messages are saved in `localStorage`, so they don't disappear after the page is reloaded.
- Synchronization between tabs in the same browser (via `BroadcastChannel`).

> ⚠️ **Important:** This chat doesn't use a backend, so messages are only visible within the same browser. A backend (such as Firebase or Supabase) is required for multiplayer mode.

## Technologies

- **HTML5** - page structure.
- **CSS3** — interface styling (responsive design, built-in styles without external dependencies).
- **JavaScript (ES6)** — chat logic, working with `localStorage`, `BroadcastChannel` for tab synchronization.
- **Git & GitHub** — code hosting and publishing via GitHub Pages.
