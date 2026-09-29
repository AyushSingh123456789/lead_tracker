# Lead Tracker

A lightweight Chrome extension popup for saving and tracking leads (links). Type a URL, click **SAVE INPUT**, and it appears as a clickable list item that opens in a new tab.

## Files

| File         | Purpose                                  |
| ------------ | ---------------------------------------- |
| `index.html` | Popup markup: input, button, leads list  |
| `index.css`  | Styling (green `#5f9341` accent theme)   |
| `index.js`   | Saves input to `myLeads` and renders it  |
| `manifest.json` | Chrome extension manifest (v3)        |
| `icon.png`   | Extension icon                           |

## Features

- Save text/URLs with one click
- Input clears automatically after saving
- Each lead renders as a link opening in a new tab
- No dependencies — plain HTML, CSS, and JavaScript

## Usage

1. Open `index.html` in a browser (or load the folder as an unpacked Chrome extension via `chrome://extensions` → **Load unpacked**).
2. Enter a link (e.g. `http://google.com`).
3. Click **SAVE INPUT** — the lead is added to the list below.

> Note: leads are kept in memory only; they reset when the popup/page is closed.

## Development

No build step required. Edit the files and refresh the popup to see changes.
