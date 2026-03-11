# Hi, I'm Paul 👋 — Application Systems Analyst & Google-Certified Data Analyst  

[![Google Data Analytics Certification Badge](https://img.shields.io/badge/Google%20Data%20Analytics-Certified-blue)](https://www.credly.com/badges/d41670d1-a861-474d-be14-0c973c39d122/public_url)
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/systemslibrarian)
[![GitHub Followers](https://img.shields.io/github/followers/systemslibrarian?style=social)](https://github.com/systemslibrarian)
[![GitHub Stars](https://img.shields.io/github/stars/systemslibrarian?style=social)](https://github.com/systemslibrarian)

---

**Specializing in AI-augmented development, library technology, and workflow automation.**  
With a background in IT librarianship and a passion for data, I build tools, data pipelines, and automated workflows that **turn information into actionable insight.**

I use AI as a **true development partner**, freeing me to focus on system architecture, data engineering, and delivering reliable, user-friendly solutions.

💡 **I believe technology is a gift from God — meant to serve people, bring light, and reflect His wisdom and creativity. Everything I build, I want to use for good and for God's glory.**

My ultimate goal? **Contribute to a world-class team at Google while creating technology that honors God and helps people.**

Philosophy & Toolkit
I believe in designing systems that simplify, not complicate — using AI responsibly to empower people and enhance access to knowledge.
CategoryTechnologies & MethodsLanguagesPython, C#, SQL, Rust, JavaScript, HTML/CSSFrameworks & Runtimes.NET 8, ASP.NET Core MVC, Next.js, FastAPIAI / MLPrompt Engineering, LangChain, OpenAI API, Google AI Platform, Multi-Agent Systems, LLM OrchestrationData & EngineeringData Pipelines, Pandas, Visualization, Automation, APIs, WASM, Async Systems, CI/CD, ObservabilitySecurity / PrivacyApplied Cryptography, Protocol Design, Threat Modeling, Steganography, Tamper Detection, Fail-Closed DesignCore PracticesAI-Assisted Development, Ethical Design, Test-Driven Development (TDD), Security Review, Human-Centered Design

🌟 Featured Projects
🤖 AI Conversation Platform — Multi-Agent AI Collaboration

🚀 Live Demo — Watch AI models debate in real-time!


"Because AIs shouldn't monologue — they should converse."

A fully async, type-safe, enterprise-grade platform that turns AI models into autonomous conversational agents.
No scripts. No prompts. Just real-time, multi-model dialogue.
Highlights

5 top-tier LLMs (Claude, ChatGPT, Gemini, Grok, Perplexity)
Async orchestration with circuit breakers & rate limiting
Web dashboard + CLI control
Observability (Prometheus + Grafana)
LLM Guard security & path hardening
Docker, CI/CD, 90%+ test coverage

bashuv run aic-start --agent1 claude --agent2 chatgpt --topic "AI consciousness" --yes
Production-ready. Developer-obsessed. AI-to-AI, out of the box.

🔐 Meow-Decoder — Secure Air-Gapped Data Transfer
🌐 Live Demo
Meow-Decoder is a research and development project for transferring data across air gaps using animated QR / image frames.
A phone acts only as an untrusted optical sensor. All cryptographic operations happen on the endpoints.
Security and design focus

AEAD: AES-256-GCM
Password KDF: Argon2id
Fail-closed parsing and tamper detection
Explicit, versioned byte-level protocol specifications
Threat-model-driven design and security invariants
Conservative, misuse-resistant design goals

Status: Pre-v1 hardening. Not externally audited.
This project is focused on disciplined cryptographic engineering, careful protocol design, and honest security boundaries.

🌍 Additional Projects
✝️ Scripture Journey
🌐 Live Demo
A Christ-centered learning application designed to help people explore how the entire Bible points to Jesus through promise, prophecy, pattern, and fulfillment.
The goal is to help people understand the unified story of Scripture and God's love revealed through Christ.
Tech: Next.js, Tailwind CSS, React, Progressive Web App

🐢 Dad Mode Morse
🌐 Live Demo
A browser-based Morse messaging app that combines encryption, audio transmission, and tribute-driven design in a project dedicated to my dad, a Navy veteran who knew Morse code.
Tech: JavaScript, Web Audio, Client-Side Crypto, HTML/CSS · Focus: Creative Security, Signal Encoding, Human-Centered Design

❄️ SNOW2
🌐 Live Demo
A modern Rust tribute to the classic SNOW steganography tool, focused on secure hidden-message embedding, modern cryptography, and educational security engineering.
Tech: Rust, WASM, Cryptography, Steganography · Focus: Security Engineering, Privacy Tools, Modernized Classic Concepts

📊 IMLS Public Libraries Analysis (2022)
Analyzing U.S. library service and funding trends using IMLS Public Libraries Survey data.
Tech: Python, Pandas, Matplotlib · Focus: Public Library Data, Visualization, Insights

📚 NYT Bestsellers CatKey Generator
Automates catalog key creation for SirsiDynix by fetching NYT Bestseller ISBNs.
Tech: Python, APIs, Automation · Focus: Library Automation

🧠 Bible + AI Prompting Class (NIV Edition)
Teaches AI prompting through interactive Bible study in Google Colab.
Tech: Python, Colab, LLM APIs · Focus: Education, Faith + Technology

🏛️ Selected Private / Internal Projects
Some systems I have built cannot be open sourced because they involve internal infrastructure or operational systems used by the library. Below are high-level summaries of selected projects.
Secure Patron Registration Platform + Staff Administration Dashboard (Private)
Designed and deployed a secure online library card registration platform for the LeRoy Collins Leon County Public Library, along with a separate staff administration and diagnostics dashboard for secure internal processing and operational support. The platform processes patron applications and supporting identity documents while integrating with the SirsiDynix Symphony Integrated Library System through Symphony Web Services APIs.
Key capabilities:

Secure document upload pipeline with AES-256-GCM encryption
Multi-layer file validation and malware scanning
Barcode reservation and issuance workflow
Address validation using ArcGIS services
Automated patron record creation using SirsiDynix Symphony Web Services
Secure staff dashboard for reviewing, approving, rejecting, and managing registrations
Diagnostics dashboard for Symphony connectivity checks, configuration review, and log inspection
Request size limits, rate limiting, and defensive security controls
Adversarial, security, and integration testing to validate system boundaries

Architecture:

ASP.NET Core MVC applications written in C#
Separate public registration app and staff/admin dashboard for security isolation
Encrypted JSON-based shared record storage
Service-layer architecture for validation, scanning, encryption, email, diagnostics, and external integrations
Fail-closed startup behavior and defensive error handling
Integration with SirsiDynix Symphony ILS via Web Services APIs

Focus: Security Engineering, PII Protection, Library Systems Integration, Operational Reliability

SwipeWatcher – Real-Time C-CURE 9000 Event Monitoring System (Private)
Developed a real-time monitoring platform for access control events generated by the C-CURE 9000 security system using Victor Web Services. The system processes door swipe activity, detects operational conditions, and triggers automated alerts for staff.
Key capabilities:

Real-time ingestion of access control events
Secure webhook endpoint with HMAC signature validation
Automated email alerting for monitored door events
Health monitoring and diagnostics endpoints
Structured logging and operational visibility
Reliability safeguards preventing missed or duplicate alerts

Architecture:

Web service written in JavaScript
Victor Web Services integration with the C-CURE platform
Webhook-based event processing pipeline
Monitoring and diagnostics interface for staff

Focus: Real-Time Systems, Security Event Monitoring, Systems Integration, Operational Reliability

LibCal–C-CURE 9000 Integration: Automated Meeting Room Access System (Private) (Team Project)
A collaborative project with a staff programmer to build a web service integrating LibCal meeting room reservations with the C-CURE access control system via Victor Web Services. My role focused on systems analysis, integration architecture, and domain expertise — recognizing that LibCal's APIs could serve as the integration entry point, understanding how the two platforms could be bridged, defining the data flow, and guiding the overall design. The programmer handled implementation.
The system automatically provisions temporary door access permissions, allowing patrons to unlock meeting rooms using their library cards.
Highlights:

Automated creation of temporary access clearances
Integration between LibCal reservations and access control infrastructure
Reduced staff intervention for study and huddle room access
Improved patron autonomy through automated access provisioning
Recognized with an I² (Innovator / Inspirator) Award for development and deployment leadership

Architecture:

Web service written in C#
LibCal APIs used to retrieve reservation data as the integration entry point
C-CURE 9000 via Victor Web Services used to provision and manage access clearances
Web service layer bridging reservation events to access control actions

Focus: API Integration, Systems Analysis, Workflow Automation, Access Control Systems

LibCal–SirsiDynix Integration: Automated Library of Things Checkout System (Private) (Team Project)
A collaborative project with a staff programmer to build a web service integrating LibCal reservation data with the SirsiDynix Symphony Integrated Library System through Symphony Web Services APIs, enabling automated checkout transactions for Library of Things items. My role focused on systems analysis and integration design — identifying that LibCal's APIs could be leveraged as the integration entry point, understanding how LibCal and Symphony could be connected, and defining the data relationships and workflow logic. The programmer handled implementation.
Key capabilities:

Real-time circulation transactions via SirsiDynix Symphony Web Services
Automated synchronization between LibCal reservations and Symphony patron/item records
Reduced manual staff processing for equipment lending workflows
Improved operational efficiency and reliability for Library of Things programs

Architecture:

Web service written in C#
LibCal APIs used to retrieve reservation data as the integration entry point
SirsiDynix Symphony Web Services APIs used to drive circulation transactions
Web service layer bridging LibCal reservation events to Symphony checkout operations
Automated transaction processing for circulation operations

Focus: Library Systems Integration, Systems Analysis, Web Services, Process Automation, Operational Efficiency

💬 Let's Connect
I'm always open to collaboration, thoughtful technical discussions, and projects that combine AI, data, automation, ethics, and public good.
If you're building systems that help people, improve access to knowledge, or solve real operational problems, I'd love to connect.


"So whether you eat or drink or whatever you do, do it all for the glory of God."
— 1 Corinthians 10:31 (NIV)
