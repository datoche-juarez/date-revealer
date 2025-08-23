# Date Revealer

A lightweight Chrome extension that adds clear posting dates and relative time badges to job listings.

## Features

- 📅 Extracts hidden `datePosted` data from job pages
- 🕒 Shows both absolute date/time and relative time (e.g. "Just posted", "3 hours ago", "2 months ago")
- 🎨 Color-coded badges that highlight how recent the posting is
- ⚡ Automatically reinserts the badge if the page re-renders

## Installation (Development Mode)

1. Clone or download this repo
2. Visit `chrome://extensions` in Chrome
3. Enable **Developer mode** (top right)
4. Click **Load unpacked**
5. Select the project folder

The extension will now run automatically on supported job pages.

## Supported Sites

- ✅ **Indeed.com** job listing pages (opened in their own tab)
- ❌ Not supported on multi-listing search result sidebars (those previews don’t include structured `datePosted` data)

💡 To use the extension, right-click a job listing and open it in a new tab.

## Coming Soon

- Options page for customizing colors or relative time format
- Dark mode improvements
- Support for additional job boards
- Firefox support

## Disclaimer

This extension is an independent project and is **not affiliated with, endorsed by, or sponsored by any job site**.

## License

MIT
