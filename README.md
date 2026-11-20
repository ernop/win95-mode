# Win95 Mode

A local, single-file writing tool for producing precisely sized text screenshots. It uses a Windows 95 Notepad interface and works without a server, build step, account, or network connection.

(The Caddy-served copy with McPhee spelling integration lives in `mybrowser/utilities/caddy/site/win95-mode/` at `http://win95-mode.localhost`.)

## Features

- Edit text directly in the page.
- Use the browser's spelling dictionary, including **Add to dictionary** from the right-click menu.
- Find repeated spaces independently from spelling errors.
- Resize the frame from its lower-right corner; live dimensions remain in a separate bar at the bottom of the browser viewport.
- Hide editing controls and diagnostic marks without changing the frame's dimensions.
- Recover edits automatically from browser storage.

## Use

1. Download `index.html`.
2. Open it in a browser.
3. Replace the example text with your post.
4. Resize the frame to the required dimensions.
5. Press `F9` and take the screenshot.
6. Press `Escape` to return to editing.

Keyboard shortcuts:

- `F7` — toggle spelling
- `F8` — toggle repeated-space marks
- `F9` — toggle screenshot mode
- `Escape` — leave screenshot mode

All text remains in the browser on the local machine.
