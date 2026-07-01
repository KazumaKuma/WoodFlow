---
Project: WoodFlow
Document: ADR-001 – Technology Stack
Version: v0.1.0
Status: Active
Author: Kazuma
Created: 2026-07-01
Last Updated: 2026-07-01
---

## Context

WoodFlow is designed as an offline-first application for woodworking businesses.
The application must be easy to maintain, cross-platform, responsive and suitable for future expansion.

The project should also provide a modern development experience while keeping the technology stack stable and well supported.

## Decision

The following technology stack has been selected:

- React
- TypeScript
- Vite
- Progressive Web App (PWA)

Future technologies may be added as required, but the initial project foundation will remain intentionally lightweight.

## Rationale

The selected stack provides:

- Excellent developer experience
- Strong TypeScript support
- Large community
- Excellent compatibility with AI-assisted development (Codex)
- Fast build times
- Cross-platform deployment
- Offline capability through PWA technologies

## Consequences

### Positive

- Modern and maintainable architecture
- Runs on desktop, tablet and mobile devices
- No dedicated backend required for the first versions
- Easy future expansion

### Negative

- Initial learning curve for React and TypeScript
- Native device integration requires additional implementation if needed

---

**Decision Owner**

Kazuma Kuma