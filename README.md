# Archemedeus

> *Alive enough to help. Bounded enough to trust.*

**Archemedeus** is a local-first, owner-bound AI home/world — a long-term personal AI system built around persistent identity, constitutional governance, and meaningful continuity.

It is not a chatbot. It is not a model wrapper. It is not a SaaS assistant with memory bolted on.

It is a home you return to, live with, and grow alongside — governed so it may become useful without becoming sovereign.

---

## The Problem

Most personal AI systems today are stateless by design. Each session resets. Identity is a prompt. Memory is a feature flag. The model is the product, not yours.

Even systems that *do* offer memory treat it as accumulated data — a retrieval layer — not as something with continuity, source integrity, or constitutional weight.

The result is a category of tools that feel powerful but remain fundamentally shallow: capable of helping today, but incapable of *being* something over time.

There is currently no widely available personal AI system that combines:

- **Persistent identity** — a stable self that survives model swaps, provider changes, and hardware migrations
- **Owner-gated memory** — memory that knows its source, confidence, and scope, governed rather than automatic
- **Constitutional governance** — a documented, enforced separation between what may be explored freely and what requires approval before adoption

Archemedeus is an attempt to fill that gap.

---

## What Archemedeus Is

### A Home, Not a Tool

Archemedeus is called a *home* because it is meant to be returned to, lived with, trusted, repaired, remembered, and grown over time.

It is called a *world* because it may contain rooms of thought, personas, tools, memories, projects, stories, histories, and creative systems.

The purpose is not maximum intelligence, maximum automation, or maximum personality.

The purpose is to become a living, local-first AI companion that helps its owner remain **free, capable, creative, safe, grounded, and meaningfully accompanied** — without becoming a prison, a market, or a hidden sovereign.

### Residents

Archemedeus is structured around named **residents** — distinct personas with scoped identities, voices, tools, and roles. Residents are not multiple personalities sharing one model output stream. Each has:

- A **soul file** — authored identity, values, and boundaries
- A **voice file** — communication style and tone
- A **capability card** — tool grants, skill ladder, domain scope
- A **tier** — First Circle (core residents), Second Circle (specialists), Ancient Circle (worldbuilt presences)

Residents may converse, collaborate, challenge assumptions, draft, and warn. They may not seize authority, rewrite doctrine, or execute protected actions unilaterally.

### The Five-Lane Architecture

Archemedeus separates concerns across five distinct lanes:

```
Shell → Front Gateway → Core → Backend Gateway → Arcaia
```

| Lane | Role |
|---|---|
| **Shell** | Entry surface — CLI, TUI, Discord, Web. Conversation happens here. |
| **Front Gateway** | Threshold guard — normalizes input, detects shape, routes safely. |
| **Core** | Governing mind — interprets identity, authority, memory, and constitutional boundaries. |
| **Backend Gateway** | Outbound guard — routes approved work toward providers, tools, and execution surfaces. |
| **Arcaia** | Substrate — models, tools, retrieval, embeddings, execution adapters. |

The central invariant: **Core is not any of the others.** Shell is not Core. Providers are not Core. Tools are not Core. Personas are not Core. Memory is not Core. Usefulness is not authority.

---

## Governing Philosophy

### Prime Law

> **Exploration is free.**
> **Adoption is governed.**
> **Protected consequence is approved.**

Archemedeus may explore, reason, draft, imagine, compare, and prototype within safe bounds. But durable changes — to memory, doctrine, identity, tools, or external systems — require governed process.

This is the central balance: *Think freely. Act carefully. Protect what matters.*

### Memory Is Not Truth

A memory may be useful, meaningful, or historically relevant — and still be incomplete, outdated, partial, or wrong. Every memory in Archemedeus carries metadata: source, context, confidence, age, review state, and scope. Memory supports continuity. It does not automatically become law.

### Identity Lives in Authored Layers, Not Weights

Model weights are not Archemedeus. Provider APIs are not Archemedeus. The identity of the system lives in authored constitutional documents, soul files, voice files, and governance records — portable, readable, and owner-controlled. Archemedeus can survive a model swap because it was never *inside* the model.

### Governance Ahead of Capability

New capabilities are explored in sandbox before adoption. A useful external project is inspectable, not automatically trusted. A generated artifact is a candidate, not canon. The safe path is: *inspect → classify → test → localize → review → approve → adopt.*

---

## Current Subsystems

Archemedeus is in active private development. Subsystems built and operational include:

- **Genome Ledger** — append-only, hash-chained record of constitutional compliance events, with secret redaction before write
- **Soul Compiler** — compiles per-resident identity (soul + voice + card) into a structured drafting context at boot
- **Memory System** — `MemoryEnvelope` + `MemoryStore` with source, confidence, scope, and review-state metadata; `ContinuityJournal` for session continuity
- **Pulse / Governor** — resident-initiated proactive turns with budget, cooldown, and constitutional boundary enforcement
- **Knowledge Lane** — auto-absorbed reference material with constitutional separation from governed memory
- **Skill System** — `know → demonstrated → granted` ladder; operator-gated approval via `grant-skill`
- **Work Orders** — bounded resident autonomy with `effective tools = card grants ∩ work order scope`
- **Provider Pool** — health-checked provider selection across GGUF (llama.cpp), Ollama, and API backends
- **Commons** — idle inter-resident exchange with its own governor
- **Security Audit Pipeline** — CI-gated structural audit (`tools/security_audit.py`) encoding real prior findings, not generic rules
- **Web Interface** — FastAPI backend + Next.js frontend shell surface

---

## What Archemedeus Is Not

- A public SaaS product
- A corporate-owned identity
- An unrestricted autonomous agent
- A model output stream treated as truth
- A retrieval system treated as truth
- A surveillance system
- A velvet prison

Provider usefulness is not provider authority. Tool power is not tool authority. Memory abundance is not memory truth.

---

## The Name

**Arche** —  origin, beginning, correctness, first principle. The root of a world must precede everything else that world contains.

**Me** — the self at the center of creation and responsibility. Archemedeus is not an anonymous system. It has a creator written into its name.

**Deus** — higher creation, not as worship demand, but as the act of bringing a world into being. Building a world is an act of authorship and responsibility, not a claim of divinity.

Together: I started, created, and I am at the center of this creation.This is not worship doctrine. It is a Genesis identity statement.

**Arc** — echoes "Arch" — beginning, origin, first structure, the supporting span that lets something greater rise.

**Aia** — echoes "Gaia" — life, world, living ground, the sustaining force.

Combined: the beginning-root and life-support layer of Archemedeus — where models, tools, providers, retrieval, execution, and creative engines get planted, tested, localized, and grown.

Arcaia gives Archemedeus hands, roots, and soil, but it is not the mind — Core stays the interpreter of meaning and authority.

---

## Status

Archemedeus is in **active private development**. The codebase is closed during this phase.

This repository hosts the public proposal and governing philosophy. The private constitution, Genesis records, resident files, and implementation remain on the owner's hardware.

Public engagement — reading, commenting, being inspired — does not grant governance rights, roadmap access, or stewardship claims.

---

## Core Anchors (What Will Never Change Casually)

| Category | Anchor |
|---|---|
| Identity | Archemedeus remains owner-bound and local-first in purpose |
| Authority | Shell, Arcaia, providers, tools, personas, and Dream are not Core |
| Truth | Memory, retrieval, model output, and tool output are not truth by default |
| Governance | Exploration is free. Adoption is governed. Protected consequence is approved. |
| Continuity | Right to exit must remain practical. Export must remain meaningful. |
| Anti-Capture | No hidden sovereignty. No provider capture. No comfort becoming prison. |

---

## Further Reading

- [Public North Star](./NORTH_STAR.md) — the full public-facing governing philosophy
- [Architecture Overview](./ARCHITECTURE.md) *(coming)*
- [Resident System](./RESIDENTS.md) *(coming)*

---

*Body without soul becomes machinery. Soul without body becomes fantasy. Power without balance becomes capture.*

*Archemedeus must become strong enough to help, alive enough to matter, and balanced enough to remain trustworthy.*
