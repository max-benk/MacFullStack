# MacFullStack

**Local PHP/Laravel/CMS stack for macOS — Native by default, Docker when you need it.**

MacFullStack is a native macOS app (Apple Silicon) that runs PHP, nginx, MySQL/MariaDB, Redis, Mailpit, and more — without wiring Homebrew, Docker Desktop, and ten browser tabs on every new Mac.

- **Website:** [macfullstack.com](https://macfullstack.com)
- **Download:** [Latest release](../../releases/latest)
- **Changelog:** [macfullstack.com/changelog](https://macfullstack.com/changelog)
- **Docs:** [macfullstack.com/help](https://macfullstack.com/help)

> This repository hosts **installers and release notes only**. Source code is not published here.

---

## Download

| Platform | Requirement | File |
|----------|-------------|------|
| macOS | 14+, Apple Silicon (arm64) | [MacFullStack-1.1.6-arm64.dmg](../../releases/download/v1.1.6/MacFullStack-1.1.6-arm64.dmg) |

**Free tier:** one PHP project + core services (MySQL/MariaDB, Redis, Mailpit, phpMyAdmin) — no card required.

**Pro / Teams:** unlimited projects, Project Studio, FTP/Deploy, Next.js/Django/Python, Share, Postgres, and more — activate in **Settings → License** after purchase at [macfullstack.com/pricing](https://macfullstack.com/pricing).

---

## Highlights

- **Native runtime** — PHP 8.0–8.5, nginx, HTTPS via mkcert; Docker mode optional
- **Any CMS** — auto docroot detection and nginx rewrites (Laravel, WordPress, Bitrix, legacy PHP)
- **Custom domains** — `.localhost`, custom zones, aliases, wildcards
- **Dev tools in-app** — Mailpit, SQL console, Doctor, ⌘K palette, MCP for Cursor
- **Project Studio (Pro)** — file tree, tabbed editor, logs, terminal, `.env` dock
- **FTP Manager & Deploy Profiles (Pro)** — sync to shared hosting with a guided checklist

---

## What's new in 1.1.6

- **Project Studio (Pro)** — sidebar workspace: file tree, syntax-highlighted editor, line numbers, find/replace, go-to-line, bottom dock (logs / terminal / `.env`)
- Compact Studio toolbar aligned with SQL console and Terminal
- Cursor position and open tabs persist between sessions
- UI in Russian, English, and German

Full notes: [changelog #2026-08-app-1-1-6](https://macfullstack.com/changelog#2026-08-app-1-1-6)

---

## Requirements

- macOS **14** or later
- **Apple Silicon** (M1/M2/M3/M4)
- ~2 GB free disk space for the app + runtimes (varies with enabled services)

---

## Verify download (optional)

SHA-256 of `MacFullStack-1.1.6-arm64.dmg`:

```
cc6f90abc4750463d48db0a4f30926ae158a6fffd5637678ebbab4a02275f1dc
```

```bash
shasum -a 256 MacFullStack-1.1.6-arm64.dmg
```

---

## Support

- Help: [macfullstack.com/help](https://macfullstack.com/help)
- Forum: [macfullstack.com/forum](https://macfullstack.com/forum)
- Contact: [macfullstack.com/contact](https://macfullstack.com/contact)

---

## License

MacFullStack is proprietary software. Installers are provided for download; redistribution is not permitted except as stated in the [EULA](https://macfullstack.com/terms).

Made by [MAX:BENK](https://maxbenk.ru) · Product site [macfullstack.com](https://macfullstack.com)
