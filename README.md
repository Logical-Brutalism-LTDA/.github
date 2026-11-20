# Logical Brutalism

Parametric, server-driven UI architecture and design system engineered for high-density B2B software.

Logical Brutalism eliminates client-side Virtual DOM reconciliation overhead by pairing deterministic HTML-over-the-wire primitives with strict typographic and WCAG AAA contrast constraints.

## Core Stack
- **Server-Driven Hypermedia:** HTMX + FastAPI / Django
- **Micro-Reactivity:** Alpine.js
- **Styling & Layout Constraints:** Tailwind CSS + CSS Custom Properties
- **CLI & Scaffolding:** Available on PyPI and NPM (`logical-brutalism`)

## Empirical Benchmarks (CasesLB)
Validated across 30 cold-load runs under 4x CPU throttling against Mantine, Material Design (MUI), Chakra UI, and Ant Design:
- **Bundle Footprint:** 312.54 KB JS (vs. 516 KB – 1.16 MB in React ecosystems)
- **P50 Mount Latency:** 997.7 ms (the only tested stack breaking the sub-1s barrier under throttling)

## Ecosystem
- **Spec & Live Docs:** [logicalbrutalism.matheuslacerda.dev](https://logicalbrutalism.matheuslacerda.dev)
- **Benchmarks:** [logicalbrutalism.matheuslacerda.dev/benchmarks](https://logicalbrutalism.matheuslacerda.dev/benchmarks)
- **LLM Index:** [logicalbrutalism.matheuslacerda.dev/llms.txt](https://logicalbrutalism.matheuslacerda.dev/llms.txt)
