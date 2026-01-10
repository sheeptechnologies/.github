<img src="assets/logo.png" height="50"> <img src="assets/sheep_logo.png" height="50">

# Grounding the Agentic Future

We are on the verge of a paradigm shift. Large Language Models (LLMs) have solved the reasoning problem, but reasoning, alone, operates in a vacuum. Artificial intelligence without reliable, structured, and deterministic access to data reality is a powerful engine spinning its wheels.

Today, AI Agents are promising but fragile. They hallucinate APIs, forget code context, and struggle to query enterprise databases. The bottleneck is no longer the model's intelligence; it is information logistics.

Sheep was born to solve this problem. We don’t build the brain; we build the nervous system.

## Our Core Belief: Intelligence Needs Roots

To develop AGI—or even just an autonomous software agent society—we don't need a bigger model. We need better access to raw, static data.

Agents must stop "reading" code and data as plain text and start "understanding" them as logical structures. Our mission is to provide the infrastructure layer (Retrieval & Tooling) that transforms repositories, databases, and documentation into actionable knowledge for agents.

**If LLMs are the processors, Sheep is the system bus.**

## The Sheep Stack

We are developing a suite of modular and composable libraries, designed to be the fundamental primitives with which developers will build their autonomous "Software Houses".

### 1. Grazer: The Context Router
[https://github.com/sheeptechnologies/grazer](https://github.com/sheeptechnologies/grazer)

An agent does not live on code alone; it needs manuals, specs, and documentation. Grazer is the intelligent routing layer that orchestrates sources of truth.

*   **Unified Feed**: Manages heterogeneous repositories—whether production code, Markdown knowledge bases, or translated technical PDFs—as a single stream of context.
*   **Scope Management**: Decides exactly which repository to "graze" based on the specific task, effectively separating signal from noise and preventing context pollution.

### 2. Crader: The Codebase Cortex
[https://github.com/sheeptechnologies/crader](https://github.com/sheeptechnologies/crader)

Code is not prose; it is a graph of dependencies, logic, and semantics. Crader is the indexing and retrieval engine for complex codebases.

*   **Beyond Text**: It doesn't just read files. It uses advanced semantic chunking and graph analysis to understand that modifying function A impacts class B.
*   **Deep Context**: Gives agents the "peripheral vision" needed to navigate large repositories without getting lost.

#### Powered by Mycelium
[https://github.com/sheeptechnologies/mycelium](https://github.com/sheeptechnologies/mycelium)

At the heart of Crader lies Mycelium, our custom Python implementation of StackGraph.

*   **Zero-Latency Indexing**: In a world where agents commit frequently, re-indexing is obsolete. Mycelium makes context updates file-incremental, ensuring agents always work with a real-time understanding of the codebase structure.

### 3. Crook: The Data Interface
[https://github.com/sheeptechnologies/crook](https://github.com/sheeptechnologies/crook)

Enterprise data lives in relational tables, not vectors. Crook is the bridge between natural language and the rigid structure of SQL databases.

*   **Schema Awareness**: Maps table relationships to provide agents with a deep understanding of the data domain before they even write the first query.
*   **Text-to-SQL Reliability**: Provides the tools necessary for an agent to autonomously explore, query, and verify data, transforming vague questions into precise extractions.

## The Vision: A Society of Agents

We envision an ecosystem where:

*   One agent uses **Grazer** to assimilate technical specifications from a documentation repo.
*   A second agent uses **Crader** (powered by Mycelium) to instantly navigate the code and implement a feature.
*   A third agent uses **Crook** to validate the impact on production data.

To make this future possible, agents must have better tools than humans, not worse. They must be able to "touch" raw data.

**Sheep provides these tools. We are building the foundations upon which agents will build tomorrow's software.**

## Use Cases: The Infrastructure in Action

Sheep isn't about building better chatbots. It’s about enabling new operating models for software production. Here is how our infrastructure enables scenarios impossible with traditional tools.

### 1. Molecular Enterprise Construction (The Block Paradigm)

*   **The Goal**: Create a complete software company (e.g., a logistics platform) by assembling autonomous business "blocks" (Order Collection, Invoicing, Shipping) instead of writing monolithic code.
*   **The Flow**: The human architect defines only the inputs/outputs of the blocks in natural language. Agents develop each module independently.
*   **The Sheep Advantage**:
    *   **Interlocking Logic**: When Agent A builds the "Orders" block, **Crader** instantly exposes the API interfaces. Agent B, building "Invoicing", uses Crader to "see" exactly how to connect to the Orders block without errors.
    *   **Dynamic Wiring**: If the architect decides to insert a "Quality Control" block in the middle, **Mycelium** recalculates the dependency graph and guides agents to rewire connections between blocks in real-time.
*   **Result**: "Liquid" and modular software, assembled like an assembly line.

### 2. High-Frequency Feature Loop

*   **The Goal**: Implement complex features in rapidly evolving codebases without breaking production.
*   **The Flow**: An agent modifies core logic. In a classic system, the agent is "blind" until CI/CD runs.
*   **The Sheep Advantage**: Thanks to **Mycelium**, the code index is file-incremental. The agent sees the impact of its change on the entire system the instant it saves the file (zero latency), fixing regressions before even committing.

### 3. Data-Aware Reasoning (The "Full Stack" Agent)

*   **The Goal**: Fix bugs that depend not on syntax, but on data state (e.g., an exception caused by corrupt or unexpected data).
*   **The Flow**: The application crashes. The agent must understand why.
*   **The Sheep Advantage**: The agent doesn't just look at the code. It uses **Crook** to query the Production Database and correlate data state with code logic mapped by Crader. It discovers the crash is caused by a NULL value in a specific column and writes a patch that fixes both the code (error handling) and the data (cleanup query).

### 4. The "Archeologist" Migration

*   **The Goal**: Modernize legacy systems where documentation is lost and knowledge is tribal.
*   **The Flow**: Extract a microservice from a 10-year-old monolith.
*   **The Sheep Advantage**: **Grazer** ingests old PDFs and wikis to recover the original business logic. **Crader** maps the "spaghetti code" to find safe cut points. **Crook** deduces hidden relationships in the old database. Agents work on a complete map of reality, not assumptions.

## Join the Flock.