# Paul Clark

[![Google Data Analytics](https://img.shields.io/badge/Google%20Data%20Analytics-Certified-blue?style=flat&logo=google&logoColor=white)](https://www.credly.com/badges/d41670d1-a861-474d-be14-0c973c39d122/public_url)
[![IBM AI Product Manager](https://img.shields.io/badge/IBM%20AI%20Product%20Manager-Certified-054ADA?style=flat&logo=ibm&logoColor=white)](https://www.credly.com/badges/abb7596f-3978-48e2-8b19-f344f5a8e9e4/public_url)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/systemslibrarian)


## ⭐ Featured Projects

| Project | Why it stands out |
|---|---|
| ❄️ **[SNOW2](https://github.com/systemslibrarian/snow2)** **[Live Demo](https://systemslibrarian.github.io/snow2/)** | A modern Rust reimplementation inspired by Matthew Kwan's classic SNOW tool, hiding authenticated encrypted payloads inside ordinary-looking text using whitespace steganography. Uses XChaCha20-Poly1305, Argon2id + HKDF, hardened extraction bounds, secure-memory handling, and optional post-quantum support. |
| 🔐 **[TruePad]** [Browser Edition](https://systemslibrarian.github.io/TruePad/)| A cross-platform educational one-time-pad system focused on the engineering problem OTPs usually omit: keeping pad material single-use across crashes, stale copies, restores, two-party state, authentication, and delivery. Uses OTP encryption with one-time Wegman–Carter authentication. |
| 👻 **[Ghost Ink](https://github.com/systemslibrarian/Ghost-Ink)** **[Live Demo](https://systemslibrarian.github.io/Ghost-Ink/)** | An offline-capable browser security lab for hidden and deceptive content across text, Unicode, source code, CSS, clipboard, images, and AI-facing views. Thirteen interactive demonstrations pair hiding techniques with inspection, cleaning, survivability testing, and optional AES-256-GCM payload protection. |

---
## 🏛️ The Cryptography Ecosystem

> **I build systems where trust has to be earned by design — not assumed.**

The arc: history → analysis → selection → experimentation → secure application.

| # | Project | Role in the arc |
|---|---|---|
| 1 | **[Cipher Museum](https://ciphermuseum.com)** · [repo](https://github.com/systemslibrarian/cipher-museum) | **Explore history.** 3,900+ years of cryptography across 167 exhibits — 147 cipher and history exhibits in 13 halls, a 17-exhibit mathematics annex, and 3 protocol and construction exhibits — with 88 browser-runnable engines, live demonstrations, and cryptanalysis tools. |
| 2 | **[Cipher Detective AI](https://huggingface.co/spaces/systemslibrarian/cipher-detective-ai)** · [repo](https://github.com/systemslibrarian/cipher-detective-ai) | **Analyze intelligently.** AI-assisted cipher identification and cryptanalysis exploration — connecting classical cipher patterns with modern machine-learning techniques. |
| 3 | **[Crypto Compare](https://crypto-compare.systemslibrarian.dev)** · [repo](https://github.com/systemslibrarian/crypto-compare) | **Choose wisely.** Side-by-side comparisons of 100 algorithms across 17 categories with misuse-resistant recommendations. |
| 4 | **[Crypto Lab](https://crypto-lab.systemslibrarian.dev/)** · [repo](https://github.com/systemslibrarian/crypto-lab) · [2026 Cybersecurity Excellence Awards — Gold Winner](https://cybersecurity-excellence-awards.com/candidates/crypto-lab-2026/) | **Experiment deeply.** Browser-based cryptography demonstrations spanning post-quantum cryptography, zero-knowledge proofs, homomorphic encryption, MPC, threshold schemes, attacks, steganography, and more. Crypto Lab serves as the continuously maintained master catalog for the collection, with new exhibits added regularly and existing demos periodically re-audited against primary sources, standards, and current research. Its catalog, indexing, metadata, and maintenance tooling are continually refined to keep the growing fleet accurate, discoverable, and current. Now with course modules and worksheets for instructors. Browser-constrained. No accounts. Just the math.|
| 5 | **[Meow Decoder](https://www.meowdecoder.com)** · [repo](https://github.com/systemslibrarian/meow-decoder) | **Apply securely.** Everything above, put to work in an applied security engineering project focused on optical air-gap data transfer and modern encrypted-transfer experiments. |



---
## 📦 Post-Quantum .NET Packages
The **PostQuantum.*** ecosystem is a post-quantum cryptography toolkit for .NET: primitives, framework integrations, analyzers, infrastructure, and governance tools under one package family.

It is not one package trying to do everything. It is a migration path — from cryptographic engines, to application integrations, to misuse-prevention guardrails, to production infrastructure and cryptographic inventory.

**Current scale:** 54+ published NuGet packages · 145K+ total downloads  
**Links:** [NuGet profile](https://www.nuget.org/profiles/systemslibrarian) · [PostQuantum.FileFormat repo](https://github.com/systemslibrarian/PostQuantum.FileFormat)

### The package layers

| Layer | What it provides | Representative packages |
|---|---|---|
| **Engines** | Core cryptographic building blocks: ML-KEM, ML-DSA, hybrid encryption, Argon2id, secret sharing, secure channels, and file encryption. | `PostQuantum.Cryptography` · `PostQuantum.Hybrid` · `PostQuantum.FileEncryption` · `PostQuantum.FileEncryption.Hybrid` · `Argon2id.PasswordHasher` |
| **Integrations** | Packages that bring PQC into places .NET developers already work: ASP.NET Core, Identity, EF Core, Data Protection, JWT/authentication, and dependency injection. | `PostQuantum.Jwt.AspNetCore` · `PostQuantum.Identity` · `PostQuantum.EntityFrameworkCore` · `PostQuantum.DataProtection` · `PostQuantum.FileEncryption.Extensions.DependencyInjection` |
| **Guardrails** | Roslyn analyzers, templates, and testing packages that help developers avoid common cryptographic misuse before it reaches production. | `PostQuantum.Jwt.Analyzers` · `PostQuantum.Jwt.Templates` · `PostQuantum.SecureChannel.Testing` |
| **Infrastructure** | Production-oriented support for cloud key storage, Redis, OpenTelemetry, CLI tooling, signing, replay protection, and key lifecycle management. | `PostQuantum.FileEncryption.Cli` · `PostQuantum.FileEncryption.Signing` · `PostQuantum.DataProtection.Redis` · `PostQuantum.DataProtection.OpenTelemetry` |
| **Governance** | Inventory, configuration, and key-management tooling for teams that need to know what crypto they run, where it lives, and whether it is ready for migration. | cryptographic inventory · configuration tooling · key-management packages |

The goal is not to pretend post-quantum migration is finished. The goal is to make it understandable, testable, reviewable, and usable in real .NET applications.

**ML-KEM · ML-DSA · X-Wing · X25519 · Ed25519 · AES-256-GCM · Argon2id**



---

## 🛡️ Applied Security Engineering

**[Secure File Upload Pipeline (.NET)](https://systemslibrarian.github.io/secure-file-upload-dotnet/)** · [repo](https://github.com/systemslibrarian/secure-file-upload-dotnet)

Most real-world breaches don’t break cryptography — they exploit file uploads and input validation failures.

This project demonstrates a hardened ASP.NET Core upload pipeline with a live demo:

- spoofed file rejection (extension vs content mismatch)
- magic number validation (file signature verification)
- strict allowlisting and fail-closed behavior
- size and abuse protections

*A real attack surface — and what it takes to defend it correctly.*


---
## 🔒 Production Library Systems *(Private — institutional)*

Live systems serving a public library institution and its community. This is where the discipline meets the daily work.

<details>
<summary><strong>Patron Registration Platform + Staff Admin Dashboard</strong></summary>

Replaced a vendor-managed legacy Perl system that had become a single point of failure. Built a modern ASP.NET Core 8 platform integrated with SirsiDynix Symphony Web Services — with a security-first document pipeline (AES-256-GCM encryption, ClamAV malware scanning, deep file content validation), automated patron creation, billing, and barcode lifecycle management.

**Outcome:** staff own the registration workflow for the first time. No vendor dependency for day-to-day operations.

`ASP.NET Core MVC` `C#` `AES-256-GCM` `SirsiDynix`

</details>

<details>
<summary><strong>SwipeWatcher — Real-Time Access Control Monitor</strong></summary>

Before this system, staff had no live view of who was entering or exiting the building. SwipeWatcher monitors C•CURE 9000 door events via HMAC-validated webhooks and delivers immediate alerting and structured logging.

**Outcome:** operational visibility staff had never had before.

`C#` `.NET 8` `Victor Web Services` `C•CURE 9000`

</details>

<details>
<summary><strong>LibCal ↔ C•CURE 9000 Integration</strong> · 🏆 <em>I² Innovator/Inspirator Award</em></summary>

Patrons now unlock meeting rooms with their library cards at the scheduled time — automatic provisioning and revocation driven entirely by LibCal reservation data.

**Outcome:** no staff intervention, no manual access grants, no friction.

`C#` `LibCal APIs` `Victor Web Services`

</details>

<details>
<summary><strong>LibCal ↔ SirsiDynix Integration</strong></summary>

Circulation transactions trigger automatically from LibCal reservation events for Library of Things equipment.

**Outcome:** eliminated a manual checkout step previously required on every loan.

`C#` `LibCal APIs` `SirsiDynix Symphony Web Services`

</details>

---

## ✝️ Scripture & Ministry — Prayer Sealed Ministries, Inc.

> *"For God so loved the world that he gave his one and only Son, that whoever believes in him shall not perish but have eternal life."*  
> — John 3:16 (NIV)

The goal of this work is simple: **that people would come to know Jesus Christ as their Lord and Savior — and keep walking with Him.**

These projects are part of **[Prayer Sealed Ministries, Inc.](https://prayersealed.org)**, a Florida nonprofit organization I founded and serve as **President**. The same way of building — intentional architecture, honest design, and long-term thinking — applied to something eternal.

> 🕊️ **Not sure where you stand with God? [Start with Gospel Journey →](https://systemslibrarian.github.io/gospel-journey/)**  
> A short, Scripture-guided walk from creation to the cross to the empty tomb — and an honest invitation to respond. No account. No tracking.

### One path, not a collection

**Believe → Understand → Remember → Discern → Intercede → Pass It On**

| # | Stage | Project | What it does |
|---|---|---|---|
| 1 | **Believe**<br><sub>Romans 10:9</sub> | **[Gospel Journey](http://gospel.prayersealed.org)** · [repo](https://github.com/systemslibrarian/gospel-journey) | **Start here.** The Gospel in 7 Scripture-anchored steps — created for God, separated by sin, promised a Savior, Jesus came, died for our sins, and rose again — and how to receive Him by grace through faith. Includes *Who Is Jesus?*, *Why Do I Need Saving?*, *The Scarlet Thread*, a prayer of response, and next steps for new believers. |
| 2 | **Understand**<br><sub>Luke 24:27</sub> | **[Scripture Journey](http://scripture.prayersealed.org)** · [repo](https://github.com/systemslibrarian/scripture-journey) | Maps 200+ Old Testament messianic prophecies to their New Testament fulfillments across 7 categories. Scripture as one unified story, with Jesus at the center. |
| 3 | **Remember**<br><sub>Psalm 119:11</sub> | **[Hide in Heart](https://heart.prayersealed.org)** · [repo](https://github.com/systemslibrarian/HideInHeart) | A calm daily companion for Scripture memorization — read the verse, rebuild it word by word, and carry it into life. 47 topics, with a kids mode. |
| 4 | **Discern**<br><sub>James 1:5</sub> | **[His Will Guide](https://hiswillguide.com)** · [repo](https://github.com/systemslibrarian/hiswillguide) | A 10-step biblical framework for seeking God's will through surrender, Scripture, prayer, godly counsel, and obedient trust. |
| 5 | **Intercede**<br><sub>1 Timothy 2:1</sub> | **[Prayer Sealed](https://prayersealed.org)**<br><sub>Flagship project · private beta · public launch December 2026</sub> | **Because Prayer Can’t Wait™** — private prayer for Android and iOS, with partners, groups, and post-quantum end-to-end encryption. Your prayers stay yours—unreadable to the server. |
| 6 | **Pass It On**<br><sub>Psalm 78:4</sub> | **My Life With Christ**<br><sub>In development</sub> | A private Scripture journal for sermon notes, prayers, and reflections that never leaves your device — and over the years becomes a printable record of your faith to hand down to the next generation. |

---

## 🤖 AI as Architecture, Not Autocomplete

I use AI the way I use any other powerful primitive: with an explicit model of what it's good at, what it fails at, and where the guardrails belong.

[**AI Conversation Platform**](https://github.com/systemslibrarian/AI-Conversation-Platform-The-Future-of-Multi-Agent-Collaboration) is the most visible example — async orchestration of autonomous conversations between Claude, ChatGPT, Gemini, Grok, and Perplexity. The point isn't novelty. It's stress-testing reasoning by putting competing models against the same problem and watching what holds up.

Circuit breakers · Prometheus + Grafana observability · LLM Guard · 90%+ test coverage.

---

## What I believe about systems

Security is a posture — not a layer.

Define the threat model first. Build fail-closed. Document honestly where guarantees end.

Understand the primitive before you trust it — at implementation depth.

Systems should be reliable, observable, and self-sustaining in production.

---

**Engineering Focus**

**Languages** — C# · TypeScript · JavaScript · Python · Dart · Rust · SQL

**Frameworks** — .NET 10 (native ML-KEM / ML-DSA BCL types) · .NET 8 · ASP.NET Core MVC · Next.js · Node.js · Vite · Flutter · Firebase

**Security** — AES-256-GCM · Argon2id · HMAC · HKDF · BIP-39 · ML-KEM · ML-DSA · X-Wing (X25519 + ML-KEM) · Ed25519 · HQC · multivariate & ZK schemes · E2EE · forward secrecy · threat modeling · fail-closed design

**Cryptography Education** — crypto-lab (200+ browser demos) · Cipher Museum (167 exhibits) · crypto-compare (100 algorithms across 17 categories) · real-primitive demos · KNOWN-GAPS documentation

**Library Systems** — SirsiDynix Symphony · LibCal · C•CURE 9000 · Victor Web Services

**Practices** — TDD · CI-proven invariants · ADR-driven design · security reviews · WCAG accessibility · explicit threat models · honest capability documentation


---
## Recognition

- 🥇 **Cybersecurity Excellence Awards — Gold** (2026) — Security Education category, for [Crypto Lab](https://github.com/systemslibrarian)
- 🏅 **I² Innovator/Inspirator Award** (2024, 2025) — back-to-back, for LibCal ↔ C•CURE integration
- 🌍 **Library Journal Mover & Shaker** (2012) — Global Leadership
- 🏆 **Florida Librarian of the Year** (2011) — Florida Library Association
- ❤️ **I Love My Librarian Award** (2010) — Carnegie Corporation of New York, *The New York Times*, and the American Library Association
- 🗣️ **Advocate of the Year** (2010) — Florida Association of Counties

Two decades of recognition across advocacy, community leadership, and now security engineering — the same focus on public impact, carried forward
through system design and infrastructure.

---


> *"So whether you eat or drink or whatever you do, do it all for the glory of God."*  
> — 1 Corinthians 10:31 (NIV)
