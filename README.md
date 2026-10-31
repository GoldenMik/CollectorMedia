CollectorMedia — Browser Extension & Automated Licensing Ecosystem

CollectorMedia is a full-stack media scraping solution consisting of a Manifest V3 browser extension and an automated Telegram payment bot. It is designed to detect, preview, and bulk-download high-resolution media from modern SPA/Next.js websites and stock platforms.

Core Functionality

Smart Media Scraping: Automatically extracts high-resolution images and direct video streams (.mp4, .m3u8) while filtering out UI clutter, avatars, and banners.

Interactive Dark-Mode Gallery: Features a responsive overlay with keyboard navigation and an integrated Plyr media player for seamless previewing.

Batch Downloading & In-Memory ZIP: Supports one-click bulk downloading and packages media collections directly into ZIP archives using JSZip in the browser memory.

Multi-Tier Access System: Includes built-in logic for Free (up to 20 files), Amateur (bulk downloads), and PRO (ZIP archiving & unlimited access) user tiers.

Autonomous Cryptographic Licensing: Uses a custom hash-signature verification algorithm (SECRET_SALT) to validate license keys offline inside the extension without requiring an external database server.

Telegram Store Bot: A Python-based (pyTelegramBotAPI) automated store that processes payments via Telegram Stars and CryptoBot (USDT), instantly generating and delivering mathematically signed license keys to buyers.

Project Status
Please note that the codebase is currently in an early/raw state (MVP), meaning the code structure has room for refactoring and UI/UX polishing. However, it is fully functional, stable, and performs at a solid, reliable level in real-world scenarios. All core mechanics—from DOM parsing and ZIP generation to payment processing and key validation—work out of the box.

Tech Stack

Extension: JavaScript (ES6+), Manifest V3, Chrome Storage & Downloads API, Plyr.js, JSZip.

Backend Bot: Python 3, pyTelegramBotAPI (TeleBot), CryptoPay API, Telegram Stars API.

Purchase Full Source Code
This complete project (unobfuscated browser extension source code + Telegram payment & keygen bot) is available for purchase for $150.

Buying this repository gives you a ready-to-monetize SaaS product that you can rebrand, customize, or deploy immediately. To purchase the full source code and rights, please reach out via Telegram: https://t.me/Lilumakim
