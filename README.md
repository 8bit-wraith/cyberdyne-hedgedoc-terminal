# 🕶️ CyberDyne HedgeDoc Terminal

> "All documents are now CyberDyne property."

This is a Coolify-ready Docker Compose setup for a fully-themed HedgeDoc markdown server — powered by 8B Systems and protected by CyberDyne Systems.

## Features

- 🌐 Keycloak OAuth2 Auth (via `id1.is`)
- 🖤 CRT-styled dark theme with scanlines, flicker, and neon UI
- 🧠 Ready for Coolify's smart domain injection
- 🔐 Secure by default with CSP + HSTS
- 📦 Easy volume storage for uploads and Postgres
- ⚡ Ready to connect to 5o/Precinct PXE nodes (future)

## Quick Start

```bash
git clone https://github.com/your-org/cyberdyne-hedgedoc-terminal.git
cd cyberdyne-hedgedoc-terminal
cp .env.example .env
# edit the .env file with your secrets

docker compose up -d
```

## License

MIT — Have fun. Stay secure. Stay weird. 🛡️
