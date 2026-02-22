# Urlyth: Contextual Web Memory

**Stay Lithe. Remember URLs.**

Urlyth is a local-first browser extension that provides a context-aware sidebar for pinning notes, voice memos, and snapshots directly to the websites you visit. Instead of managing a disconnected notebook, Urlyth anchors your data to the relevant URL, surfacing your thoughts exactly when you need them.

![Urlyth Cover](https://urlyth.com/img/urlyth-cover.webp)

## 🚀 Key Features

- **Anchored Data:** Notes are automatically filtered by the current URL or domain. Your thoughts stay where they belong.
- **Lithe Voice Memos:** Record audio thoughts instantly to capture context without stopping to type.
- **Site Snaps:** Take visual bookmarks (screenshots) of the current tab and pin them alongside your notes.
- **Local-First & Private:** Urlyth is serverless. All data is stored locally in your browser and never leaves your machine.
- **Scoping:** Toggle between "This Page," "Whole Site," and "Everything" to control how much data you see.
- **Data Portability:** Built-in JSON Import/Export tools for manual backups and migration.

## 🛠 Installation

1. Download the extension from the [Chrome Web Store](https://chromewebstore.google.com/detail/urlyth/hohhodojpmnjolihlhklkeleiaelajne).
2. Pin the Urlyth icon to your browser toolbar.
3. Open the side panel on any website to start pinning data.

## 📖 How it Works

Urlyth utilizes the `chrome.storage.local` API to store data. When you navigate to a website, the extension detects the `window.location.href` and filters the stored items to show only those matching the current "Scope."

### Scopes:
- **This Page:** Matches the exact URL.
- **Whole Site:** Matches the domain (e.g., all pages on `github.com`).
- **Everything:** A global view of all saved items.

## 🔒 Privacy

Your privacy is paramount.
- **No Analytics:** We do not track your browsing habits.
- **No Servers:** There is no back-end database; your data is yours.
- **No Cloud:** Syncing is not currently supported to ensure data remains strictly local.

## 📄 License

Copyright © 2026 [Weblaro](https://weblaro.com). All rights reserved.

---
Built with ❤️ for professional workflows.
