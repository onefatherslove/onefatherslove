## Hi there 👋
# OneFathersLove — Development Context & AI Collaboration Layer

## Overview

This repository is part of **OneFathersLove.com**, a dignity-first civic assistance platform designed to help people move from confusion and crisis into clear, immediate action through structured access to public resources.

The system begins in Sacramento (clinic/resource prototype) and is designed to scale nationally.

---

## Working Development Model

This project is being developed through a **multi-AI support workflow**, used to maintain continuity, reduce overload, and accelerate structured implementation.

### AI Collaboration Roles

- **ChatGPT (System Architect)**
  - Overall system design
  - Data pipeline structure (Ingest → Normalize → Rank → Render)
  - UX logic and civic system architecture
  - Accessibility-first enforcement (Section 508)
  - Long-range scalability planning

- **Claude (Implementation Support)**
  - Code refinement and synthesis
  - Structural debugging assistance
  - Alternative implementation approaches

- **Gemini (UX + External Review Layer)**
  - Interface feedback
  - UX critique and alternative reasoning
  - External perspective validation

---

## Core Design Principles

### 1. Dignity-First UX
Users are never treated as broken or deficient.  
The system removes friction and restores agency.

### 2. Portal Psychology Model
UX flow is structured as:

Need → Emotional State → Clarity → Action Readiness → Solution

### 3. Single-Focus Interaction
- One resource at a time
- One primary action per resource:
  - CALL
  - NAVIGATE
  - APPLY
  - VISIT
  - SAVE

### 4. Accessibility by Default
- Section 508 compliance required
- Screen reader compatibility
- Keyboard navigation support
- Mobile-first design

---

## Technical Architecture

- Static-first deployment (GitHub Pages)
- HTML/CSS primary structure
- Minimal JavaScript usage
- No heavy frameworks
- Core Web Vitals optimized

### Data Pipeline

Ingest → Normalize → Rank → Render

All external data sources are normalized into a structured schema before rendering:

```json
{
  "id": "",
  "name": "",
  "location": "",
  "contact": "",
  "services": "",
  "tags": [],
  "urgency_score": 0,
  "primary_action": ""
}


---

UX Constraints

No cognitive overload design

Flip cards preferred over sliders

Returning users skip hero section (localStorage state)

Map and card systems are synchronized

Motion is secondary to clarity and action



---

Current Focus

Sacramento clinic/resource directory (prototype system)

Leaflet map integration

Card-based resource navigation system

Stable API/data rendering pipeline


Known issue:

Clinic rendering pipeline stabilization still in progress



---

Development Philosophy

This project is not treated as a traditional website.

It is treated as:

> A civic guidance system that reduces friction between people and essential services.



The goal is not aesthetic complexity, but functional clarity under real-world constraints.


---

Status

Early-stage public prototype
Active development
Small commit history (intentional early-phase build)


---

Note on Collaboration

This project is intentionally structured for iterative improvement using constrained, step-by-step development. Stability is prioritized over expansion.

One change at a time. One system at a time. One validation at a time.

<!--
**onefatherslove/onefatherslove** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
