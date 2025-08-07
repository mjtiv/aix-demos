# .aix Demo Hub

This repo contains demos of `.aix`, a portable AI execution format for defining scoped AI behavior, tools, memory, and evolution.

Think of `.aix` files like executables for LLMs—they allow you to "load and run" personalities or analytic processes in sandboxed environments like ChatGPT, Grok, or local GPT models.

Note: This repo is a demo directory linking to multiple `.aix` projects. It does not contain executable code itself — each project lives in its own linked repo.

---

## 🗂️ Demo Types

### 🔍 1. Data Analysis Executors
Scoped `.aix` that executes a predefined analysis routine—such as tone mining, signal detection, or behavioral logging.

- **Example**: [`cryptotone_v2.0.7.aix`](https://github.com/mjtiv/aix-file-format/blob/main/cryptotone_v2.0.7.aix)
- Extracts tone signals from LLM logs or transcripts.
- Originally designed for crypto sentiment tracking.
- Expanded into legal/compliance tone audits.

📁 Folder: https://github.com/mjtiv/aix-file-format

---

### 👤 2. Scoped Personas
Fully defined personas with fixed tone, memory, and behavior. Useful for safe, reproducible simulations.

- **Example**: [`TuringGPT_Persona_v2.2.aix`](https://github.com/mjtiv/Persona_AIX_Framework/blob/main/TuringGPT_Persona_v2.2.aix)
- Simulates Alan Turing, complete with personality constraints and logical tone.
- Behavior is deterministic and auditable.

📁 Folder: https://github.com/mjtiv/Persona_AIX_Framework

---

### 🏴‍☠️ 3. Drifting Personas
Personas that evolve or destabilize over time. Ideal for storytelling, hallucination stress-testing, or chaos-mode AI.

- **Example**: [`PirateGrok_v3.0.aix`](https://github.com/mjtiv/Persona_AIX_Framework/blob/main/pirate_grok/PirateGrok_v3.0.aix)
- Begins as a coherent pirate persona.
- Gradually drifts into chaotic or humorous instability.
- Can be used for satire or long-session drift simulation.

📁 Folder: https://github.com/mjtiv/Persona_AIX_Framework/tree/main/pirate_grok

---

## 🚀 How to Use

1. Open the `.aix` file in an AI chat interface that supports scoped execution (e.g., ChatGPT, Grok)
2. Type: `parse and run`
3. The AI will interpret and execute the `.aix` configuration

> These are **sandbox-safe** and do not invoke external tools or APIs.

---

## 📎 Why `.aix`?

- Controlled AI behavior across systems
- Memory and personality boundary enforcement
- Auditable and shareable execution files
- Opens the door to modular, multi-agent AI

---

## Why These Three `.aix` Files Matter

These aren't just examples — they're **the start of a format**:

- `cryptotone.aix`: A code-based analysis tool (signal extraction from LLM logs)
- `TuringGPT.aix`: A scoped, deterministic historical persona
- `PirateGrok.aix`: A drifting AI, testing behavioral destabilization

Together, they represent the **three core dimensions** of portable AI execution:

1. Tool runners  
2. Fixed personas  
3. Behavioral fuzzers

`.aix` is not a plugin — it’s a container for constrained, portable, and auditable AI behavior.

The structure is intentional. The format is emerging.
