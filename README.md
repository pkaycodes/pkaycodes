# Papakwame Afrifa Mensa

I build full-stack web applications, local-first products and small developer
tools in Accra, Ghana — and run [Mejo Labs](https://pkaycodes.github.io/mejo-labs/),
a software studio for businesses that need useful internal systems. Django or
Node on the server, React or plain HTML/CSS on the client, with PostgreSQL,
SQLite and Cloudflare underneath. I like systems that keep working when the
network does not.

## Featured work

### [Adom Hospital HMS — the whole clinic, in one system](https://github.com/pkaycodes/adom-hospital-hms)

A hospital management system for Ghanaian clinics and small hospitals. Reception
opens a visit, nursing records vitals, the doctor consults and orders tests or
drugs, the lab posts results, the pharmacy dispenses, and the cashier takes cash
or Mobile Money — with NHIS fields, role-based permissions, invoices, receipts,
low-stock alerts and an audit trail. The server is Express + SQLite, the client
is React + TypeScript, and the same API also runs as a Cloudflare Worker on D1.

`Node.js` · `Express` · `React` · `TypeScript` · `SQLite` · `Cloudflare D1`

### [PKLink — anything you want to share, one scan away](https://github.com/pkaycodes/pklink) · [Live site](https://site-1e61daf990414aa78567f4776a59d442.freebuff.page/)

A QR page builder for messages, photo galleries, video, documents and links.
Publish to a live `/p/<slug>` page in one click, choose public, unlisted,
password or private access, style the QR code with your own colours and logo,
then download it as PNG or SVG. Guests can start without an account; signed-in
users keep their pages across devices and see scans, unique visitors, devices
and countries. Built on Next.js 16, Cloudflare D1 and R2, with access checks
enforced on the server.

`Next.js 16` · `React 19` · `TypeScript` · `Tailwind CSS 4` · `Cloudflare Workers` · `D1` · `R2`

### [Edgebook — a private P&L journal for traders](https://github.com/pkaycodes/edgebook)

A trading journal for crypto, stocks and forex. Log trades by hand in one
ledger, then read back net P&L, win rate, profit factor, expectancy, payoff,
drawdown, streaks, hold times, weekday edge and strategy or symbol breakdowns.
The dashboard covers 7D through all-time, accounts persist in SQLite, and a
one-click demo opens 49 deterministic sample trades. No exchange connections or
API keys.

`React 19` · `TypeScript` · `Vite` · `Express 5` · `node:sqlite`

### [Efie — find a place that feels like home](https://github.com/pkaycodes/efie) · [Live site](https://pkaycodes.github.io/efie/)

A rental marketplace for Ghana. Landlords post houses, apartments, hostels,
single rooms and short stays; renters search by area, type, price, bedrooms and
furnishing, see the rent and deposit up front, and contact the landlord directly
on WhatsApp or by phone. Saved homes persist in the browser, photos are
compressed before upload, and Supabase can power shared listings when a backend
is configured.

`React 19` · `TypeScript` · `Vite` · `Supabase` · `GitHub Pages`

### [Sharkbook — private lending, properly recorded](https://github.com/pkaycodes/sharkbook) · [Live demo](https://pkaycodes.github.io/sharkbook/?demo=1)

An offline-first ledger for private lenders. Borrowers and facilities, flat and
reducing-balance schedules calculated to the pesewa, part payments, balances and
receivables aging all reconcile to the same book. Every agreement and numbered
receipt prints as a clean A4 document. The 39-test suite covers money and date
parsing, schedules, statuses, aging, browser storage, onboarding and the payment
journey.

`React 19` · `TypeScript` · `Vite` · `PWA` · `Vitest`

### [Sukuu — school fees, clearly](https://github.com/pkaycodes/sukuu) · [Live demo](https://pkaycodes.github.io/sukuu/?demo=1)

A calm fee book for small schools. Set up terms and classes, bill students,
record part payments and print receipts, with per-student discounts and
historical billing snapshots so changing a fee today never rewrites last term's
books. It runs from the browser, installs as a PWA and keeps working offline. No
account, server or subscription.

`React 19` · `TypeScript` · `Vite` · `PWA` · `Vitest`

### [Kae — the small shop's memory](https://github.com/pkaycodes/kae) · [Live demo](https://pkaycodes.github.io/kae/?demo=1)

An offline-first credit ledger for small shops, built as a React 19 + TypeScript
PWA. Shopkeepers record credit and part payments, see who owes what, send
WhatsApp reminders and export statements or a JSON backup. No account, server or
network required; the demo opens a sample shop and saves everything on the
device. Tested with Vitest and deployed to GitHub Pages from CI.

`React` · `TypeScript` · `PWA` · `Vite` · `Vitest`

### [Same Page — different desires, shared understanding](https://github.com/pkaycodes/same-page)

A working, responsive dating beta built around intentions instead of a public
photo feed. Verified phone numbers, server-enforced eligibility gates,
text-only conversations, privacy controls that change the query, and a
compatibility score whose weights and reasons are visible. The app and its
tests are public; commercial proposals, wireframes and vendor records stay
private.

`Next.js 16` · `PostgreSQL` · `TypeScript` · `Product design`

### [Mejo Labs — any system, built for your business](https://github.com/pkaycodes/mejo-labs) · [Live site](https://pkaycodes.github.io/mejo-labs/)

The online home of my software studio in Accra. A typographic, dependency-free
static site for custom software, internal systems and IT solutions, with real
project links, direct contact routes, structured data and a custom 404. No
framework, build step, tracker or third-party runtime script.

`HTML` · `CSS` · `JavaScript` · `GitHub Pages`

### [Shipcheck — does your repository look ready to ship?](https://github.com/pkaycodes/shipcheck)

A zero-dependency Node CLI and GitHub Action that audits the things a stranger
sees first: README, license, tests, CI, hard-coded secrets, `.gitignore`,
environment hygiene, package metadata and lockfiles. It returns a weighted
score, a letter grade and specific next steps, with JSON output for automation.
Tested on Node 20, 22 and 24; the package is npm-ready and the action is usable
as `pkaycodes/shipcheck@v1`.

`Node.js` · `CLI` · `GitHub Actions` · `Security` · `Zero dependencies`

### [CTMS — College Tutorial Management System](https://github.com/pkaycodes/college-tutorial-management-system-thesis)

My final-year thesis: a Django application for tutorial scheduling, attendance,
student feedback with automatic sentiment tagging, complaints and lecturer
claims. Administrators, lecturers and students each get their own dashboard,
and claim eligibility is enforced on the server rather than in the interface.

`Python` · `Django` · `SQLite` · `Bootstrap`

### [UG CTMS API](https://github.com/pkaycodes/university-tutorial-claims-api)

The same domain rebuilt as a JSON API — Express, PostgreSQL and JWT — with the
role rules enforced server-side. Ships with the schema and a seed script that
populates every tutorial state, so a fresh clone runs in three commands.

`Node.js` · `Express` · `PostgreSQL` · `JWT`

### [SikaPOS](https://github.com/pkaycodes/sikapos)

A point-of-sale system for Ghanaian shops: till sales, live stock with low-stock
alerts, customer credit ("owing") tracking, expenses and profit reports. One
folder, one database file, no internet required.

`Python` · `Django` · `SQLite`

### [SwiftGrab](https://github.com/pkaycodes/swiftgrab)

A zero-dependency Node web app that turns a pasted video or image link into a
download. Native extractors for X, TikTok, Facebook, Instagram, Reddit, Vimeo,
Pinterest and others, with yt-dlp as an optional self-installed fallback and HLS
assembled natively. Pinterest image pins, TikTok photo posts, Instagram photos
and mixed carousels, direct image URLs and og:image pages all use the same
download queue as video.

`Node.js` · `HTTP` · `HLS`

## More work

- **[MotorVault](https://github.com/pkaycodes/motorvault)** · [Live preview](https://pkaycodes.github.io/motorvault/) — a car rental marketplace prototype for Ghana, with date-aware search, a full booking flow and a host listing flow. `HTML` · `CSS` · `JavaScript`
- **[Tiptoes Ghana](https://github.com/pkaycodes/tiptoes-ghana)** · [Live site](https://pkaycodes.github.io/tiptoes-ghana/) — an editorial storefront for a personal shopper, with a small Node server that syncs a live Instagram feed.
- **[AM Homecare & Nursing Home](https://github.com/pkaycodes/am-homecare)** · [Live site](https://pkaycodes.github.io/am-homecare/) — a one-page site for home care and nursing services in Ofankor, Accra.
- **Gambler's Friend** — a private betting ledger with cross-device sync and Coach Solo, an in-app analyst that reads the book without giving tips. Currently in private beta.

## Coursework

- **[C# coursework](https://github.com/pkaycodes/csharp-coursework)** —
  console exercises in generics, interfaces, records and JSON persistence
  (DCIT 308 and DCIT 318, 2025).

## Tools

Python · Django · Node.js · Express · PostgreSQL · SQLite · React · TypeScript ·
JavaScript · Vite · Vitest · Tailwind CSS · Cloudflare Workers · D1 · R2 ·
HTML/CSS · GitHub Actions · Git

Accra, Ghana
