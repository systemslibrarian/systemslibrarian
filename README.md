# Paul Clark · Systems Analyst · Library Technologist · AI Builder

**I build production systems where security, AI, and public service intersect — from library platforms that staff depend on daily to cryptographic protocols and Scripture apps that matter.**

Application Systems Analyst · Google Data Analytics Certified

[![Google Data Analytics](https://img.shields.io/badge/Google%20Data%20Analytics-Certified-blue?style=flat&logo=google&logoColor=white)](https://www.credly.com/badges/d41670d1-a861-474d-be14-0c973c39d122/public_url)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/systemslibrarian)
[![GitHub Followers](https://img.shields.io/github/followers/systemslibrarian?style=social)](https://github.com/systemslibrarian)

---

## Start Here

Recommended projects to explore my work:

1. 🔐 **[Meow Decoder](https://github.com/systemslibrarian/meow-decoder)** — Secure air-gapped data transfer using animated QR code frames. Explicit threat model, AEAD cryptography, fail-closed design.
2. 🤖 **[AI Conversation Platform](https://github.com/systemslibrarian/AI-Conversation-Platform-The-Future-of-Multi-Agent-Collaboration)** — Multi-agent LLM orchestration with circuit breakers, observability, and 90%+ test coverage.
3. ✝️ **[Scripture Journey](https://github.com/systemslibrarian/scripture-journey)** — A Christ-centered PWA mapping 200+ Old Testament prophecies to their New Testament fulfillments.
4. 🧪 **[Cryptography Lab](https://systemslibrarian.github.io/crypto-lab/)** — 13 browser-based crypto demos. Real primitives. No backends.

---

## About

By day I'm the engineer behind production systems that a public library depends on — patron registration, access control, ILS integrations, and automated workflows that staff and patrons use without thinking about them, because they just work.

By night I'm building air-gapped crypto tools, multi-agent AI platforms, and Scripture apps that matter to me personally. Scripture Journey and Hide in Heart aren't side projects — they're the same discipline applied to something eternal.

I use AI as a real development partner — moving faster without cutting corners on architecture or correctness.

My Christian faith is the throughline in all of it. Clarity, integrity, and building things worth depending on. I do this work for the glory of God.

---

## Engineering Focus Areas

- **AI Systems & Multi-Agent Orchestration** — Coordinating multiple LLMs for reasoning, comparison, and collaborative problem-solving
- **Security Engineering & Applied Cryptography** — Protocol design, AEAD encryption, threat modeling, and fail-safe architectures
- **Library Systems Integration** — Connecting ILS platforms, access control, reservations, and patron workflows
- **Data Pipelines & Analytics** — Turning raw public-sector data into actionable insights
- **Human-Centered Design** — Prioritizing reliability, accessibility, and real-world usefulness

---

## Technical Toolkit

| Category | Technologies & Tools |
|---|---|
| **Languages** | Python, C#, SQL, Rust, TypeScript, JavaScript |
| **Frameworks** | .NET 8, ASP.NET Core, Next.js, FastAPI |
| **AI / ML** | Multi-Agent Systems, LLM Orchestration, LangChain, OpenAI API, Prompt Engineering |
| **Data** | Pandas, Data Pipelines, APIs, Visualization, CI/CD, Observability |
| **Security** | Applied Cryptography, AEAD, Steganography, Threat Modeling, Fail-Closed Design |
| **Practices** | TDD, Security Reviews, Ethical & Human-Centered Design |

---

## Featured Projects

### 🤖 [AI Conversation Platform](https://github.com/systemslibrarian/AI-Conversation-Platform-The-Future-of-Multi-Agent-Collaboration)

Async platform for orchestrating real-time conversations between multiple LLMs — useful for comparing model reasoning, stress-testing arguments, and exploring how different AI systems approach the same problem.

**Key Features**
- Supports Claude, ChatGPT, Gemini, Grok, and Perplexity
- Async orchestration with circuit breakers and rate limiting
- Observability via Prometheus + Grafana
- LLM Guard integration and security hardening
- Dockerized with CI/CD and 90%+ test coverage

```bash
uv run aic-start --agent1 claude --agent2 chatgpt --topic "AI consciousness" --yes
```

[🌐 Live Demo](https://ai-conversation-demo.onrender.com)

---

### 🔐 [Meow Decoder](https://github.com/systemslibrarian/meow-decoder)

A research tool for secure data transfer across air gaps using animated QR code frames. The phone acts only as an untrusted optical channel — all cryptographic operations stay on the secure endpoints.

**Key Features**
- AES-256-GCM with Argon2id key derivation
- Explicit, versioned byte-level protocol specification
- Fail-closed parsing with tamper detection
- Comprehensive threat model with documented invariants

**Status:** Actively hardening — not yet externally audited.

[🌐 Live Demo](https://www.meowdecoder.com)

---

### ✝️ [Scripture Journey](https://github.com/systemslibrarian/scripture-journey)

A Christ-centered web app that helps readers explore how the entire Bible points to Jesus through 200 messianic prophecy lessons — one of my favorites. Built to show that Scripture is one unified story, and Jesus is the center of all of it.

**Tech Stack:** Next.js · Tailwind CSS · React

[🌐 Live Site](https://scripturejourney.com)

---

## Additional Projects

- ✝️ **Hide in Heart** — A calm daily companion for hiding God's Word in your heart. Rooted in Psalm 119:11 — guiding you through reading, reflection, memorization, and application. `Next.js` `TypeScript` `Supabase` · [🌐 Live App](https://hideinheart.com/)
- 🙏 **PrayerWarriors** — A platform for organizing prayer requests, tracking intercession, and staying grounded in Scripture. Mobile app launching later this year. `Firebase` `Firestore` `Cloud Functions` · [🌐 Preview](https://prayerwarriors.mobi) *(mockup — app coming soon)*
- 📖 **[HisWillGuide](https://github.com/systemslibrarian/hiswillguide)** — Finding God's will through Scripture, prayer, and wisdom. `Faith` · [🌐 Live Site](https://hiswillguide.com)
- 🏛️ **[Cipher Museum](https://github.com/systemslibrarian/cipher-museum)** — Interactive platform exploring the history and mechanics of cryptographic algorithms. `Security Education` · [🌐 Live Site](https://ciphermuseum.com/)
- 📊 **[IMLS Public Libraries Analysis](https://github.com/systemslibrarian/imls-public-libraries-2022)** — Analysis of U.S. public library service and funding trends using IMLS survey data. `Python` `Pandas` `Matplotlib`
- 📚 **[NYT Bestsellers CatKey Generator](https://github.com/systemslibrarian/NYT-Bestsellers-CatKey-Generator)** — Automates SirsiDynix catalog key creation using current NYT Bestseller data. `Python`

---

## Production Systems (Private)

Live systems built for a public library institution — not open-sourced due to security and operational sensitivity.

**🔒 Secure Patron Registration Platform + Staff Administration Dashboard**
Replaced a manual paper-based registration process with a full-stack ASP.NET Core system — encrypted document uploads (AES-256-GCM), malware scanning, ArcGIS address validation, and automated patron record creation through SirsiDynix Symphony Web Services. Staff went from processing paper forms to a streamlined digital workflow.
`ASP.NET Core MVC` `C#` `AES-256-GCM` `SirsiDynix`

**🚪 SwipeWatcher — Real-Time Access Control Event Monitor**
Monitors C-CURE 9000 door events in real time via HMAC-validated webhooks, with automated staff alerting and structured logging — giving staff immediate visibility into access activity they had no way to monitor before.
`JavaScript` `Victor Web Services` `C-CURE 9000`

**🔑 LibCal ↔ C-CURE 9000 Integration** *(Team Project)*
Patrons now unlock meeting rooms with their library cards — no staff intervention required. Automatic access provisioning driven by LibCal reservation data. Recognized with an **I² (Innovator / Inspirator) Award**.
`C#` `LibCal APIs` `Victor Web Services`

**📦 LibCal ↔ SirsiDynix Integration** *(Team Project)*
Eliminated manual checkout processing for Library of Things equipment by triggering circulation transactions directly from LibCal reservation events.
`C#` `LibCal APIs` `SirsiDynix Symphony Web Services`

---

## Let's Connect

Open to conversations on secure AI systems, library technology, applied cryptography, or projects that serve the public good. If you're building something meaningful, I'd love to connect.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/systemslibrarian)

---

> *"And whatever you do, whether in word or deed, do it all in the name of the Lord Jesus, giving thanks to God the Father through him."*
> — Colossians 3:17 (NIV)
