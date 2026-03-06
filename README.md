# Web Scraper Lite

A Chrome extension for extracting structured data from any webpage. Point at elements, click to select, preview results, and export to CSV or JSON. No coding required.

Built on Manifest V3. Works entirely in your browser with zero data collection.


WHAT IT DOES

- Visual point-and-click element selector that highlights elements as you hover
- Extracts text, links, images, and tables from any website
- Custom CSS selectors for advanced targeting
- Side panel interface for configuring scrapers and previewing results
- Export extracted data to CSV or JSON
- Save scraper templates for reuse across sessions
- Scrape history with quick access to recent extractions
- Free tier with monthly row limits, Pro tier with unlimited access


HOW TO USE

1. Click the extension icon on any webpage
2. Use the visual selector to pick elements, or write a CSS selector manually
3. Preview extracted data in the side panel
4. Export to CSV or JSON, or copy to clipboard


PERMISSIONS

| Permission | Reason |
|------------|--------|
| activeTab | Interact with the current tab to highlight and extract elements |
| storage | Save templates, preferences, and scrape history locally |
| scripting | Inject the element selector overlay onto web pages |
| sidePanel | Power the side panel where you configure and preview scrapes |
| Host permissions (all URLs) | Allow scraping on any website you choose |


PRIVACY

Web Scraper Lite collects zero user data. All extraction, templates, history, and analytics stay on your device using Chrome's local storage API. Nothing is transmitted to external servers.

The only network call is license verification for Pro users, handled through Zovo. That sends your license key, extension ID, and a session ID for fraud prevention. No scraped content, URLs, or browsing data ever leaves your browser.

Full details in PRIVACY.md and privacy-policy.html.


INSTALL

From the Chrome Web Store (link coming soon), or load from source:

1. Clone this repository
2. Open chrome://extensions in Chrome
3. Enable Developer mode
4. Click Load unpacked and select the extension folder


PRO UPGRADE

Pro removes the monthly row limit and unlocks unlimited scraping. Managed through Zovo at zovo.one with secure payment processing. License status is cached locally and verified roughly once per hour.


CONTRIBUTING

Contributions welcome. See CONTRIBUTING.md for guidelines, development setup, and coding standards.

Report bugs or request features on GitHub Issues:
https://github.com/theluckystrike/web-scraper-lite/issues


LICENSE

MIT License, Copyright (c) 2025 theluckystrike. See LICENSE for full text.


---

Web Scraper Lite is a zovo.one project.
https://zovo.one
