<a href="https://mayanksahu.dev/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
    <img alt="Mayank Sahu — High-trust systems built to survive an unpredictable machine age." src="./assets/hero-light.svg" width="100%">
  </picture>
</a>

<p align="center">
  <a href="https://mayanksahu.dev/">mayanksahu.dev</a> &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/mayank-sahu-89ba67325">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:108mayanksahu@gmail.com">108mayanksahu@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://github.com/msnotfound/msnotfound.github.io/tree/main/papers">Research</a>
</p>

I build low-level process supervisors, local-first WebAssembly engines, and reliable distributed backends—focused on explicit invariants over black-box abstractions. Studying Data Science & AI at **IIIT Naya Raipur** (`2024 – 2028`).

---

### Selected Systems

<table>
<tr>
<td width="50%" valign="top">

**[Fleetorch](https://github.com/msnotfound/fleetorch)** — `Go`

Multi-agent process supervisor across isolated Git worktrees. Sub-15ms bootstrap latency, cross-platform `ConPTY` / `POSIX PTY` multiplexing, and lock-free bounded ring buffers.

</td>
<td width="50%" valign="top">

**[Mnemium](https://github.com/msnotfound/mnemium)** — `WASM · TypeScript · Go`

Local-first AI memory engine. `sqlite-vec` compiled to WebAssembly with zero-copy IPC (`< 12ms` 768-dim search), SSE stream capture, and hybrid BM25 + SLM retrieval.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[HookGuard](https://github.com/msnotfound/hookguard)** — `Node.js · PostgreSQL · Redis`

Webhook ingestion and delivery gateway using the Transactional Outbox pattern, pre-flight DNS SSRF mitigation, HMAC-SHA256 / AES-256-GCM, and a Failure Lab chaos harness.

</td>
<td width="50%" valign="top">

**[Draftdeckai](https://github.com/msnotfound/Draftdeckai)** — `TypeScript · 79 ★`

Open-source AI document creation platform that turns natural-language prompts into structured resumes, presentations, and CVs.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[GhostSignal](https://github.com/msnotfound/ghostsignal)** — `Midnight ZK · TypeScript`

Verifiable AI trading-signal protocol using zero-knowledge proofs and SHA-256 commit-reveal primitives for sub-second trade attestations without exposing weights.

</td>
<td width="50%" valign="top">

**[Tropicam](https://github.com/msnotfound/tropicam)** — `Python`

Deterministic, CPU-only, training-free event-vision engine operating over the tropical (max-plus) semiring.

</td>
</tr>
</table>

<details>
<summary>Archive — additional systems &amp; prototypes</summary>
<br>

| Project | Stack | Notes |
| --- | --- | --- |
| **[rl-emergency-traffic-control](https://github.com/msnotfound/rl-emergency-traffic-control)** | `Python` `PPO` `SUMO` | Deep-RL traffic-signal control prioritizing emergency vehicles (~70% faster ambulance travel) |
| **[structura](https://github.com/msnotfound/structura)** | `Python` | Floor-plan analysis with IS 456:2000 design checks, 3D visualization, and cost estimation |
| **[syntra](https://github.com/msnotfound/syntra)** | `TypeScript` | B2B intelligence delivery suite |
| **[RetroShare](https://github.com/msnotfound/RetroShare)** | `Next.js` `AWS S3` | Ephemeral file sharing via 6-character codes |
| **[academic-helper](https://github.com/msnotfound/academic-helper)** | `TypeScript` `Ollama` | Local RAG study assistant with ChromaDB |

</details>

---

### Applied Research

- **[Phantom: A Middleware Layer for Cost-Amortized Agentic Desktop Automation](https://github.com/msnotfound/msnotfound.github.io/blob/main/papers/phantom.md)** — Compiles single demonstrations into parameterized execution graphs dispatched via AT-SPI with local `all-MiniLM-L6-v2` fallback (`$0` per-replay cost, break-even at $N^* = 1$).
- **[Semantic Artifact Navigation (SAN)](https://github.com/msnotfound/msnotfound.github.io/blob/main/papers/san-swg.md)** — Formalizing coordinate-free interaction with computational workbooks.

---

### Stack

`Go` · `Rust` · `TypeScript` · `Python` · `C++` · `PostgreSQL` · `WebAssembly` · `POSIX PTY / ConPTY` · `Linux cgroups v2` · `sqlite-vec` · `Redis / BullMQ` · `Blake3 CAS`
