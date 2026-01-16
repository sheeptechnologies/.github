<img src="assets/logo.png" height="50"> <img src="assets/sheep_logo.png" height="40">

**Grounding the Agentic Future.**

Relying on closed AI monoliths means exposing your IP, data, and business logic to black boxes you can't control. SheepTechnologies exists to solve this engineering gap.

We don't build the model (the engine). We build the **Cognitive Middleware** that gives it eyes, hands, and safe boundaries.

Our mission: provide **Open-Source Primitives** that let you decouple Intelligence from Execution. The AI reasons, but you control the infrastructure.

---

## The Sheep Stack

Five primitives that work together to build sovereign AI systems:

### 1. [Crader](https://github.com/sheeptechnologies/crader)- Sovereign Code Intelligence

**Build your own Copilot. Keep your IP inside the firewall.**

A production-ready indexer that transforms your repository into a semantic map. Agents can navigate dependencies and reason about legacy architecture without ever sending source code to third-party clouds.

**Use when**: You need AI to understand codebases without exposing IP.

**Cool use**: Build your personal Cursor/Copilot alternative with open-source models and local GPU. Focus on agentic development without vendor lock-in.

---

### 2. [Crook](https://github.com/sheeptechnologies/crook)- Air-Gapped Data Interface

**High-level reasoning on strictly private data.**

The bridge between fluid reasoning and rigid SQL. Crook extracts schema without touching sensitive values, allowing LLMs to generate precise queries while execution happens locally on your secure infrastructure.

**GDPR compliant by design.**

**Use when**: You need natural language queries on sensitive databases.

**Cool use**: Let non-technical teams query production databases with natural language—compliance team asks "show me all EU user data", sales asks "revenue by region last quarter"—all without exposing raw data to external APIs.

---

### 3. [Collie](https://github.com/sheeptechnologies/collie)- Dynamic Skill Manager

**Skill Discovery & Fabrication.**

A smart router for tool execution. Collie manages the "muscle memory" of the system, allowing agents to discover existing tools or autonomously generate and register new capabilities on the fly.

**Use when**: Your agent needs to adapt to unknown tasks.

**Cool use**: Build self-extending agents that fabricate missing tools on demand. Agent needs to parse a new file format? It generates the parser, tests it, and registers it for future use—growing smarter with each task.

---

### 4. [Silo](https://github.com/sheeptechnologies/silo) - State Persistence Layer

**Memory is Identity.**

Models are ephemeral; Silo provides continuity. It manages connection pools and persists the "stream of consciousness" across sessions, turning isolated interactions into long-term workflows.

**Use when**: You need stateful agents with memory across sessions.

**Cool use**: Create agents that evolve with your codebase. Track architectural decisions over months, remember why certain patterns were chosen, and surface relevant context when similar situations arise—like a senior architect who never forgets.

---

### 5. [Grazer](https://github.com/sheeptechnologies/grazer)- Orchestration CLI

**The Unified Control Plane.**

The global interface (CLI/API) that orchestrates the entire Sheep stack. Grazer abstracts the complexity of the primitives, serving as the bridge between you (the Architect) and the Infrastructure.

**Use when**: You want to control the full stack from one place.

**Cool use**: Build complex multi-agent workflows from your terminal. "Analyze this PR for security issues, query historical incident data, generate a risk report, and persist findings"—one command that orchestrates Crader, Crook, and Silo seamlessly.

---

## Project Status

All projects are currently in **active development**:
- Open for contributions
- Breaking changes may occur
- Production use: evaluate based on your risk tolerance

Check each repository's README for installation and getting started guides.

---

## Getting Involved

- **Explore**: Browse [all repositories](https://github.com/orgs/sheeptechnologies/repositories)
- **Discuss**: Share ideas in [Discussions](https://github.com/orgs/sheeptechnologies/discussions)
- **Contribute**: See CONTRIBUTING.md in each repo
- **Propose**: Submit [RFCs](https://github.com/orgs/sheeptechnologies/discussions/categories/rfc-request-for-comments) for architectural changes

---

**Control returns to those who write the code, not those who own the model.**
