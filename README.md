## Matvey Klimanskiy

Full-stack developer based in Nha Trang, Vietnam. Right now I do two things: rebuild outdated
websites for small businesses, and build products of my own.

**Site with screenshots and details: [klimanskiy1.github.io](https://klimanskiy1.github.io/)**

### Website rebuilds

I take a business's existing site — WordPress, Wix, a page builder from 2012 —
keep every page, price, course and photo, and rebuild it as a fast static site:
one CSS file, dark mode, works on a 360 px phone, deploys to any host. Each site
gets a small Python generator, so content lives as data and the pages are written
by code. Nothing gets invented: the design changes, the facts do not.

| Site | What it is | Scale |
| --- | --- | --- |
| **[Rainbow Divers Vietnam](https://klimanskiy1.github.io/rainbow-divers-vietnam/)** | PADI dive centre since 1996, rebuilt from divevietnam.com | 35 pages · 4 languages · 123 photos |
| **[Sailing Club Divers](https://klimanskiy1.github.io/sailingclubdivers-preview/)** | WordPress → static, ocean theme in light and dark | 5 languages · no tracking |
| **California Scuba Center** | Dive shop, school and travel, with the full shop catalogue | 1 277 products · 25 courses |
| **Ace Diving Miami** | Wix → static, dive map with a depth filter | 47 pages · 95 dive sites |
| **Squalo Divers** | Course catalogue with filters, rendered from one data file | 42 courses · 53 dive sites |

### Own products

| Project | What it is | Stack |
| --- | --- | --- |
| **WipeSquad** | Teammate matching and clan CRM for Rust: Steam-verified hours and bans, rooms sized for the server's group limit, a wipe calendar | Next.js · TypeScript · PostgreSQL · Redis · BullMQ |
| **MeToo** | Anonymous conversations between people feeling the same thing right now — closed rooms that vanish with the conversation | Expo · Fastify · Socket.IO · PostgreSQL |
| **[Tutor](https://github.com/klimanskiy1/Tutor)** | A personal Anki on the FSRS scheduler: load any test set as JSON, answer a few a day | FastAPI · SQLite |

### How I work

Spec before code: a product doc, a data model and a decision log that says what
was chosen, why, and what it costs. Rules that matter are enforced by a guard
linter and pre-commit hooks mirrored in CI, not by prose. Tests run against a
real database. Backups count only after an actual restore.

I use AI coding agents for a lot of the typing and treat their output like a
pull request from someone else: a scoped task, a separate security pass that
only reports findings, and my own eyes on the result before anything ships.

### Smaller things

| Project | What it is | Stack |
| --- | --- | --- |
| **[shortener-service](https://github.com/klimanskiy1/shortener-service)** | URL shortener with a Docker setup and an isolated test environment | FastAPI · PostgreSQL · Docker · Pytest |
| **[ReqPy CLI](https://github.com/klimanskiy1/htpy-cli-app)** | Terminal HTTP client — a lighter Postman for people who live in the shell | Python · Click · Requests |
| **[WardenV2](https://github.com/klimanskiy1/WardenV2)** | Watches Avito listings and pushes new ones to Telegram; Redis-backed dedup with a 2-day TTL | asyncio · Redis · aiogram |

### Stack

**Languages** — TypeScript, Python, Go
**Web** — Next.js, Fastify, FastAPI, Django, Gin, aiogram
**Data** — PostgreSQL, Redis, MySQL, Drizzle, SQLAlchemy
**Infra** — Docker, Linux, nginx, Git, GitHub Actions, Playwright

### Elsewhere

[Telegram](https://t.me/matew_1) · [Email](mailto:klimanskiymatvey@gmail.com) · [LinkedIn](https://www.linkedin.com/in/klimanskiy-m)
