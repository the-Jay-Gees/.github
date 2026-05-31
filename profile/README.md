### The Jay Gees ft: Spoonie Helper & the Local‑First Disability Tech Stack
Welcome to The Jay Gees, a small but loud collective of pipeline rats, code genies, and disabled makers building tools that center accessibility, autonomy, and community.
The name JG started as jeangenie — a nod to the David Bowie song The Jean Genie — and evolved into a whole identity: the Jay Gees, the genies in the machine, the rats in the pipes, the people who build what we need because nobody else will.

This org is home to the Spoonie Helper project and the experimental infrastructure that powers it, including ROCm‑based local AI training, domain‑scraping tools, and accessibility‑first design patterns.

### ✨ Mission
We build local‑first, privacy‑respecting, accessibility‑centered tools for disabled people — especially spoonies, Deaf/DeafBlind folks, neurodivergent people, and anyone who needs tech that doesn’t treat them as an afterthought.

Our work is grounded in disability justice and the legacy of Camp Jened.

    “For we are leaders of inclusiveness and community, of love, equity, and justice.”  
    — Judith Heumann

This quote guides Jened the Spoon, the philosophy behind Spoonie Helper and the Jay Gees:
we build for each other, with each other, and we build access into the foundation.

### 🧬 Project History
A narrative timeline of how this org came to be.
Phase 0 — Domain Scout

The very first experiment: a domain‑ranking tool that prioritized community‑owned, disabled‑owned, and BIPOC‑owned domains.
It introduced the community‑first scoring system that still influences our work today.
Phase 1 — Vendor Finder / AccessiFind

Domain Scout evolved into a vendor‑discovery tool for assistive tech, mobility aids, sensory tools, and disability‑owned shops.
This phase proved that disabled‑centered search is both possible and necessary.
Phase 2 — Runbook Experiments

We built personal runbooks for chronic illness management, troubleshooting routines, and symptom tracking.
This became the backbone of Spoonie Helper’s structure.
Phase 3 — Spoonie Helper (Current)

The flagship project.
A local‑first, accessibility‑first toolkit for spoonies to manage routines, resources, and self‑care workflows.
Phase 4 — Local AI Infrastructure (Ongoing)

To support offline use, we built ROCm‑based training pipelines for QLoRA and PyTorch on consumer AMD GPUs.

Public repos include:

    ROCm 7700XT QLoRA Training  
    https://github.com/thejeangenie18/rocm-7700xt-qlora

    ROCm 7700XT PyTorch Environment  
    https://github.com/thejeangenie18/rocm-7700xt-pytorch

These repos power the local inference and fine‑tuning experiments behind Spoonie Helper.

### 🥄 Spoonie Helper
What it is:

A local‑first assistant for chronically ill and disabled people.
It helps manage:

    routines

    symptom logs

    escalation steps

    resource lists

    accessibility‑friendly workflows

    offline‑capable AI helpers

What it stands for

    Local‑first: your data stays on your device

    Accessibility‑first: built for Blind, DeafBlind, spoonie, and neurodivergent users

    Community‑first: shaped by disabled people, not corporations

    Privacy‑first: no analytics, no silent network calls

### 🧩 Key Principles
Local‑First Architecture

    No silent network calls

    No cloud dependencies unless explicitly enabled

    Offline‑capable AI models

    User‑controlled backups and sync

Accessibility as a Hard Requirement

    DeafBlind‑standard alt text

    Screen‑reader‑first structure

    Keyboard‑only navigation

    High‑contrast and low‑cognitive‑load design

    Plain‑language documentation

Open Source, But Not Open Season

We welcome contributions — but accessibility, privacy, and community safety come first.

### 📦 Repositories in This Org (Work in Progress)
Spoonie Helper (Flagship)

Local‑first disability‑tech assistant.
Domain Scout (Archive)

The original domain‑ranking engine.
AccessiFind / Vendor Finder (Archive)

Assistive‑tech vendor discovery tool.
ROCm AI Training Repos (External but Related)

Maintained under the founder's personal account:

    https://github.com/thejeangenie18/rocm-7700xt-qlora (github.com in Bing)

    https://github.com/thejeangenie18/rocm-7700xt-pytorch (github.com in Bing)

### 👤 About the Maintainer
I’m Jillian, a Deaf, neurodivergent, Disabled, non‑traditional coder building the tools I wish existed.
I work local‑first because disabled people deserve privacy.
I build accessibility‑first because disabled people deserve dignity.
I build community‑first because we deserve each other.

### 🚀 Getting Started
Clone the flagship project:
bash

git clone https://github.com/the-Jay-Gees/spoonie-helper.git
cd spoonie-helper

Documentation lives in the /docs folder.
Local‑first mode is enabled by default.

### 🤝 Contributing
See the full CONTRIBUTING.md below.
Accessibility is not optional here — it is the foundation.
CONTRIBUTING.md
Contributing to The Jay Gees Projects

Thank you for wanting to contribute.
This project is built by and for disabled people, and contributions must uphold that purpose.

### 🧭 Core Values

    Accessibility is mandatory

    Privacy is mandatory

    Local‑first design is mandatory

    Community safety is mandatory

    Disabled people lead the direction of the project

### 🥄 Jened the Spoon — Our Guiding Philosophy

    “For we are leaders of inclusiveness and community, of love, equity, and justice.”  
    — Judith Heumann

This quote guides the Jay Gees.
Every contribution must reflect these values.

###🔒 Mandatory Accessibility Standards

DeafBlind‑Standard Alt Text

All images must include:

    literal transcription of visible text

    description of layout and relationships

    description of purpose

    no interpretation or filler

Screen‑Reader‑First Structure

All UI and docs must use:

    correct heading hierarchy

    semantic HTML

    ARIA roles when appropriate

    logical focus order

    no visual‑only indicators

Keyboard‑Only Navigation

All interactive elements must be fully operable without a mouse.

Plain‑Language Documentation

Write clearly, directly, and accessibly.

Local‑First Data Handling
No silent network calls.
No cloud dependencies without explicit opt‑in.

### 🧪 Pull Request Checklist

Before submitting a PR:

    [ ] All images have DeafBlind‑standard alt text

    [ ] Screen‑reader semantics validated

    [ ] Keyboard navigation tested

    [ ] Documentation is plain‑language

    [ ] No violations of local‑first policy

    [ ] Tests pass

    [ ] PR description is clear and scoped

### 🐛 Reporting Accessibility Issues

Open an issue with:

    steps to reproduce

    expected vs actual behavior

    environment details

### Accessibility issues are treated as critical.
❤️ Thank You

Your contributions help build a future where disabled people have tools made for us, not around us.
