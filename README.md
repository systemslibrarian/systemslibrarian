# Paul Clark

[![Google Data Analytics](https://img.shields.io/badge/Google%20Data%20Analytics-Certified-blue?style=flat&logo=google&logoColor=white)](https://www.credly.com/badges/d41670d1-a861-474d-be14-0c973c39d122/public_url)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/systemslibrarian)
[![GitHub](https://img.shields.io/github/followers/systemslibrarian?style=social)](https://github.com/systemslibrarian)
[![Website](https://img.shields.io/badge/systemslibrarian.dev-visit-brightgreen?style=flat&logo=github)](https://systemslibrarian.dev)

## I build systems where trust has to be earned by design — not assumed.

Patron data. Access control. Cryptographic tools. Multi-agent AI. The common thread is the same: systems that hold up under scrutiny because that's how they were built from the first line of code.

Every system I ship carries an explicit threat model, a fail-closed posture, and an honest accounting of what it does and doesn't guarantee.

---

## 🔐 Start here: Meow Decoder

> [**meowdecoder.com**](https://www.meowdecoder.com) · [repo](https://github.com/systemslibrarian/meow-decoder)

**Secure file transfer across an air gap.** Two computers that will never touch a network exchange data through animated QR-code streams on a phone screen. The phone is treated as an untrusted optical channel — every cryptographic guarantee stays on the secure endpoints.

The threat model is the point. Not the primitives — the primitives are standard. What's rare is the discipline of deciding up front what you're defending against, designing for that, and documenting honestly where the protection ends.

**Stack:** AES-256-GCM · Argon2id · ML-KEM-1024 hybrid (post-quantum) · fountain codes · versioned byte-level protocol · fail-closed parsing


---

## 🛡️ Applied Security Engineering (Live Demonstration)

**[Secure File Upload Pipeline (.NET)](https://github.com/systemslibrarian/secure-file-upload-dotnet)** · [Live Demo](https://systemslibrarian.github.io/secure-file-upload-dotnet/)

Most real-world breaches don’t break cryptography — they exploit file uploads and input validation failures.

This project demonstrates a hardened ASP.NET Core upload pipeline with a live demo:

- spoofed file rejection (extension vs content mismatch)
- magic number validation (file signature verification)
- strict allowlisting and fail-closed behavior
- size and abuse protections

*A real attack surface — and what it takes to defend it correctly.*


---

## 🏛️ The Cryptography Ecosystem

Meow Decoder didn't appear from nowhere. It exists because I spent years building the understanding to make it trustworthy. These four projects form one deliberate path — from classical ciphers to production-grade applied cryptography.

| | Project | Role in the arc |
|---|---|---|
| **1** | [**Cipher Museum**](https://ciphermuseum.com/) · [repo](https://github.com/systemslibrarian/cipher-museum) | **Learn the history.** 2,500 years of cryptography through 37 ciphers, 10 exhibit halls, live demos, and cryptanalysis tools. |
| **2** | [**Crypto Compare**](https://crypto-compare.systemslibrarian.dev/) · [repo](https://github.com/systemslibrarian/crypto-compare) | **Choose wisely.** Side-by-side algorithm comparisons across 17 categories with misuse-resistant recommendations. |
| **3** | [**Crypto Lab**](https://crypto-lab.systemslibrarian.dev/) · [repo](https://github.com/systemslibrarian/crypto-lab) | **Experiment deeply.** 99+ browser-based demos — post-quantum, ZK proofs, homomorphic encryption, MPC, threshold schemes, attacks, steganography. *Browser-constrained. Educational by design. No accounts. Just the math.* |
| **4** | [**Meow Decoder**](https://www.meowdecoder.com) · [repo](https://github.com/systemslibrarian/meow-decoder) | **Apply securely.** Everything above, put to work. |

I didn't build these to pad a portfolio. I built them because I wanted to know — at implementation depth — what I was trusting in production code.

---

## 🔒 Production Library Systems *(Private — operational sensitivity)*

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

## ✝️ Scripture & Ministry — The Same Discipline

The same way of building — intentional architecture, honest design, long-term thinking — applied to something eternal. Structured as a path, not a collection.

| Stage | Project | What it does |
|---|---|---|
| **Understand** | [**Scripture Journey**](https://scripturejourney.com) | Maps 200+ OT messianic prophecies to NT fulfillments across 7 categories. Scripture as one unified story, with Jesus at the center. |
| **Remember** | [**Hide in Heart**](https://hideinheart.com) | Daily companion for Scripture memorization. Rooted in Psalm 119:11. |
| **Discern** | [**HisWillGuide**](https://hiswillguide.com) | A 10-step biblical framework for finding God's will through Scripture, prayer, and community wisdom. |
| **Intercede** | [**PrayerWarriors**](https://prayerwarriors.mobi) | Mobile-first platform for organizing prayer requests and tracking intercession. Live mockup at prayerwarriors.mobi — in active design. Long-term ministry goal. |

---

## 🤖 AI as Architecture, Not Autocomplete

I use AI the way I use any other powerful primitive: with an explicit model of what it's good at, what it fails at, and where the guardrails belong.

[**AI Conversation Platform**](https://github.com/systemslibrarian/AI-Conversation-Platform-The-Future-of-Multi-Agent-Collaboration) is the most visible example — async orchestration of autonomous conversations between Claude, ChatGPT, Gemini, Grok, and Perplexity. The point isn't novelty. It's stress-testing reasoning by putting competing models against the same problem and watching what holds up.

Circuit breakers · Prometheus + Grafana observability · LLM Guard · 90%+ test coverage.

---

## What I believe about systems

**Security is a posture, not a layer.**  
You hold it from the start or you don't have it.

**Honest documentation is part of the system.**  
If something isn't audited, I say so. If a browser-based demo can't replicate real-world attack conditions, I say so. Overstating guarantees is its own security failure.

**Understand the primitive before you trust it.**  
I built 99+ cryptographic demos so I'd know, at implementation depth, what I was calling in production.

**Good systems outlast their builders.**  
The ones I've shipped run without me in the room. That's the goal.

---

## Engineering Focus

**Languages** — C# · TypeScript · JavaScript · Python · Rust · SQL

**Frameworks** — .NET 8 · ASP.NET Core MVC · Next.js · Node.js

**Security** — AES-256-GCM · Argon2id · HMAC · ML-KEM · SMAUG-T · HAETAE · threat modeling · fail-closed design

**Library Systems** — SirsiDynix Symphony · LibCal · C•CURE 9000 · Victor Web Services

**Practices** — TDD · security reviews · WCAG accessibility · explicit threat models · honest capability documentation

---

## Recognition

National and industry recognition for leadership, advocacy, and public impact in library systems and community access:

- 🏆 **Florida Librarian of the Year (2011)** 
- 🌍 **Library Journal Mover & Shaker — Global Leadership (2012)**  
- ❤️ **I Love My Librarian Award (2010)** — Carnegie Corporation of New York, *The New York Times*, American Library Association  
- 🗣️ **Advocate of the Year (2010)** — Florida Association of Counties  
- 🏅 **I² Innovator/Inspirator Award (2024, 2025)** — LibCal ↔ C•CURE Integration

These recognitions reflect earlier work in advocacy and community leadership — the same focus on public impact now carried forward through system design, security, and infrastructure.

---

If what I've described sounds like the way you think — public infrastructure, applied cryptography, AI systems that have to be responsible — let's talk.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/systemslibrarian)

---

> *"So whether you eat or drink or whatever you do, do it all for the glory of God."*  
> — 1 Corinthians 10:31 (NIV)
