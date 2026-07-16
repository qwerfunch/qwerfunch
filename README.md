<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)" srcset="./assets/hero-light.svg">
  <img src="./assets/hero-light.svg" width="100%" alt="Jungsoo Kim, Ph.D. — Security R&amp;D Lead researching and building AI agents and autonomous systems">
</picture>

<p align="center">
  <a href="#research-focus">Research Focus</a> ·
  <a href="#flagship-open-system">Flagship</a> ·
  <a href="#related-open-work">Open Work</a> ·
  <a href="#current-research-direction">Research Direction</a> ·
  <a href="#contact">Contact</a>
</p>

I work across **security research** and **software engineering**—from reverse engineering and Android runtime analysis to AI agents, multi-agent architectures, and autonomous systems.

## Research Focus

- **Security R&D** — Reverse engineering, Android security, RASP, and code protection.
- **AI agents** — Multi-agent orchestration, agent architecture, context engineering, and workflow design.
- **Autonomous systems** — Autonomous VAPT, intelligent threat modeling, specification-driven development, and system-level verification.

## Flagship Open System

### [cladding →](https://github.com/qwerfunch/cladding)

**An integrity layer for AI-coded software.**

Before host agents write, cladding supplies the project's intent. After they work, it checks the result for drift, tests, architecture, and evidence. The goal is simple: turn _“done”_ from a claim into something that can be verified.

[Explore cladding](https://github.com/qwerfunch/cladding) · [Read the Ironclad standard](https://github.com/qwerfunch/ironclad)

## Related Open Work

- **[Ironclad](https://github.com/qwerfunch/ironclad)** — A graded standard for provable consistency among specs, code, and tests.
- **[harness-boot](https://github.com/qwerfunch/harness-boot)** — A role-focused multi-agent development harness built around living specifications.
- **[LogcatOn](https://github.com/qwerfunch/logcat-on-releases)** — A high-performance Android logcat viewer for macOS, Windows, and Linux.

## Current Research Direction

> **Research question:** How can autonomous security agents act with enough traceability, containment, and proof to be trusted?

My long-term direction is **Autonomous Defense**: systems that do more than automate a checklist—they observe, reason, act within boundaries, and leave evidence behind.

> _“Exploits are written by code. Defenses should be too.”_

<details>
<summary><strong>Open the lab console</strong></summary>

```text
$ ./research-loop --status

observe      reverse engineering + runtime signals
model        threats + system intent
orchestrate  focused agents
verify       drift + tests + evidence

status       building
side_quest   cosmic-suika
```

Off-duty experiment: **[Cosmic Suika](https://github.com/qwerfunch/cosmic-suika-pages)** — a 3D space-themed merge game with orbital physics.

</details>

## Contact

For research exchange and open-source collaboration: **[qwerfunch@gmail.com](mailto:qwerfunch@gmail.com)**
