# Awesome-Calendar

# Top Calendar Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Scheduling, CalDAV Sync & Personal Information Management*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Calendar and Scheduling**. These tools manage personal and team calendars, event scheduling, meeting polls, and contact synchronization across devices and platforms.

**Examples** include Google Calendar, Microsoft Outlook Calendar, Fantastical, Cron Calendar, Morgen, Calendar.com, Teamup Calendar, Zoho Calendar, TimeTree, and Vimcal (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosting, CalDAV/CardDAV servers, and privacy-focused calendar clients — ideal for individuals and organizations seeking data sovereignty. The open-source ecosystem is exceptionally strong here, built on the open CalDAV standard, with production-grade sync servers and mature desktop/mobile clients available.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Google Calendar](https://calendar.google.com/)**  
  Free, ubiquitous calendar with excellent cross-platform sync, Gmail integration, and basic appointment scheduling. The default choice for most users .

- **[Microsoft Outlook Calendar](https://www.microsoft.com/microsoft-365/outlook/)**  
  Enterprise-standard calendar bundled with Microsoft 365. Strong for organizational scheduling, resource booking, and Teams integration. Copilot AI features require a Microsoft 365 subscription .

- **[Fantastical](https://flexibits.com/fantastical)**  
  Premium Apple-only calendar with best-in-class natural language event creation and multi-calendar overlay. Subscription-based ($57/year), with key features behind the paywall .

- **[Notion Calendar (formerly Cron)](https://www.notion.so/product/calendar)**  
  Developer-favorite calendar acquired by Notion in 2024. Clean interface with Notion workspace integration. No Android app .

- **[Morgen](https://www.morgen.so/)**  
  Calendar and scheduling tool with focus on time blocking and task integration.

- **[Calendar.com](https://www.calendar.com/)**  
  Modern calendar with scheduling links and team availability features.

- **[Teamup Calendar](https://www.teamup.com/)**  
  Shared calendar for teams and organizations with granular access permissions and no user accounts required for viewing.

- **[Zoho Calendar](https://www.zoho.com/calendar/)**  
  Calendar within the Zoho ecosystem with sharing and scheduling features.

- **[TimeTree](https://timetreeapp.com/)**  
  Shared calendar app popular for families and small groups.

- **[Vimcal](https://www.vimcal.com/)**  
  Keyboard-first calendar designed for power users and executive assistants.

## Open-Source GitHub Projects

- **[Radicale](https://github.com/Kozea/Radicale)**  
  Simple, lightweight CalDAV and CardDAV server written in Python. Extremely low administrative overhead, using standard `.ics` and `.vcf` files on disk for storage with no vendor lock-in. Supports multiple authentication backends (htpasswd, LDAP, remote user) and native Git-based versioning for audit trails. The de facto choice for personal and small-team privacy-first calendar hosting . GPL-3.0 licensed.

- **[Baïkal](https://github.com/sabre-io/Baikal)**  
  Lightweight CalDAV and CardDAV server built on the sabre/dav framework. PHP-based with a web admin interface, suitable for users who prefer PHP stacks over Python .

- **[SabreDAV](https://github.com/sabre-io/dav)**  
  Open source CardDAV, CalDAV, and WebDAV framework and server in PHP. The underlying framework powering Baïkal and Nextcloud's CalDAV implementation . MIT licensed.

- **[DAViCal](https://github.com/DAViCal/davical)**  
  CalDAV server for calendar sharing using PostgreSQL as the data store. Mature and battle-tested .

- **[Xandikos](https://github.com/jelmer/xandikos)**  
  CardDAV and CalDAV server with minimal administrative overhead, backed by a Git repository. Written in Python .

- **[AgenDAV](https://github.com/agendav/agendav)**  
  CalDAV web client with AJAX interface, similar to Google Calendar. Provides a browser-based calendar experience on top of a CalDAV backend .

- **[Fossify Calendar](https://github.com/FossifyOrg/Calendar)**  
  Community-maintained fork of Simple Mobile Tools Calendar. Lightweight Android calendar with no ads, analytics, or unnecessary permissions. Supports local storage, multiple calendars, and the standard Android event provider .

- **[DAVx⁵](https://github.com/bitfireAT/davx5-ose)**  
  The essential open-source CalDAV/CardDAV sync adapter for Android. Syncs with Android's system calendar storage, so any calendar app (Fossify, Etar, etc.) can read and write to it. Available free on F-Droid, paid on Play Store .

- **[GNOME Calendar](https://github.com/GNOME/gnome-calendar)**  
  Simple and beautiful calendar application designed for the GNOME desktop. Integrates with GNOME ecosystem and supports online calendars . GPL-3.0 licensed.

- **[KOrganizer](https://github.com/KDE/korganizer)**  
  KDE's calendar and scheduling component of Kontact. Manages events and tasks, alarm notification, web export, group scheduling, and import/export of calendar files. Works with NextCloud, Kolab, and various calendaring services .

- **[Merkuro Calendar](https://github.com/KDE/merkuro)**  
  Kirigami-based calendar and task management application from KDE. Supports local calendars, Nextcloud, Google Calendar, Outlook, CalDAV, and more .

- **[calrs](https://github.com/teicee/calrs)**  
  Fast, self-hostable scheduling platform written in Rust. Like Cal.com but with CalDAV pull-based sync for free/busy lookup and write-back for confirmed bookings. Features SQLite storage, email notifications with `.ics` invites, timezone-aware slot picker, team event types with round-robin, and OIDC/SSO authentication .

- **[Rallly](https://github.com/lukevella/rallly)**  
  Open-source group scheduling and meeting polls tool — a self-hosted Doodle alternative. Participants mark Yes/If need be/No without signup, with automatic timezone conversion and ICS invites on finalization .

- **[chroncal](https://github.com/douglasdemoura/chroncal)**  
  Terminal-based calendar application with interactive TUI and comprehensive CLI. Supports CalDAV account sync, recurring events (RRULE), todos, journal entries, iCal import/export, and free/busy computation .

- **[vdirsyncer](https://github.com/pimutils/vdirsyncer)**  
  Command-line tool for synchronizing calendars and addressbooks between various servers and the local filesystem. Essential for terminal-centric workflows .

### Additional Strong Open-Source Options

- **[Nextcloud Calendar](https://github.com/nextcloud/calendar)** — Full-featured calendar app within Nextcloud, using SabreDAV as backend. Provides web UI, sharing, and mobile sync .
- **[Calindori](https://invent.kde.org/plasma-mobile/calindori)** — Touch-friendly calendar application designed for mobile Linux devices .
- **[Karlender](https://github.com/dj-bolt/karlender)** — Adaptive calendar app for GNOME and Phosh .
- **[renCal](https://github.com/renCal/renCal)** — Modern, local-first desktop calendar application for Linux and macOS .
- **[SOGo](https://github.com/Alinto/sogo)** — Very fast and scalable groupware suite offering calendaring, address book, and ActiveSync with native Outlook compatibility .

**Frameworks for building custom calendar solutions**: Combine **Radicale** as a lightweight CalDAV backend with **Fossify Calendar** + **DAVx⁵** for Android clients and **GNOME Calendar** or **Merkuro** for Linux desktops . For team scheduling with booking pages, **calrs** provides CalDAV-native scheduling infrastructure . For group meeting coordination, **Rallly** offers Doodle-style polls . For terminal users, **chroncal** delivers full calendar management from the command line .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Calendar tools handle sensitive personal and organizational data. Self-hosted solutions require proper security hardening, SSL/TLS configuration, and backup procedures.
- CalDAV/CardDAV sync requires client configuration and may not support all proprietary features (e.g., Google Meet links, Microsoft Teams integration).

---

**Made for privacy-conscious users, self-hosters, and teams seeking calendar data sovereignty.**  
Let's make calendar and scheduling more open, transparent, and user-controlled.
