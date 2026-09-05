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
| macOS | 14+, Apple Silicon (arm64) | [MacFullStack-1.1.7-arm64.dmg](../../releases/download/v1.1.7/MacFullStack-1.1.7-arm64.dmg) |

**Free tier:** one PHP project + core services (MySQL/MariaDB, Redis, Mailpit, phpMyAdmin) — no card required.

**Pro / Teams:** unlimited projects, Project Studio, FTP/Deploy, Next.js/Django/Python, Share, Postgres, and more — activate in **Settings → License** after purchase at [macfullstack.com/pricing](https://macfullstack.com/pricing).

---

## Highlights

- **Native runtime** — PHP 8.0–8.5, nginx, HTTPS via mkcert; Docker mode optional
- **Any CMS** — auto docroot detection and nginx rewrites (Laravel, WordPress, Bitrix, legacy PHP)
- **Custom domains** — `.localhost`, custom zones, aliases, wildcards
- **Dev tools in-app** — Mailpit, SQL console, Doctor, ⌘K palette, MCP for Cursor
- **Project Studio (Pro)** — editor, split view, Git dock, logs, terminal, `.env`
- **FTP Manager & Deploy Profiles (Pro)** — sync to shared hosting with a guided checklist

---

## What's new in 1.1.7

- **Project Studio (Pro)** — Quick Open, project search, split editor, pinned tabs, breadcrumbs, detached window
- **Git dock** — stage / unstage / discard, commit, amend, push / fetch / pull (`--ff-only`), ahead/behind, colored diff
- **MCP for Cursor** — local `macstack mcp` tools for projects, stack control, Doctor, logs, safe `db_ping` (`SELECT 1` only)

Full notes: [RELEASE_NOTES_v1.1.7.md](./RELEASE_NOTES_v1.1.7.md) · [changelog](https://macfullstack.com/changelog#2026-09-app-1-1-7)

---

## Requirements

- macOS **14** or later
- **Apple Silicon** (M1/M2/M3/M4)
- ~2 GB free disk space for the app + runtimes (varies with enabled services)

---

## Verify download (optional)

SHA-256 of `MacFullStack-1.1.7-arm64.dmg`:

```
da81f48768c1a4f252a8a13cde08c0f565011cbccd4c4b20ebc1811d6ca5115c
```

```bash
shasum -a 256 MacFullStack-1.1.7-arm64.dmg
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
