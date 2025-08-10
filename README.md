# Notion Calendar Restyle

A lightweight Chrome extension that injects CSS to make Notion Calendar cleaner and more consistent, inspired by Google Calendar’s visual cues.

## Features
- **Event color = ribbon color**: Sets every event’s background to its ribbon color so it matches how colors appear in Google Calendar.
- **Notion tasks styling**: Distinct styling per task type; completed tasks get a strikethrough and subdued color, mirroring Google Tasks behavior.
- **Past events dimming**: Events that have ended are automatically dimmed to reduce visual noise, similar to Google Calendar.

## Install
1. Download or clone this repository.
2. Open `chrome://extensions` in Chrome.
3. Enable Developer mode (top-right toggle).
4. Click "Load unpacked" and select the project folder.

## Use
- Open Notion Calendar at `https://calendar.notion.so` or `https://calendar.notion.com`.
- The styles apply automatically on page load. If you don’t see changes, hard refresh the page.

## Develop
- Edit styles in `styles/styles.css` and behaviors in `scripts/content/content.js`.
- After changes, click the refresh icon on the extension card in `chrome://extensions` and reload your Notion Calendar tab.
