<div align="center">
  <img src="assets/tokey.svg" alt="Tokey" width="420" />
  <h1>Tokey — Issue Tracker</h1>
  <p>Bug reports &amp; feature requests for the Tokey platform</p>
</div>

---

**Tokey** is an LLM inference simulator — a tool for experiencing what different hardware and network configurations actually feel like when streaming tokens. You can compare a Raspberry Pi against an H100, a cloud API against a local GPU, or a reasoning model's long TTFT against a snappy consumer card, all without touching real hardware.

This repository is the issue tracker for the platform. There is no code here. If something is broken or you have an idea, open an issue and use one of the templates — they keep reports consistent and make triage faster.

👉 [Open an issue](../../issues/new/choose)

## Samples

The [`samples/`](samples/) directory contains the simulator's built-in configurations as plain YAML, in case you want to reference them, fork them, or understand what drives a particular preset.

**[`samples/presets/`](samples/presets/)** — The 11 named presets available in the UI, covering GPUs (RTX 3070 through H200), cloud APIs, CPU inference (Pi 5, i7-13700K, Threadripper), bad network conditions, and thinking models. Each file contains the full `SimulationConfig`: tokens per second, TTFT, jitter, prompt and completion length, cadence batching, and stall settings.

**[`samples/harnesses/`](samples/harnesses/)** — The five content harnesses used to drive the simulator: code generation (a multi-turn Go task engine implementation), creative writing (a Paris short story), emails & business communication, conversational chat (a TypeScript walkthrough), and the custom harness placeholder. Each file contains the full multi-turn stage content — prompts, thinking text, and response text — exactly as used in the app.

## Security

Do not file security vulnerabilities as public issues. See [SECURITY.md](SECURITY.md) for responsible disclosure.
