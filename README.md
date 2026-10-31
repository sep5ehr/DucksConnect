# DucksConnect

**DucksConnect** is an advanced, high-performance Cloudflare Worker-based VLESS/Trojan multi-user proxy panel combined with robust outbound routing and backup relay support.

## Features
- **Multi-User Management**: Built on Cloudflare D1 (SQLite) database with individual user subscription links and traffic monitoring.
- **Enhanced Outbound Routing & Proxy Relay**: Pre-configured with reliable backup relays (Warp/Cloudflare endpoints) to ensure 100% accessibility on sensitive websites (e.g., `check-host.net`, Google, and major CDNs).
- **Telegram Bot Integration**: Manage users, stats, and settings directly via Telegram.
- **Stealth & Kill Switch**: Advanced routing controls and security modes.

## Deployment
1. Create a Cloudflare Worker.
2. Bind a Cloudflare D1 database named `ducks-db`.
3. Paste the contents of `ducksconnect.js` into your worker.
4. Set up your environment variables or access the admin panel.
