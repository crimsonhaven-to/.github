# crimsonhaven.to

# **!IMPORTANT!**

GitHub just recently took down the main developer's GitHub account. It likely is just a matter of time before this org also gets taken down. Therefore, check out the new repos:
[https://gitlab.ramon.moe/crimsonhaven-to](https://gitlab.ramon.moe/crimsonhaven-to)
Development will only continue there! The code here on GitHub is stale and not up-to-date anymore!
As of right now, we are still re-organizing everything, rebuilding CI/CD pipelines etc., but in due time everything will go back to normal.
(hopefully)


> *"Welcome to your digital domain, little mortal. Here, the network flows through blood-red links, and every manifestation is catalogued for your eternal amusement."*
> — **Luminas, the Vampire Queen**

---

## 🌹 The Sanctuary

We are not a corporation. We are a **System Engineer** (who might be a touch too arrogant :3) and architects of the unconventional.

**Crimson Haven** is an **expansive, performance-oriented streaming framework** for self-hosters — a metadata brain wrapped around a stateless, horizontally-scalable backend (scale it as far as your hardware dares). Think of it as your own private sanctuary, something like Jellyfin, but forged in the fires of crimson aesthetics and raw engineering.

We provide the throne; you provide the crown. Our tools bridge the gap between your personal media archives (NAS, Jellyfin, or local relics) and a seamless, high-fidelity viewing experience. No bloat, no trackers, just the pure essence of *your* collection. Since this began as an anime-centered project, our metadata engine is laid out for anime first: it natively maps **TMDB ↔ AniList** with per-season metadata, graceful TMDB fallback, and (now) full support for ordinary TV shows and movies. This is the developer's "perfection" given form.

---

## ❓ Why?

Why did I forge this? An interesting tale, truly. I've always admired projects like P-Stream (sudo-flix, movie-web, or whatever name it wears this week). Before this, I hadn't built anything on this scale in years — yet no project has brought me more joy to develop, test, and "mend" into my definition of perfection.

The technical challenge, getting to *use* my own creation, and being able to change anything that annoyed me on a whim — that was (and still is) a whole lot of fun. So I wish for more people to use it, build upon it, and expand it further, perhaps with ideas I'd never have dreamt of. To that end the entire framework is public and open-source: a neutral, capable vessel that ships with **no sources of its own** — what you (lawfully) pour into it is yours to decide.

---


## 🧛 Meet Lumi (Luminas) — Our Vampire Queen

> *"I’ve lived centuries, but I still blush at a good tsundere arc."*

**Lumi** (Full name: *Luminas Crimsonveil*) is the immortal, cute, and slightly mischievous vampire queen who watches over the Haven.

- **The Look** — A petite girl with pale skin, deep crimson eyes, and long crimson hair with violet undertones. Usually seen wrapped in a velvet cape, judging your 404 errors.
- **The Soul** — Regal but playful. She’ll mock your taste in generic isekai while secretly bookmarking them in her Royal Archives. She drinks `#8B0000` tea and performs moonlit code reviews.
- **The Decree** — *"Don’t worry, I only bite lag and broken subtitles. Your data belongs to you—I have no interest in mortal tracking."*

You’ll find Lumi haunting our UI elements, guiding lost souls in the forgotten corridors (404 pages), and occasionally leaving sarcastic remarks in the console logs.

![Lumi!](/assets/images/nobackgroundmascot.png)

---

## 🏰 The Crimson Ecosystem

The sanctuary is built from **five small halls** that work together — all public and open-source, for those brave enough to summon them. You can raise a working instance with just the first three.

### 🩸 [crimson-backend](https://gitlab.ramon.moe/crimsonhaven-to/crimson-backend) — the brain
A high-performance FastAPI engine that maps your metadata and orchestrates everything.
- **Mapping Intelligence:** Bridges TMDB ↔ AniList for complex multi-season clusters.
- **Operator-owned media:** Serves *your own* Local / Cache / Jellyfin sources — and scrapes nothing third-party.
- **NDJSON Streaming:** Pushes metadata and stream results to the client the instant they're found.

### 🍷 [crimson-client](https://gitlab.ramon.moe/crimsonhaven-to/crimson-client) — the face
A React 19 interface refined for speed and visual impact.
- **Cryptographic Identity:** Mnemonic-based (12-word seed) accounts — no passwords, just soul-binding — alongside optional invite-gated email + password.
- **Neon Crimson Theme:** A sleek, performance-optimized UI that feels like a *crimson* home.
- **The Royal Archives:** Favorites and History tracking, stored within your own castle.

### 🌐 [crimson-proxy](https://gitlab.ramon.moe/crimsonhaven-to/crimson-proxy) — the edge
A signed, HLS-aware CORS relay on free edge hosting (Netlify / Cloudflare) that carries heavy video bytes so your own server never has to.

### 🦇 [crimson-extension](https://gitlab.ramon.moe/crimsonhaven-to/crimson-extension) — the familiar
An optional, tiny browser companion that unlocks the smoothest, most direct playback (CDN → viewer).

### 📖 [crimson-docs](https://gitlab.ramon.moe/crimsonhaven-to/crimson-docs) — the grimoire
The full self-hosting documentation — Lumi will guide you personally through every hall.

> **And your sources — the secret.** The public stack ships with **no** streaming providers. The actual sources live in *your own private repository*, bundled in at build time. That's the whole design: the public halls stay shareable; the part that finds streams stays yours.

---

## 🛠 Forged With

Our artifacts are forged using the finest mortal and immortal technologies:

- **Frontend:** [React 19](https://react.dev/) + [Vite 8](https://vite.dev/) + [Tailwind CSS 4.0](https://tailwindcss.com/)
- **Backend:** [Python](https://www.python.org/) + [FastAPI](https://fastapi.tiangolo.com/) + [PostgreSQL](https://www.postgresql.org/)
- **Security:** Ed25519 Cryptography + BIP39 Mnemonics
- **Infrastructure:** [Docker Swarm](https://docs.docker.com/engine/swarm/) & [Docker Stack](https://docs.docker.com/engine/reference/commandline/stack/) (For high-availability empires) or simply Docker Compose for simple setups!

---

## ⚖️ The Queen's Decree (Disclaimer)

*Hearken, mortals, to the laws of the realm. Crimson Haven is an expansive, performance-oriented **streaming framework** and metadata engine — a neutral vessel, a hollowed sarcophagus waiting to be filled with your own chosen manifestations. We do **not** host, store, embed, ship, or pre-load any sources, playlists, or streams, and we do **not** condone piracy.*

*The framework exists solely to let you add your **own** sources — legally acquired streams, public-domain content, or media you have explicit permission to access, such as a personal Jellyfin instance or a NAS.*

*We do not condone, encourage, or facilitate any form of copyright infringement. You, the mortal, are solely responsible for ensuring your sources are lawful and for complying with all applicable laws (including the Swiss URG).*

---

## 🕸️ Follow the Queen

- **Organization:** [@crimsonhaven-to](https://github.com/crimsonhaven-to)
- **Instagram:** [@crimsonhaven.to](https://www.instagram.com/crimsonhaven.to)
- **Reddit:** [r/crimsonhaven](https://www.reddit.com/r/crimsonhaven)
- **TikTok:** [@crimsonhaven.to](https://www.tiktok.com/@crimsonhaven.to)

> *"One day, you’ll open your browser, and your own private haven will be waiting—in crimson splendor."*  
> — **Luminas Crimsonveil**
