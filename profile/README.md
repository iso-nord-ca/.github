<div align="center">

# Technology, shaped by the North.

**Independent creative technology from Québec City.**  
Privacy-first software · Local AI · Native tools · Cinematic digital experiences

English · [Français](README.fr.md)

[Explore the work](#selected-work) · [See what is emerging](#coming-into-view) · [Get in touch](#contact)

</div>

---

## We build at the edge of software and image

ISO NORD is an independent creative technology lab from Québec City, building privacy-first software, open-source developer tools, intelligent products, and cinematic digital experiences.

The most interesting products rarely stay inside one category. A native Mac utility can express how computers should feel. A photography tool can be applied computer vision. A city platform can combine geospatial systems, real-time graphics, and filmmaking language. An AI workflow can become infrastructure for an independent builder.

ISO NORD exists in that overlap.

We build considered technology: useful before impressive, understandable before clever, and crafted from internal architecture to final pixel. We work across Swift, SwiftUI, TypeScript, Go, Python, web graphics, computer vision, local models, agent tooling, and creative production. The stack changes with the problem. The principles do not.

The name comes from Québec City: northern without being remote, historic without being frozen in time, and built from contrasts. That environment shapes the work. Resilience, clarity, atmosphere, and small details matter because they make a system trustworthy. Some projects become products, some become open infrastructure, and others remain research until the idea is ready.

## A manifesto for useful ambition

### The best technology creates agency

A computer should make its user more capable. It should remove repetitive work, expose meaningful control, and help a person move from intention to result without demanding that they surrender their judgment.

That is especially important as software becomes more autonomous. AI systems can now see screens, generate media, route work, operate tools, and coordinate other agents. The opportunity is enormous, but so is the temptation to replace transparency with spectacle. We take the opposite approach. The user should know what a system can do, where information goes, what remains local, and how to stop or reverse an action.

Agency is not a settings page added at the end. It is an architectural choice.

### Privacy is a product feature

Local-first is not a slogan for us. It is often the shortest path to a faster, more reliable, more respectful product. When a task can happen on the device, it should not automatically require a server round trip. When sensitive media can be analyzed with Apple frameworks or local models, it should not be uploaded simply because cloud inference is convenient. When a developer tool can run without telemetry, an account, or an API key, that simplicity is worth protecting.

Privacy also changes the feeling of a product. A local tool can be immediate. It can work during a network outage. It can operate on private repositories, personal photographs, or system context without turning that material into someone else’s dataset. It can be inspected, controlled, and removed.

Not every system can be entirely local, and pretending otherwise would be dishonest. But every project can minimize collection, make boundaries explicit, and treat trust as part of the interface.

### Craft includes the invisible parts

Good software is more than a screenshot. Motion, typography, latency, keyboard behavior, error recovery, installation, documentation, naming, accessibility, data formats, and the ability to undo a change all contribute to quality.

The invisible parts matter too: a clear repository, safe defaults, predictable state, understandable logs, reversible operations, and components that can evolve without turning the entire product into a puzzle. We like native platforms because they can make these details feel natural, but we are not attached to nativeness as a badge. We use it when it creates a better relationship between the tool and the machine.

Our visual background influences this engineering practice. In cinematography, the frame is only the surface. Lens choice, blocking, light, rhythm, sound, and editing determine whether the image means anything. Software works the same way. The interface is the frame; architecture and behavior create the experience.

### Open source is a conversation

Open source can be a distribution model, but its deeper value is legibility. It allows an idea to be tested in public. It invites someone to challenge an assumption, adapt a component, learn from a failure, or carry a project into a context its original author never imagined.

We publish tools when openness makes them more useful. That may mean a full application, a command-line utility, a documented binary format, a workflow template, or a small guardrail that prevents a dangerous command. The scale is secondary. A twenty-line script can change a developer’s day; a complete native app can become a foundation for a community.

Open also means honest. Early projects should look early. Limitations should be written down. Licenses should be clear. A public repository is not automatically a finished product, and experimentation should not be disguised as stability.

### Small teams can build serious systems

The modern software workshop has changed. One focused builder can now combine native development, AI-assisted research, design systems, automated testing, media production, and distribution in a single workflow. That does not remove the need for expertise. It makes judgment more valuable.

ISO NORD explores tools for this new scale of work: routing tasks to the right coding agent, monitoring MCP servers, turning an iPad into a control surface, generating motion graphics locally, and coordinating a fleet of agents without hiding what they are doing. These projects are not about replacing teams with prompts. They are about giving independent builders better instruments.

## Four territories

### 01 — Native software

Native apps can feel like part of the computer rather than a website placed inside it. We build for Apple platforms when deep system integration, performance, privacy, or interaction quality makes that choice meaningful.

Our native work includes menu-bar utilities, media tools, system customization, computer-use infrastructure, and iOS research. Swift and SwiftUI let us work close to platform capabilities such as Vision, file metadata, accessibility, system appearance, and local process control. The goal is not to imitate Apple. It is to understand the platform well enough to create software with its own identity that still feels at home.

### 02 — Local AI and agent tools

Agents are becoming a new interface layer for software development and computer operation. We are building the support systems around them: orchestration, observability, routing, physical controls, safe defaults, and native computer use.

This territory is deliberately practical. An agent should be easier to understand when it fails. Multiple tools should not require a maze of configuration. A local workflow should not demand another subscription or API key when an existing authenticated product can do the work. The result should feel less like a demo and more like dependable equipment.

### 03 — Creative technology

Creative work is full of technical friction: reviewing thousands of images, maintaining metadata, generating motion assets, moving between devices, and turning an abstract brief into something visible. Our creative tools come from direct experience with photography, video, drone work, and motion design.

We are interested in automation that protects taste. The machine can detect blur, group bursts, render variations, or assemble a pipeline. The person still decides what matters. Great creative software does not erase authorship; it gives authors more time for the decisions only they can make.

### 04 — Experimental platforms

Some ideas need room before they become products. Digital twins, biometric verification, night-observation archives, administrative navigation, and spatial interfaces combine policy, design, sensing, data, and storytelling in ways that cannot be reduced to a weekend feature list.

We approach these projects as research with a destination. Prototypes establish the interaction. Open-source editions test the architecture. Private previews protect unfinished work while the boundaries become clear. When something enters public view, its status is stated plainly.

## Selected work

The projects below are public experiments and releases. Some live in the ISO NORD organization; others are published under the founder's account. Each link points to the canonical repository.

### [Hurst](https://github.com/iso-nord-ca/hurst-framework)

**A TypeScript algorithmic trading framework — write a strategy once, run it in backtest, paper, and live modes.**

Hurst is the organization's flagship infrastructure project: a hexagonal trading engine for Interactive Brokers and beyond. Strategies are written once and run unchanged across backtest, paper, and live modes, with isolated sub-portfolios, Sharpe/Sortino/drawdown metrics, and a CLI. Phase 1 (the backtest engine, CSV+Parquet adapters, 72 passing tests) is implemented and published on npm as [hurst-framework](https://www.npmjs.com/package/hurst-framework).

The ecosystem spans focused repositories — broker adapters, data importers, a 55-strategy library, a risk-management overlay, Docker packaging with IB Gateway, a terminal UI with an AI assistant, and a companion website. It is honest about maturity: what is built, what is stubbed, and what comes next is written down.

### [Folia](https://github.com/iso-nord-ca/folia)

**Real-time AI voice notes. You talk, Folia writes.**

Folia structures your voice into clean notes, summaries, to-dos, math, and diagrams as you speak — then lets you search, replay, edit, and chat with everything you have recorded. The bet is live structuring rather than post-hoc transcription: the value shows up while you are recording, not five minutes after.

It is early development, with an open [spec](https://github.com/iso-nord-ca/folia-docs). The design goal is stationery that happens to be alive — quiet, editorial, nothing that looks like a productivity tool.

### [Nova Computer Use](https://github.com/theodorebeaupre-prog/nova-computer-use)

**Native, local-first computer use for Codex on Intel and Apple Silicon Macs.**

Nova explores what computer control looks like when it belongs on the Mac. Written in Swift and released under the AGPL, it is designed around local operation and native system integration rather than a remote automation service. Supporting both Intel and Apple Silicon matters: capable hardware should not become irrelevant simply because a tool assumes the newest machine.

The project sits at the intersection of accessibility APIs, agent tooling, and trustworthy automation. Its broader question is simple: can an AI operate a computer while the user retains a clear sense of where the capability lives and how it behaves?

### [Agentbar](https://github.com/theodorebeaupre-prog/agentbar)

**Mission control for coding agents, in the macOS menu bar and the terminal.**

Agentbar gives agent-heavy workflows a native place to live. It is free, local, and designed with zero telemetry. Rather than treating coding agents as invisible background processes, it makes their presence and activity easier to reach from the system interface developers already use all day.

The project reflects an ISO NORD pattern: observability should be lightweight enough to remain open, not another dashboard that demands constant attention.

### [PhotoCull](https://github.com/theodorebeaupre-prog/photocull)

**On-device photo culling for macOS.**

PhotoCull applies computer vision to one of photography’s least cinematic realities: sorting a large shoot. It detects blur and closed eyes, groups bursts, and writes XMP sidecars that fit into Lightroom workflows. Analysis stays on the device.

The purpose is not to let an algorithm choose the final photograph. It is to surface technical problems and repeated frames quickly, so the photographer can spend more attention on expression, timing, story, and the images that deserve a second look. PhotoCull is free, open source, written in Swift, and licensed under MIT.

### [MCP Deck](https://github.com/theodorebeaupre-prog/mcp-deck)

**A native macOS dashboard for Model Context Protocol servers.**

As more development tools depend on MCP, configuration becomes infrastructure. MCP Deck brings health checks, per-client enable and disable controls, and live logs into a focused menu-bar application. It is built to answer the operational questions that appear after the first successful demo: Which server is running? Which client can see it? What just failed?

The project is open source under MIT and treats agent infrastructure like something that deserves a proper control surface.

### [Usher](https://github.com/theodorebeaupre-prog/usher)

**One command. The right coding agent. Every time.**

Usher is a Go command-line router for Claude Code, Codex, and Gemini subscriptions. It selects a suitable agent for the task without asking users to rebuild their workflow around API keys. The idea is intentionally small: developers already have powerful tools, but choosing and invoking them consistently creates friction.

Usher turns that choice into infrastructure. It is a doorway, not another room.

### [Hangar](https://github.com/theodorebeaupre-prog/hangar)

**Mission control for the solo AI builder.**

Hangar is a Python-based family of Claude Code skills for preparing, fueling, and launching a fleet of coding agents. Where Usher focuses on routing, Hangar focuses on workflow: establishing context, creating repeatable operating patterns, and helping one builder coordinate more work without losing the thread.

Its aviation language is not decoration. Good launches depend on preparation, checks, clear roles, and knowing when the vehicle is not ready to fly.

### [CoMotion](https://github.com/theodorebeaupre-prog/comotion)

**A self-hosted path from brief to motion-graphics video.**

CoMotion combines a Claude Code skill, MCP server, and CLI into a local video-generation pipeline. It can turn a brief into motion graphics with voiceover while keeping rendering self-hosted. The project explores a creative workflow in which AI coordinates production steps without forcing the entire process into a closed generation platform.

For ISO NORD, this is the interesting part of generative media: not a single surprising output, but a system that can be inspected, directed, repeated, and integrated into real production.

### [ISO OS — Open Source](https://github.com/theodorebeaupre-prog/iso-os-oss)

**A privacy-first urban digital twin and cinematic city-visualization platform.**

ISO OS explores the city as an interface. Its open-source edition brings together geospatial thinking, real-time web graphics, privacy, and a cinematic approach to observation. Instead of reducing a place to abstract dashboards, it asks how digital infrastructure can preserve atmosphere and spatial understanding.

The project is built in TypeScript and remains experimental. It is both a platform direction and a research surface for visualizing complex urban information without losing the human scale of the streets beneath it.

### [Aura](https://github.com/theodorebeaupre-prog/Aura)

**Reversible macOS 26 Tahoe customization.**

Aura is an early-development Swift utility for Liquid Glass presets, animation controls, and other system appearance adjustments. Its central word is reversible. Personalization should not require risky one-way tweaks or leave users guessing how to return to a stable state.

Aura is open source under MIT and approaches customization as product design rather than a collection of hidden commands.

### [Garmin GCD Toolkit](https://github.com/theodorebeaupre-prog/garmin-gcd-toolkit)

**Inspect, extract, and research Garmin firmware containers.**

The Garmin GCD Toolkit documents a firmware-container format and provides a Python CLI for analysis. It grew from hands-on reverse engineering and an interest in interoperability: understanding how an existing device stores and moves its software, then turning that understanding into reproducible tooling.

This work represents another side of ISO NORD. Not every project starts with a new interface. Sometimes the valuable work is careful observation, binary analysis, documentation, and leaving the path clearer for the next researcher.

### [CoPad Server](https://github.com/theodorebeaupre-prog/copad-server)

**Turn an iPad into a physical control surface for Claude Code.**

CoPad Server connects a Mac workflow to an iPad interface, creating something closer to a Stream Deck for agentic development. It explores the physical dimension of software tools: buttons, state, proximity, and the value of moving important controls off the crowded main display.

It is a practical experiment in making AI workflows tangible.

### [ISO NORD Claude Code Starter](https://github.com/theodorebeaupre-prog/iso-nord-claude-code-starter)

**A safer starting point for agent-assisted development.**

This starter combines a dangerous-command guard hook, reusable `CLAUDE.md` templates, and a writing guide. It focuses on the part of agent tooling that is easiest to ignore: the quality of the instructions and boundaries surrounding the model.

The repository is free and intentionally approachable. Better agent workflows should not require discovering every failure mode personally.

## Coming into view

The following projects are private or still in development. They are included here as directions, not promises. There are no announced beta dates, and details may change as the work becomes clearer.

### kitty — In development

kitty is the group chat's money layer for Canada: one link, everyone chips in, nobody gets chased. It coordinates group purchases over Interac e-Transfer — collecting confirmations, tracking who is in, and keeping things transparent — while never holding, moving, or escrowing funds. Money moves directly between participants on rails we do not operate, and that boundary is treated as a hard compliance line, not a feature.

It is a deliberately small product with a deliberately clear edge.

### VISO ID — Research / private preview

VISO ID investigates privacy-first local biometric verification for iPhone and Mac. The research focuses on how identity or presence can be verified while keeping sensitive biometric processing close to the user’s devices and making system boundaries understandable.

Biometrics is a high-trust domain. The project is therefore being treated as research before product: threat models, storage, liveness, transport, enrollment, recovery, and user comprehension matter as much as recognition performance.

### ISO OS — In development

The private ISO OS work extends the ideas visible in the open-source edition: an urban digital twin with a cinematic visual language and privacy-first foundations. It explores how a platform can connect spatial information, city systems, observation, and narrative without turning people or places into an extractive data layer.

The open-source repository is the public window. The broader product remains in development.

### Nocturne — Private preview

Nocturne is a cinematic WebGL night-observation archive built with Astro, Lenis, and Three.js. Shader-driven image planes remain synchronized with the document, allowing the interface to preserve the rhythm of editorial browsing while introducing depth, movement, and atmosphere.

It is a meeting point between photographic archive, web engineering, and night cinematography—less a gallery template than an experiment in how digital space can carry a visual memory.

### Cairn — In development

Cairn is a SwiftUI administrative navigation app for major life transitions in Québec. Its premise is that important moments—moving, changing status, starting a new chapter—often create a confusing map of forms, institutions, deadlines, and dependencies.

The name refers to a marker that helps someone find a path through difficult terrain. The product is being developed with the same intention: make bureaucracy legible without pretending it is simple.

## How we build

We choose technology from the constraints outward.

For native Apple work, that often means Swift, SwiftUI, Vision, system frameworks, and direct platform integration. For durable command-line tools, Go or Python may create a clearer distribution and maintenance story. TypeScript connects web interfaces, MCP systems, real-time graphics, and creative pipelines. Astro and Three.js support visual work where the browser is both document and scene.

Across stacks, we prefer a few consistent qualities:

- **Local by default when the task permits it.** Data should not travel without a reason.
- **Reversible operations.** Users need a safe path back.
- **Observable behavior.** Logs, state, and failure should be understandable.
- **Small, composable tools.** A focused CLI or protocol can outlive a large interface.
- **Native affordances where they matter.** Menu bars, files, metadata, shortcuts, and accessibility are part of the product.
- **Documentation as a feature.** A system is not complete if only its author can operate it.
- **Honest maturity labels.** Research, preview, early development, and release mean different things.
- **Design with atmosphere, not decoration.** Visual identity should support orientation and meaning.

AI is part of the workshop, not the author of record. Models can accelerate research, implementation, testing, and iteration. Judgment remains human: deciding what to build, checking what is true, recognizing what feels wrong, protecting private information, and taking responsibility for the released result.

## Open work, open doors

ISO NORD’s public repositories are working objects. Some are complete utilities; others are active experiments. Issues, focused pull requests, careful bug reports, documentation improvements, and real-world feedback are welcome where a repository supports them.

Before contributing, read the project’s own README and license. Each tool has different boundaries. A native macOS app, a firmware research toolkit, and an agent skill family should not be forced into the same contribution process.

If you use one of the tools, the most valuable feedback is concrete: what you were trying to do, which environment you used, what happened, what you expected, and whether the problem can be reproduced. If you extend a project, explain the use case before the implementation. Clear intent makes technical review faster.

We also believe unfinished knowledge can be useful. A documented constraint, an unsuccessful approach, or a small interoperability note may save someone else days. Open source becomes stronger when repositories preserve reasoning, not only final code.

## Built in Québec City

ISO NORD is based in Québec City, Canada.

The studio’s perspective comes from making software and images in the same place: writing Swift beside camera batteries, testing local infrastructure on old and new Macs, studying motion through both interface animation and real footage, and treating the city as a technical environment as much as a backdrop.

The North in ISO NORD is not a claim of distance or severity. It is a design constraint and a source of character. Build for changing conditions. Make systems that remain useful. Respect the material. Let light, motion, silence, and precision do some of the talking.

We are early, independent, and still defining the full shape of the lab. That is an advantage. It leaves room to connect disciplines before organizational boundaries harden around them. It makes it possible for a firmware tool, a photo-culling app, a city platform, and an agent dashboard to inform one another.

Different outputs. One practice.

## Contact

For collaboration, project questions, creative technology work, or thoughtful conversations about what we are building:

- **Email:** [info@theo-picture.com](mailto:info@theo-picture.com)
- **GitHub:** [@iso-nord-ca](https://github.com/iso-nord-ca)
- **Founder:** [@theodorebeaupre-prog](https://github.com/theodorebeaupre-prog)
- **Instagram:** [@iso_nord](https://www.instagram.com/iso_nord/)

If you are writing about a specific open-source project, use that repository’s issue tracker when possible. It keeps technical context public and useful to the next person.

---

<div align="center">

**ISO NORD**  
Independent creative technology from Québec City.

*Build close to the machine. Keep people in control. Make it worth looking at.*

</div>
