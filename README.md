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

I lead **security R&D** and research **AI** alongside it.

> _"Exploits are written by AI agents. Defenses should be too."_

## Research Program

The AI question I keep returning to is a plain one: **how do people get genuinely useful work out of it?**

Speed turned out to be the easy part. Knowing whether what came back is right is not—so verification is where I started.

**The approach.** Write the intent down precisely enough that a machine can check it. Build the checker. Then ship real software through it and find out whether it holds.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/stack-dark.svg">
  <source media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)" srcset="./assets/stack-light.svg">
  <img src="./assets/stack-light.svg" width="100%" alt="Ironclad, the standard — first L4 implementation — cladding, the enforcer — built and shipped through it — LogcatOn, the product">
</picture>

Three artifacts, one argument. A standard nobody applies proves nothing—so **cladding** implements **Ironclad** and runs the gate on itself, and **LogcatOn** is a real product that went out through it.

That is one answer to one part of the question. The rest is still open.

## Work

### [Ironclad](https://github.com/qwerfunch/ironclad)

**A graded standard for falsifiable consistency among spec, code, and tests.** Four levels, from static checks to human-in-the-loop audit—each one attemptable only once the level below it has passed.

<sub>Draft · MIT</sub>

### [cladding](https://github.com/qwerfunch/cladding)

**An integrity layer for AI-coded software.** Before an agent writes, cladding supplies the project's intent. After it works, cladding checks the result against the spec—drift, tests, architecture, evidence. It runs the same gate on itself.

<sub>Open source · TypeScript · works with Claude Code, Codex, Gemini, Antigravity, and Cursor</sub>

### [LogcatOn](https://qwerfunch.github.io/logcat-on-releases/)

**The log is where you find out what an app actually did**—and as more of the code is written by agents, that matters more. LogcatOn makes it legible: bind to a package and it follows the PID, re-binding on its own when the app restarts. Crashes, ANRs, and native faults land on the minimap and timeline the moment they happen, one click from the line that caused them, and sessions stay smooth into the hundreds of thousands of lines.

<sub>Desktop app · macOS, Windows, Linux · free · [Releases](https://github.com/qwerfunch/logcat-on-releases/releases)</sub>

## Focus

- **Security R&D** — VAPT, reverse engineering, Android runtime analysis, RASP, and code protection.
- **AI** — Multi-agent orchestration, agent architecture, context engineering, workflow design, and specification-driven verification.

## Elsewhere

- **[harness-boot](https://github.com/qwerfunch/harness-boot)** — A role-focused multi-agent development harness built around living specifications.
- **[Cosmic Suika](https://github.com/qwerfunch/cosmic-suika-pages)** — Off-duty: a 3D space-themed merge game with orbital physics.

## Contact

For research exchange and open-source collaboration: **[qwerfunch@gmail.com](mailto:qwerfunch@gmail.com)**
