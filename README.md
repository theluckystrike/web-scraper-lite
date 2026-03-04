# Web Scraper Lite

[![Chrome Web Store](https://img.shields.io/badge/Chrome-Web%20Store-blue?logo=google-chrome)](https://chrome.google.com/webstore/detail/web-scraper-lite)
[![Version](https://img.shields.io/badge/version-1.0.10-green.svg)](https://github.com/theluckystrike/web-scraper-lite)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Discord](https://img.shields.io/badge/Discord-Zovo-blueviolet.svg?logo=discord)](https://discord.gg/zovo)
[![Website](https://img.shields.io/badge/Website-zovo.one-blue)](https://zovo.one)
[![GitHub Stars](https://img.shields.io/github/stars/theluckystrike/web-scraper-lite?style=social)](https://github.com/theluckystrike/web-scraper-lite)

> Extract data from any webpage with ease. Free & open source.

**Web Scraper Lite** is a Chrome extension that makes web scraping simple and accessible. Point, click, and extract — no coding required. Perfect for researchers, marketers, data analysts, and anyone who needs to extract structured data from websites.

## Features

- **Point-and-Click Element Selector** - Click on any element on a webpage to select it for extraction
- **Extract Text, Links, Images, and Tables** - Pull structured data from any website with ease
- **CSS Selector Support** - Advanced users can write custom CSS selectors for precise targeting
- **Export to CSV or JSON** - Download your extracted data in standard formats
- **Preview Results Before Exporting** - See exactly what you're getting before you download
- **Works on Any Website** - Compatible with all modern websites

## How It Works

1. Click the extension icon while on any webpage
2. Use the point-and-click selector to choose elements
3. Preview the extracted data
4. Export to CSV or JSON

## Permissions Explained

| Permission | Why |
|------------|-----|
| `activeTab` | Access page content to extract data from the current tab |
| `storage` | Save your custom selectors and preferences locally |
| `clipboardWrite` | Copy extracted data to clipboard for quick access |

## Privacy

**Web Scraper Lite collects zero data.**

- Does NOT send any data to external servers
- Does NOT track your browsing activity
- Does NOT collect analytics or telemetry
- All data extraction happens locally in your browser
- Your selectors and preferences are stored only on your device

See [PRIVACY.md](PRIVACY.md) for our complete privacy policy.

## Installation

Install from the [Chrome Web Store](https://chrome.google.com/webstore) or load unpacked from source:

1. Clone this repository
2. Open `chrome://extensions` in Chrome
3. Enable "Developer mode"
4. Click "Load unpacked" and select the extension folder

## Built by Zovo

Part of the [Zovo](https://zovo.one) developer tools family.

## License

MIT License - Copyright (c) 2026 Zovo

See [LICENSE](LICENSE) for full details.

## Support

- Report issues on [GitHub Issues](https://github.com/theluckystrike/web-scraper-lite/issues)
- Contact: support@zovo.one

## Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/my-feature`
3. **Make your changes** and commit them: `git commit -m 'Add new feature'`
4. **Push to the branch**: `git push origin feature/my-feature`
5. **Open a Pull Request**

### Development Setup

```bash
# Clone the repository
git clone https://github.com/theluckystrike/web-scraper-lite.git
cd web-scraper-lite

# Install dependencies
npm install

# Build the extension
npm run build

# Load in Chrome
# Open chrome://extensions → Enable Developer Mode → Load unpacked
```

### Coding Standards

- Use ESLint for JavaScript linting
- Follow existing code style
- Write comments for complex logic
- Test your changes manually before submitting

## See Also

- [Zovo](https://zovo.one) - Developer tools and utilities
- [Awesome Chrome Extensions Dev](https://github.com/theluckystrike/awesome-chrome-extensions-dev) - Curated list of Chrome extension development resources
- [Chrome Extension Starter MV3](https://github.com/theluckystrike/chrome-extension-starter-mv3) - Production-ready Chrome extension template
- [WebeXT Utilities](https://github.com/theluckystrike?tab=repositories&q=webext) - Collection of WebExtension components

---

Made with care by the Zovo team.

Built by [Zovo](https://zovo.one)
