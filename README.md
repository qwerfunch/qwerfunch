<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)" srcset="./assets/hero-light.svg">
  <img src="./assets/hero-light.svg" width="100%" alt="Jungsoo Kim, Ph.D. — Security R&amp;D Lead">
</picture>

<p align="center">
  <a href="#research-program">Research Program</a> ·
  <a href="#work">Work</a> ·
  <a href="#focus">Focus</a> ·
  <a href="#elsewhere">Elsewhere</a> ·
  <a href="#contact">Contact</a>
</p>

I lead security R&D—reverse engineering, Android runtime analysis, RASP, code protection—and build autonomous systems on the other side of that work. Increasingly they are the same problem.

## Research Program

> **The question.** How can an autonomous system—one that writes code, or one that defends it—act with enough traceability, containment, and proof to be trusted?

**The bet.** Define consistency precisely enough that it can be falsified. Build something that enforces it mechanically. Then ship real software under it and see whether it holds.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/stack-dark.svg">
  <source media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)" srcset="./assets/stack-light.svg">
  <img src="./assets/stack-light.svg" width="100%" alt="Ironclad, the standard — first L4 implementation — cladding, the enforcer — built and shipped through it — LogcatOn, the product">
</picture>

Three artifacts, one argument. A standard nobody applies proves nothing—so **cladding** implements **Ironclad** and runs the gate on itself, and **LogcatOn** is a real product that went out through it.

> _"Exploits are written by code. Defenses should be too."_

## Work

### [cladding](https://github.com/qwerfunch/cladding)

**An integrity layer for AI-coded software.** Before an agent writes, cladding supplies the project's intent. After it works, cladding checks the result against the spec—drift, tests, architecture, evidence. It runs the same gate on itself.

<sub>Open source · TypeScript · works with Claude Code, Codex, Gemini, Antigravity, and Cursor</sub>

### [LogcatOn](https://qwerfunch.github.io/logcat-on-releases/)

**Pick your app—the noise disappears.** Bind to a package and LogcatOn follows its PID, re-binding on its own when the app restarts. Crashes, ANRs, native faults, and lifecycle events surface as signals rather than text, and sessions stay smooth well past a million lines.

As more Android code gets written by agents, the log is where you find out what the app actually did.

<sub>Desktop app · macOS, Windows, Linux · free · [Releases](https://github.com/qwerfunch/logcat-on-releases/releases)</sub>

### [Ironclad](https://github.com/qwerfunch/ironclad)

**A graded standard for falsifiable consistency among spec, code, and tests.** Four levels, from static checks to human-in-the-loop audit—each one attemptable only once the level below it has passed.

<sub>Draft · MIT · first L4 implementation: cladding</sub>

## Focus

- **Security R&D** — Reverse engineering, Android security, RASP, and code protection.
- **AI agents** — Multi-agent orchestration, agent architecture, context engineering, and workflow design.
- **Autonomous systems** — Autonomous VAPT, intelligent threat modeling, specification-driven development, and system-level verification.

## Elsewhere

- **[harness-boot](https://github.com/qwerfunch/harness-boot)** — A role-focused multi-agent development harness built around living specifications.
- **[Cosmic Suika](https://github.com/qwerfunch/cosmic-suika-pages)** — Off-duty: a 3D space-themed merge game with orbital physics.

## Contact

For research exchange and open-source collaboration: **[qwerfunch@gmail.com](mailto:qwerfunch@gmail.com)**
