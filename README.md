# Christopher Osburn — JADIS

Systems Architect · Software Developer · AI-Assisted Builder

I build systems by starting with the problem and figuring out what actually has to exist to solve it.

I'm a self-taught developer and systems architect working across software architecture, Python, Android/Kotlin, backend systems, developer tooling, automation, AI systems, APIs, and product development.

My background isn't traditional computer science.

Before software, I spent years building things in the physical world through construction, fabrication, renovation, manufacturing, and hands-on problem solving.

The material changed.

The builder mentality didn't.

> Understand the problem. Design the system. Build it. Break it. Prove it. Fix it. Make it useful.

---

## Coding From the Void

> Why are we calling it "Vibe Coding"?
> 
> I'm not vibing.
> 
> I'm architecting systems, solving problems, connecting moving pieces, breaking things, debugging them, testing assumptions, and turning ideas into working software.
> 
> I'm a Systems Architect — coding from the Void.

I use AI aggressively because it dramatically increases how quickly I can research, architect, implement, test, audit, document, and iterate.

That doesn't eliminate engineering responsibility.

Generated code still has to integrate.

Architecture still has to make sense.

Security boundaries still matter.

Tests still have to prove something.

Hardware still has to work on hardware.

And software still has to survive outside the environment where it was generated.

> AI accelerates the work. Responsibility for the resulting system is still mine.

---

## Outer Void

Outer Void is the ecosystem where most of my active software and systems work now lives.

It isn't a monorepo and it isn't one giant application.

It's a federated collection of independent products, developer infrastructure, deterministic engines, Android systems, AI architecture, datasets, automation, and experimental systems designed to interoperate where doing so actually adds value.

The architectural rule is simple:

«Standalone where it makes sense. Integrated where it adds genuine value. No duplicated authority.»

Some projects are public.

Some are proprietary.

Some are internal infrastructure.

Some are products.

They don't need to become the same thing just because they can communicate.

---

## Selected Systems & Products

### BLUX

BLUX is the intelligence and integration architecture at the center of Outer Void's AI work.

The problem I'm trying to solve isn't simply:

> "How do I put an LLM in an application?"

It's:

> How do you build intelligence into real software systems without making the entire system dependent on AI?

BLUX is being built around modular intelligence, explicit capability contracts, deterministic authorities, provider-independent model access, agents, tool execution, structured reasoning, construction and repair, provenance, evaluation, and eventually native BLUX models.

The surrounding architecture includes:

- CogA — deterministic structured reasoning
- cA — deterministic construction and repair
- DAT — independent audit, security, quality, and release verification
- LRC — deterministic repository construction and migration
- GOD — capability and project discovery
- BLUX System — receipts, execution evidence, provenance, and replay
- BluxGPT — provider-independent model transport
- BLUX App — local observability and mission control
- blux10k — reproducible development environment and toolchain

The rule is intentional:

AI provides intelligence. Deterministic systems retain authority where determinism matters.

---

## "blux" + "ax"

Two command-line interfaces expose two different layers of the ecosystem.

### "blux"

Direct access to BLUX intelligence.

### "ax"

The AXIOM developer control plane for routing compatible Outer Void tools, engines, environments, projects, and device capabilities.

In simple terms:

> "blux" is intelligence.
> 
> "ax" is orchestration.

"ax" is deliberately thin. It routes to authoritative systems instead of becoming those systems.

---

## AXIOM Launcher

A custom Android launcher built as a standalone commercial Android product.

AXIOM includes configurable home surfaces, widgets, application management, media integration, system controls, customization infrastructure, and native supporting projects.

The broader AXIOM family includes:

VOID.SYS — native icon infrastructure and standalone icon system.

AXIOM Shooter — standalone native Android game integrated into AXIOM Launcher as a hidden home-screen Easter egg.

BLUX integration is optional by design. The launcher must remain a complete product without AI.

Kotlin · Android · Jetpack Compose · Android SDK

---

## VoidForge

Android-to-Android device engineering infrastructure.

VoidForge is designed to turn an Android device into a capable mobile development, diagnostic, recovery, and service workstation.

The architecture covers:

ADB · Fastboot · Fastbootd · Recovery · Sideload · Logcat · APK/package operations · Files · Terminal workflows · Backup/restore · Flashing · Boot image workflows · Magisk integration

VoidForge remains its own authority over device operations. BLUX can assist, but intelligence does not get to bypass local authorization for destructive actions.

Android · Kotlin · ADB · Fastboot · Termux · Linux

---

## Roughin

Mobile-first contractor software designed around how solo contractors and tradespeople actually work.

Clients. Jobs. Line items. Estimates. Invoices. Photos. Payments. Subscriptions.

The goal is straightforward:

> Build software around the field instead of forcing the field to operate like an office.

FastAPI · PostgreSQL · SQLAlchemy · React · Vite · Stripe · Cloudflare R2 · Docker

---

## Vigyl

Private caregiving and accountability infrastructure built around continuity, not simple reminders.

Vigyl supports private care circles, responsibilities, task assignment, completion, independent verification, status tracking, timelines, and structured follow-through.

The backend and development UI are now both implemented, with the remaining work centered increasingly on deployment, real notification delivery, PostgreSQL qualification, and real-world product validation.

Python · FastAPI · SQLAlchemy · Pydantic · React

---

## TheResolverBot 

Private Telegram moderation and administration infrastructure.

TheResolverBot combines deterministic moderation, authorization boundaries, administrative tooling, diagnostics, subscriptions, deployment infrastructure, and an optional intelligence layer.

The system is intentionally designed so AI can improve moderation intelligence without becoming the authority over security and administrative boundaries.

Python · Telegram · SQLite · Linux · AI Integration

---

## Termux Background

Android companion application and CLI for custom Termux background support, including live reload, opacity control, blur, scrolling animation, dependency detection, and settings preservation.

It's one of my public examples of taking a narrowly defined problem and turning it into a usable tool instead of leaving it as an idea or script.

Java · Android · Termux · CLI · GitHub Actions

---

## Eden Recovery

Not everything I architect is purely software.

Eden Recovery ("/er") is my long-range recovery-system architecture built substantially from lived experience and years of examining addiction, recovery, denial, accountability, treatment culture, homelessness, reintegration, and the gap between getting someone sober and actually rebuilding a life.

It brings together two major systems I've been developing:

### IVRP — Inner Void Recovery Program

A structured recovery curriculum centered on self-awareness, honesty, pattern recognition, accountability, emotional regulation, behavioral change, identity reconstruction, and long-term integration.

### Operation: Restore

A broader restoration model focused on removing the real-world barriers that keep people trapped even after the immediate crisis has passed:

identity · transportation · income · employment · housing · family stability · skills · community · purpose

Eden Recovery is the end-game architecture that brings those pieces together with clinical care, life stabilization, reintegration, housing, work, community, and long-term continuity.

The goal isn't simply getting someone through a program.

> It's rebuilding enough of the person and their environment that recovery has somewhere to live.

"/er" is the internal architecture and planning repository.

"/ivrp" and "/operationrestore" remain their respective public-facing project surfaces.

---

## Developer Infrastructure

A significant amount of my work isn't traditional end-user software.

I build systems that help me build, inspect, test, validate, and operate other systems.

That includes:

- DAT — audit, security, quality, and release verification

- LRC — repository construction, scaffolding, and migration

- GOD — capability and tooling discovery

- CogA — structured deterministic reasoning

- cA — structured construction and repair

- BLUX System — execution provenance and receipts

- blux10k — reproducible development environment/toolchain

- jadis.toolbox — workstation diagnostics and developer utilities

- AXIOM CLI ("ax") — ecosystem control plane

Some are useful independently.

Together they form a larger interoperable engineering environment without requiring everything to collapse into one framework.

---

## What I Work With

### Languages

Python · Kotlin · Java · JavaScript/TypeScript · SQL · Shell/Bash · HTML/CSS

### Backend

FastAPI · SQLAlchemy · SQLite · PostgreSQL · REST APIs · Authentication/Authorization · Pydantic

### Android

Kotlin · Java · Jetpack Compose · Android SDK · ADB · Fastboot · Android System Integration

### Frontend

React · Vite · HTML · CSS · Progressive Web Applications

### Infrastructure

Linux · Termux · Git · GitHub · Docker · CI/CD · GitHub Actions · VPS/Cloud Deployment

### Integrations

AI/LLM APIs · Stripe · Cloudflare R2 · Telegram APIs · External Service APIs

### Engineering

System Architecture · AI-Assisted Engineering · Rapid Prototyping · Backend/API Development · Android Development · Debugging · Testing · Automation · Repository Engineering · Technical Documentation · Integration Engineering

---

## How I Build

I don't begin with:

> "What framework should I use?"

I begin with:

> "What actually needs to exist?"

Then:

1. Understand the actual problem.
2. Determine system boundaries and authority.
3. Identify the moving pieces.
4. Design the smallest architecture capable of supporting the real objective.
5. Build it.
6. Test it.
7. Break assumptions.
8. Find the weak points.
9. Fix them.
10. Integrate the pieces.
11. Prove the important paths.
12. Keep improving it until it is genuinely useful.

One principle has become particularly important across Outer Void:

> Build the system. Prove the system. Then remove the scaffolding.

I don't consider a green test suite proof that a product works if the actual requirement hasn't been exercised.

---

## AI-Assisted Engineering

I don't hide the fact that AI is deeply integrated into my development workflow.

I use it for:

Research → Architecture → Implementation → Analysis → Debugging → Testing → Auditing → Documentation → Iteration

What interests me isn't how much code a person can manually type.

I'm interested in how much working system a person can understand, architect, build, validate, and maintain.

AI dramatically changes the amount of implementation one person can attempt.

It does not change who is responsible for deciding whether the result is actually correct.

That's the part I care about.

---

## Current Direction

I'm currently focused on:

Systems Architecture · AI-Assisted Engineering · Android Development · Backend/API Development · Developer Infrastructure · Automation · AI Systems · Rapid Product Development

I'm also continuing the long-term development of the Outer Void ecosystem, BLUX native intelligence, and Eden Recovery architecture.

For professional work, I'm interested in:

Remote Development · Contract Engineering · Systems Architecture · AI-Assisted Development · Rapid Prototyping · MVP Development · Automation · Backend/API Work · Android Development · Developer Tooling

I'm particularly interested in difficult problems where the requirement isn't simply:

> "Write this code."

It's:

> "Figure out what needs to exist, then make it work."

---

## Contact

**Christopher Osburn — JADIS**

Email: theoutervoid@outlook.com

Personal GitHub: @Justadudeinspace

Organization: @Outer-Void

---

> I build systems.
> 
> Some start as software.
> 
> Some start as problems nobody has solved the way I think they should be solved.
> 
> Either way, I want to find out what happens when I build the thing that I think should exist.
