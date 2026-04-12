# Systems Analyst · Library Technologist · Security & Cryptography

I build production systems where public infrastructure, security, and data intersect — from library platforms used by staff daily to cryptographic tools exploring modern encryption, privacy, and post-quantum design.

My work is shaped by a commitment to stewardship, integrity, and service — building systems that are not only functional, but secure, auditable, and intentionally designed.

*Application Systems Analyst · Google Data Analytics Certified*

[![Google Data Analytics](https://img.shields.io/badge/Google%20Data%20Analytics-Certified-blue?style=flat&logo=google&logoColor=white)](https://www.credly.com/badges/d41670d1-a861-474d-be14-0c973c39d122/public_url)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/systemslibrarian)
[![GitHub Followers](https://img.shields.io/github/followers/systemslibrarian?style=social)](https://github.com/systemslibrarian)

---


## Start Here

Recommended projects to explore my work:

1. 📖 **[Crypto Compare](https://systemslibrarian.github.io/crypto-compare/)** ([repo](https://github.com/systemslibrarian/crypto-compare)) — Algorithm reference & chooser across 17 cryptographic categories. Start here to understand *why* before you experiment with *how*.

2. 🧪 **[Crypto Lab](https://systemslibrarian.github.io/crypto-lab/)** ([repo](https://github.com/systemslibrarian/crypto-lab)) — The central index for Crypto Lab — 60 interactive browser-based cryptography demos. From deniable encryption and post-quantum algorithms to visual attacks and zero-knowledge proofs. Everything runs client-side. No accounts. Just the math.

   > *crypto-compare is the map. crypto-lab is the playground. Use them together.*

3. 🔐 **[Meow Decoder](https://www.meowdecoder.com/)** ([repo](https://github.com/systemslibrarian/meow-decoder)) — Secure optical air-gap file transfer via animated QR-code GIFs. AES-256-GCM + Argon2id + ML-KEM-1024 + fountain codes. Explicit threat model, fail-closed design.

4. ✝️ **[Scripture Journey](https://scripturejourney.com)** ([repo](https://github.com/systemslibrarian/scripture-journey)) — A Christ-centered PWA mapping 200+ Old Testament prophecies to their New Testament fulfillments.

5. 🤖 **[AI Conversation Platform](https://ai-conversation-demo.onrender.com/)** ([repo](https://github.com/systemslibrarian/AI-Conversation-Platform-The-Future-of-Multi-Agent-Collaboration)) — Multi-agent LLM orchestration with circuit breakers, observability, and 90%+ test coverage.

---

## About

By day, I’m a systems analyst (IT Librarian) behind mission-critical systems a public library depends on — patron registration, access control, ILS integrations, and automated workflows that staff and patrons rely on because they simply work.

Outside of work, I build air-gapped cryptographic tools, multi-agent AI platforms, and Scripture apps that matter to me personally. *Scripture Journey* and *Hide in Heart* aren’t side projects — they’re the same discipline applied to something eternal.

The cryptography work isn’t separate from my library career — it underpins it. Patron data is sensitive by nature. I built [Crypto Lab](https://systemslibrarian.github.io/crypto-lab/), [Shadow Vault](https://systemslibrarian.github.io/shadow-vault/), [Meow Decoder](https://www.meowdecoder.com/), and related projects to understand AEAD encryption, key derivation, deniable containers, and post-quantum primitives at the implementation level — not just call a library and assume correctness.

Every production system I ship reflects that discipline: AES-256-GCM encrypted uploads, HMAC-validated webhooks, fail-closed parsing, and explicit threat models. The demos exist to make that discipline visible.

I use AI as a development partner — accelerating iteration without compromising architecture or correctness.

My Christian faith is the throughline — shaping a focus on clarity, integrity, and building systems worth depending on.

---

## Engineering Focus Areas

- **Security Engineering & Applied Cryptography** — Protocol design, AEAD encryption, post-quantum primitives, threat modeling, and fail-safe architectures  
- **AI Systems & Multi-Agent Orchestration** — Coordinating multiple LLMs for reasoning, comparison, and collaborative problem-solving  
- **Library Systems Integration** — Integrating ILS platforms, access control, reservations, and patron workflows  
- **Data Pipelines & Analytics** — Transforming raw public-sector data into actionable insights  
- **Human-Centered Design** — Prioritizing reliability, accessibility, and real-world usability

---

## Technical Toolkit

**Languages**  
C#, TypeScript, JavaScript, Python, Rust, SQL  

**Frameworks**  
.NET 8, ASP.NET Core MVC, Next.js, Node.js  

**AI / ML**  
Multi-agent orchestration, LLM APIs, prompt engineering  

**Data**  
SQL Server, Power BI, Pandas, APIs, observability  

**Security**  
AES-256-GCM, Argon2id, HMAC, post-quantum (ML-KEM, SMAUG-T, HAETAE), threat modeling, fail-closed design  

**Practices**  
TDD, security reviews, WCAG accessibility, ethical and human-centered design

---

## Featured Projects

### 🔐 [Meow Decoder](https://github.com/systemslibrarian/meow-decoder)

A research tool for secure data transfer across air gaps using animated QR code frames. The phone acts only as an untrusted optical channel — all cryptographic operations stay on the secure endpoints. Built as a tribute to my Navy-veteran father.

**Key Features**
- AES-256-GCM with Argon2id key derivation
- ML-KEM-1024 post-quantum hybrid keys
- Fountain codes for reliable optical transmission
- Explicit, versioned byte-level protocol specification
- Fail-closed parsing with tamper detection

**Status:** Actively hardening — not yet externally audited. All cryptographic primitives are standard, publicly vetted algorithms. Security depends on correct implementation.

[🌐 Live Demo](https://www.meowdecoder.com)

---

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

### ✝️ [Scripture Journey](https://github.com/systemslibrarian/scripture-journey)

A Christ-centered web app that helps readers explore how the entire Bible points to Jesus through 200+ messianic prophecy lessons. Built to show that Scripture is one unified story, and Jesus is the center of all of it.

**Tech Stack:** Next.js · TypeScript · Tailwind CSS

[🌐 Live Site](https://scripturejourney.com)

---

## Additional Projects
- 🏛️ **[Cipher Museum](https://github.com/systemslibrarian/cipher-museum)** — Interactive platform exploring 2,500 years of cryptographic history across 10 halls and 37 ciphers. `Security Education` · [🌐 Live Site](https://ciphermuseum.com/)
- ✝️ **[Hide in Heart](https://hideinheart.com/)** — A calm daily companion for hiding God's Word in your heart. Rooted in Psalm 119:11. 
- 🙏 **[PrayerWarriors](https://prayerwarriors.mobi)** — A platform for organizing prayer requests and tracking intercession. 
- 📖 **[HisWillGuide](https://hiswillguide.com)** — Finding God's will through Scripture, prayer, and wisdom. 
- 📊 **[IMLS Public Libraries Analysis](https://github.com/systemslibrarian/imls-public-libraries-2022)** — Analysis of U.S. public library service and funding trends using IMLS survey data.
- 📚 **[NYT Bestsellers CatKey Generator](https://github.com/systemslibrarian/NYT-Bestsellers-CatKey-Generator)** — Automates SirsiDynix catalog key creation using current NYT Bestseller data. 

---

## Production Systems (Private)

Live systems built for a public library institution — not open-sourced due to security and operational sensitivity.

**🔒 Secure Patron Registration Platform + Staff Administration Dashboard**
Replaced a vendor-managed legacy Perl registration system with a modern ASP.NET Core platform integrated with SirsiDynix Symphony Web Services. Designed a security-first document pipeline (AES-256-GCM encryption, malware scanning, deep file validation) and automated patron creation, billing, and barcode lifecycle management. Delivered a fully auditable, accessible workflow that modernized patron onboarding and reduced reliance on vendor-controlled infrastructure.
`ASP.NET Core MVC` `C#` `AES-256-GCM` `SirsiDynix`

**🚪 SwipeWatcher — Real-Time Access Control Event Monitor**
Monitors C•CURE 9000 door events in real time via HMAC-validated webhooks, with automated staff alerting and structured logging — giving staff immediate visibility into access activity they had no way to monitor before.
`C#` `.NET` `Victor Web Services` `C•CURE 9000`

**🔑 LibCal ↔ C•CURE 9000 Integration** *(Team Project)*
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

> *"So whether you eat or drink or whatever you do, do it all for the glory of God."*
> — 1 Corinthians 10:31 (NIV)
