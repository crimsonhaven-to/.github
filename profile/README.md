# crimsonhaven.to

> *"Welcome to your digital domain, little mortal. Here, the network flows through blood-red links, and every manifestation is catalogued for your eternal amusement."*
> — **Luminas, the Vampire Queen**

---

## 🌹 The Sanctuary

We are not a corporation. We are a **System Engineer** (who might be a bit too arrogant :3) and architects of the unconventional. 

**Crimson Haven** has evolved. What began as a "legally-dubios, sketchy" webpage and then became an extension has returned to its origins, but without the sketchyness. It has returned into a full-scale, neutral watching framework for self-hosters with a stateless backend (which is pretty much horizontally scalable as much as your hardware can handle). Think of it as your own private sanctuary, something like Jellyfin, but forged in the fires of crimson aesthetics and raw engineering.

We provide the throne; you provide the crown. Our tools are designed to bridge the gap between your personal media archives (NAS, Jellyfin, or local relics) and a seamless, high-fidelity viewing experience. No bloat, no trackers, just the pure essence of your collection. Since this originally began as an anime-centered project, our metadata engine is specifically laid out for anime. With per-season metadata, fallback to TMDBs metadata and (now) support for normal TV shows, this is the developer's "perfection" given form.

---

## ❓ Why?

Why did I create this? Well, that answer is quite interesting, truly. I've always been a fan of projects like P-Stream (sudo-flix, movie-web or whatever other name it might have). Before starting this project, I hadn't built anything on this scale for years. But funnily enough, this project has brought me more joy to develop, test, and "mend" into my definition of perfection than any other project I worked on so far. 

The technical challenge, getting to use my own product and, if something annoyed me, simply being able to change it, truly was (and still is) a whole lot of fun. Therefore, I wish that more people get to use this, build upon this project and expand it even further, perhaps bringing ideas which I couldn't have even thought about so far. Since my private version of this project is... well... *not suitable for sharing for certain reasons*, I stripped out all the *problematic* code. 

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

The sanctuary is built upon two mighty pillars, both open to the public for those brave enough to summon them:

### 🩸 [Crimson Backend](https://github.com/crimsonhaven-to/crimson-backend-public)
The heart of the Haven. A high-performance FastAPI engine that manages your personal media collection with elegance.
- **Mapping Intelligence:** Bridges TMDB and AniList for complex multi-season clusters.
- **Jellyfin Integration:** Seamlessly syncs with your existing home sanctuary.
- **NDJSON Streaming:** Pushes metadata and stream results to the client the instant they are found.

### 🍷 [Crimson Client](https://github.com/crimsonhaven-to/crimson-client-public)
The veil through which you view your domain. A React-based interface refined for speed and visual impact.
- **Cryptographic Identity:** Secure, mnemonic-based (12-word seed) account system. No passwords, just pure soul-binding. (If authentication is enabled, it is still email and password- for now.)
- **Neon Crimson Theme:** A sleek, performance-optimized UI that feels like home—a *crimson* home.
- **The Royal Archives:** Comprehensive tracking for your Favorites and History, stored within your own castle.

---

## 🛠 Forged With

Our artifacts are forged using the finest mortal and immortal technologies:

- **Frontend:** [React 19](https://react.dev/) + [Vite 8](https://vite.dev/) + [Tailwind CSS 4.0](https://tailwindcss.com/)
- **Backend:** [Python](https://www.python.org/) + [FastAPI](https://fastapi.tiangolo.com/) + [PostgreSQL](https://www.postgresql.org/)
- **Security:** Ed25519 Cryptography + BIP39 Mnemonics
- **Infrastructure:** [Docker Swarm](https://docs.docker.com/engine/swarm/) & [Docker Stack](https://docs.docker.com/engine/reference/commandline/stack/) (For high-availability empires) or simply Docker Compose for simple setups!

---

## ⚖️ The Queen's Decree (Disclaimer)

*Hearken, mortals, to the laws of the realm. This framework is a neutral vessel, a hollowed sarcophagus waiting to be filled with your own chosen manifestations. It does not contain, embed, or pre-load any copyrighted content, nor does it provide any default sources, playlists, or streams.*

*The framework is designed solely to allow users to add their own sources—for example, legally acquired streams, public domain content, or content for which they have explicit permission to access, such as a personal Jellyfin-instance or a NAS-storage.*

*The developer does not condone, encourage, or facilitate any form of copyright infringement. You, the user, are solely responsible for ensuring your sources are legal and complying with all applicable laws (including the Swiss URG).*

---

## 🕸️ Follow the Queen

- **Organization:** [@crimsonhaven-to](https://github.com/crimsonhaven-to)
- **Instagram:** [@crimsonhaven.to](https://www.instagram.com/crimsonhaven.to)
- **Reddit:** [r/crimsonhaven](https://www.reddit.com/r/crimsonhaven)
- **TikTok:** [@crimsonhaven.to](https://www.tiktok.com/@crimsonhaven.to)

> *"One day, you’ll open your browser, and your own private haven will be waiting—in crimson splendor."*  
> — **Luminas Crimsonveil**
