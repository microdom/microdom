<p align="center">
  <img src="https://microdom.dev/og-image.svg" width="90%" alt="MicroDOM">
</p>
<p align="center">
  Build fast interfaces with plain HTML, CSS and JavaScript.<br>
  No build step. No dependency chain. No class soup.<br>
  <a href="https://microdom.dev">microdom.dev</a> · <a href="https://www.npmjs.com/org/microdom">npm: @microdom</a>
</p>

---

**AI can generate code. Humans still need to understand it.**
MicroDOM is a family of small, readable front-end tools that share one mental
model — the `µ(...)` call — so what you learn in one module carries to the next.
Media sites, blogs, catalogues, portfolios: none of them is an app.
None of them needs a framework. A handful of bytes will do.

## The ecosystem

| Tool | What it does | Install | Status |
|------|--------------|---------|--------|
| **Mode JS** | DOM manipulation with the smallest possible surface | `npm i @microdom/mode` | Stable |
| **Mode CSS** | Class-less styling that lets the cascade work for you | `npm i @microdom/mode.css` | Beta |
| **Mode Router** | A tiny SPA router — no opinions you didn't ask for | — | In development |
| **Mode Bind** | Reactive binding. Granular updates, no virtual DOM | — | In development |
| **Mode Move** | Transitions and motion, chained through the same `µ(...)` call — ships with the core | `@microdom/mode/move` | In development |
| **Mode DB** | A JSON database living in the browser's storage | — | In development |

## Why "Mode"?

MicroDOM is the ecosystem; **mode.*** are its modules. One naming convention,
one mental model — predictable enough that even an AI can guess what the next
module is called. That's by design: readable for bots *and* humans.

## See it in action

**[Mode CSS demo →](https://microdom.dev/mode-css/demo/)** — a full landing page
where every block ships with the exact HTML + CSS that renders it.

---

<sub>MIT licensed · Made in Buenos Aires · The web has a weight problem — we're
part of the diet: an analysis of the 10,000 most-visited pages (Aalto University,
ACM 2025) found over half of what the web ships could be deleted with nothing
the reader came for lost.</sub>
