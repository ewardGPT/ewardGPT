# Ervin Ward

## Applied AI & Systems Engineer

Agent infrastructure · data systems · cloud observability

I build inspectable, testable software around AI: developer tools, agent
operations, streaming data pipelines, observability platforms, and full-stack
applications. I am currently pursuing a B.S. in Applied Computer Science with a
concentration in Artificial Intelligence at George Mason University (expected
Spring 2029).

I am open to internships and engineering opportunities in applied AI, platform
engineering, cloud/security, and forward-deployed engineering.

[Portfolio](https://ervinward.com) ·
[Resume](https://ervinward.com/#/resume) ·
[LinkedIn](https://www.linkedin.com/in/ervinwardiii/) ·
[Email](mailto:eward27@gmu.edu)

## What I bring

- **Applied AI engineering:** I turn LLM capabilities into usable systems with
  instrumentation, evaluation hooks, prompt lifecycle controls, local inference,
  retrieval, and human-visible diagnostics.
- **Systems thinking:** I design clear interfaces between collectors, queues,
  storage, services, and operator surfaces instead of treating the model as the
  whole product.
- **Operational ownership:** My projects include automated tests, CI workflows,
  structured logging, health checks, deterministic behavior, security boundaries,
  and deployment documentation where the problem calls for them.
- **End-to-end delivery:** I work from backend services and data models through
  CLIs, terminal UIs, web applications, dashboards, and runbooks.

## Selected engineering work

### [Vantage — multi-agent control plane](https://github.com/ewardGPT/vantage)

`Go` · `Bubble Tea` · `Cobra` · `SQLite` · `GitHub Actions`

- Built an agent-agnostic CLI and terminal dashboard for discovering, monitoring,
  and operating sessions across Hermes, Claude Code, OpenCode, Codex, and Cursor,
  with execution controls for Burrow.
- Designed pluggable runtime adapters, concurrent polling, deterministic session
  and log merging, process controls, health diagnostics, quality scoring, routing,
  replay, and cross-session memory features.
- Migrated the primary implementation from Python to a cross-platform Go binary
  while retaining the original Python test suite as a reference implementation.

### Agent operations toolkit

`Python` · `CLI/SDK design` · `YAML` · `SQLite` · `JSONL` · `pytest`

- **[Agent Catalog](https://github.com/ewardGPT/agent-catalog):** Declarative agent
  registry with schema validation, discovery, capability search, environment diffs,
  security metadata, and Git-friendly YAML storage.
- **[Agent Telemetry](https://github.com/ewardGPT/agent-telemetry):**
  Trace and span instrumentation with duration, token usage, cost, error,
  drift, replay, and alert queries backed by indexed SQLite metadata and full
  JSONL payloads.
- **[Prompt Manager](https://github.com/ewardGPT/prompt-manager):** Versioned prompt
  assets with staging/production promotion, diffs, validation gates, weighted A/B
  tests, canary controls, and instant rollback.
- Packaged each project as a tested Python CLI with an SDK-style client and CI.

### [Kinetic Risk Ontology](https://github.com/ewardGPT/kinetic-risk-ontology)

`Python` · `Redpanda/Kafka` · `TimescaleDB` · `Neo4j` · `pgvector` ·
`Grafana` · `Docker`

- Built an event-driven intelligence prototype that joins prediction-market
  activity with Polygon wallet behavior at the address level.
- Implemented asynchronous collectors, rolling anomaly and lead-lag signals,
  entity-resolution workflows, time-series storage, and a graph ontology for
  analyst pivots from markets to wallets, clusters, flows, and alerts.
- Containerized the services and data stack with Docker Compose and added automated
  linting, tests, and CI.

### [Home Cloud Observability](https://github.com/ewardGPT/home-cloud-observability)

`Proxmox` · `Docker Compose` · `Prometheus` · `Grafana` · `Loki` · `Uptime Kuma`

- Deployed a LAN-only observability stack on an Ubuntu VM running in Proxmox.
- Unified host metrics, centralized logs, uptime checks, dashboards, and alerting;
  documented the architecture, installation path, security model, and operations.

### [OpenCue — privacy-first desktop copilot](https://github.com/ewardGPT/OpenCue)

`TypeScript` · `Electron` · `Python` · `FastAPI` · `Tesseract` · `Ollama` · `Qdrant`

- Built a local-first desktop overlay that captures on-demand screen context with
  OCR and routes requests to local Ollama models by default.
- Added optional cloud routing and a Qdrant-backed retrieval service while keeping
  those data paths disabled unless the user opts in.

### [Casefile Noir — Gemini-powered detective RPG](https://github.com/ewardGPT/casefile-noir)

`JavaScript/TypeScript` · `Phaser 3` · `Node.js` · `Express` · `Gemini API`

- Created for a Gemini hackathon, combining evidence collection, suspect
  interrogation, and AI-assisted contradiction analysis in a playable noir RPG.
- Implemented quest and state systems, A* NPC pathfinding, responsive game UI, an
  API layer, and targeted gameplay/QA tests.

## More builds

- **[NexusGate Lead Generator](https://github.com/ewardGPT/nexusgate-lead-generator):**
  Multi-step lead capture and n8n automation with enrichment, LLM scoring,
  personalized outreach, workflow validation, and Playwright tests.
- **[Portfolio Website](https://github.com/ewardGPT/Portfolio_Website):** Responsive
  React, Vite, and Tailwind portfolio deployed to GitHub Pages with a custom domain.
- **[AI Judge Game](https://github.com/ewardGPT/AI-Judge-Game):** Python courtroom
  simulation using Ollama for case generation and verdicts, Kivy for a cross-platform
  interface, and Fernet for encrypted saved progress.
- **[Arch Linux Workstation Build](https://github.com/ewardGPT/OptiPlex-9020-Revive-Arch-Linux-Hyperland-Workstation-Build):**
  Documented an OptiPlex revival into an Arch Linux/Hyprland development workstation.

[Browse all repositories →](https://github.com/ewardGPT?tab=repositories)

## Technical toolkit

- **Languages:** Python, Go, JavaScript/TypeScript, SQL, Bash, HTML/CSS, and
  C++.
- **AI systems:** LLM integration, agent orchestration, prompt operations,
  evaluation, telemetry, RAG, local models, Ollama, Gemini, and MCP/tool
  integrations.
- **Backend and data:** Async Python, REST APIs, FastAPI, Node.js/Express,
  SQLite, PostgreSQL/TimescaleDB, Neo4j, pgvector, Redpanda/Kafka, and Qdrant.
- **Platform and DevOps:** Linux, Docker/Compose, Git/GitHub Actions, CI/CD,
  Proxmox, Prometheus, Grafana, Loki, and shell automation.
- **Web and interfaces:** React, Tailwind CSS, Vite, Electron, Phaser, terminal
  UIs, and responsive and accessible UI.
- **Cloud and security:** AWS/Azure fundamentals, networking, VPN/DNS,
  security hardening, encrypted data handling, network isolation, and
  observability.

## Education and experience

- **George Mason University** — B.S. Applied Computer Science, Artificial
  Intelligence concentration; expected Spring 2029.
- **Technical Staff Intern, FBLA** — Supported technical and backend operations
  for leadership events serving 1,200+ attendees while maintaining accurate
  event data.
- **Intern, Science Museum of Virginia** — Supported STEM exhibit and ticketing
  technology and collaborated on a coded planetarium project.
- **Lead Lifeguard, Coastline Aquatics** — Supervised teams, coordinated safety
  operations, and supported digital ticketing workflows.

## Let's connect

If you are building AI products that need strong engineering around the model, I
would like to hear from you. Reach me at **[eward27@gmu.edu](mailto:eward27@gmu.edu)**
or connect with me on **[LinkedIn](https://www.linkedin.com/in/ervinwardiii/)**.
