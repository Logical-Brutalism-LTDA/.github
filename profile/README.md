<div align="center">

<br />

<a href="https://logicalbrutalism.matheuslacerda.dev">
  <img src="https://logicalbrutalism.matheuslacerda.dev/static/img/logical-brutalism-b2b-design-system-logo-matheus-lacerda.svg" alt="Logical Brutalism" width="76" height="76" />
</a>

# Logical Brutalism

*An engineering initiative dedicated to high-density, server-driven interfaces for B2B software.*

<br />

[Living Spec](https://logicalbrutalism.matheuslacerda.dev) · [Empirical Benchmarks](https://logicalbrutalism.matheuslacerda.dev/benchmarks) · [UI Components](https://logicalbrutalism.matheuslacerda.dev/components) · [llms.txt](https://logicalbrutalism.matheuslacerda.dev/llms.txt)

</div>

---

## The Origin

Somewhere along the last decade, enterprise B2B software adopted the architecture of consumer social networks. Internal dashboards, financial tools, and operational ERPs began shipping over a megabyte of JavaScript, hydrating complex Virtual DOM trees, and running CSS-in-JS engines—just to display tables, filters, and metrics.

At the same time, interface design drifted toward generous whitespace, soft drop shadows, and low-contrast palettes. While visually pleasant on landing pages, these patterns actively slow down operators who read dense data for eight hours a day.

**Logical Brutalism** started from a simple engineering question: *What happens when we strip away client-side framework overhead and decorative noise, and design B2B software strictly around information density, mathematical contrast, and HTML-over-the-wire?*

---

## What We Solve

This organization maintains the specifications, tooling, and empirical research built around three core engineering problems:

### 1. The Virtual DOM & Bundle Tax
Modern SPA stacks force browsers to download, parse, and reconcile massive JavaScript payloads before an operator can interact with a screen. We research and build server-driven architectures—combining **HTMX**, **Alpine.js**, and constrained **Tailwind CSS**—that return rendering responsibility to the server and keep client-side state minimal.

### 2. Low-Density, Ambiguous Interfaces
Operational tools fail when visual hierarchy is left to guesswork. We maintain a parametric design system governed by strict layout grids, monospaced/structural typography, and hard WCAG AAA contrast rules. Every pixel exists to communicate state, never decoration.

### 3. Unverified Performance Claims
Frontend engineering is full of opinions and synthetic benchmarks. Through **CasesLB**, we maintain an open, reproducible Playwright benchmarking lab that measures real cold-load latency under 4x CPU throttling and disabled cache across five production-built dashboards (`Logical Brutalism`, `Mantine`, `Material Design`, `Chakra UI`, and `Ant Design`).

In our audited 30-run suite on identical financial dashboard workloads, moving away from Virtual DOM reconciliation reduced total JavaScript payloads from **516 KB – 1.16 MB** down to **312.54 KB** (mostly Chart.js) and broke the sub-1-second P50 mount barrier (**997.7 ms** vs. **1,382.8 ms – 1,779.1 ms**).

---

## Open Ecosystem

Everything under this organization is open source and documented for both human engineers and AI agents:

| Project / Resource | Purpose |
| :--- | :--- |
| **[Living Spec](https://logicalbrutalism.matheuslacerda.dev)** | The canonical documentation of the axioms, generative principles, and interactive component primitives. |
| **[CasesLB Benchmarks](https://logicalbrutalism.matheuslacerda.dev/benchmarks)** | The reproducible monorepo, Playwright harness, and raw JSON logs comparing server-driven UI against React design systems. |
| **CLI & Scaffolding (`logical-brutalism`)** | Cross-ecosystem tooling published on [PyPI](https://pypi.org/project/logical-brutalism/) and [NPM](https://www.npmjs.com/package/logical-brutalism) to bootstrap governed projects without manual setup. |
| **[Machine-Readable Index](https://logicalbrutalism.matheuslacerda.dev/llms.txt)** | Structured `llms.txt` and `llms-full.txt` specifications designed for direct consumption by AI coding agents. |

---

<div align="center">

Founded and maintained by **Matheus Lacerda Ferreira** · Released under the **MIT License**

</div>
