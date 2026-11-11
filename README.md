<p align="center">
  <img src="assets/library-amadeus-adjusted.png" alt="A contemplative profile and a full-length masked figure in a dark, imagined library" width="100%">
</p>

### Forward Deployed Engineer · Applied AI & product · Senior full-stack

**AI agents · RAG · MCP · Product engineering**

I work where a real-world problem meets the systems needed to solve it: understanding the use case, designing the product, building the software and making AI useful to the people who work with it.

The projects below show how I explore that work in practice — from inspectable agents and human-reviewed workflows to interactive learning, local AI and systems experiments.

[**LinkedIn ↗**](https://www.linkedin.com/in/nicolas-hedoire-1734775b/) &nbsp; · &nbsp; [**All repositories ↗**](https://github.com/nicolashedoire?tab=repositories)

---

## Agents, tools & applied AI

### [Sidecraft](https://github.com/nicolashedoire/sidecraft) · Watch software take shape

<a href="https://github.com/nicolashedoire/sidecraft"><img src="assets/projects/sidecraft.png" alt="Illustration of live coding and session replay in Sidecraft" width="320"></a>

A macOS AI coding companion that writes and revises code visibly in VS Code. Its Swift agent engine supports local Ollama models and a separate Claude/MCP workflow. Recorded Claude/MCP sessions can be replayed as a structured development film, including file changes, commands and execution traces.

<sub>Private repository · access limited to authorized collaborators.</sub>

### [SDK AI Agents](https://github.com/nicolashedoire/sdk-ai-agents) · Making an agent's reasoning inspectable

<a href="https://github.com/nicolashedoire/sdk-ai-agents"><img src="https://raw.githubusercontent.com/nicolashedoire/sdk-ai-agents/main/docs/public/images/banner.svg" alt="SDK AI Agents project banner" width="320"></a>

A TypeScript SDK that gives an agent an explicit state: observations, hypotheses and contradictions can be inspected as it works. It combines evidence-aware decisions, event replay, cost and trace tracking, and MCP client/server bridges. [Explore the documentation ↗](https://nicolashedoire.github.io/sdk-ai-agents/)

### [Kadran MCP Proof](https://github.com/nicolashedoire/kadran-mcp-proof) · Connecting an agent to business operations

<a href="https://github.com/nicolashedoire/kadran-mcp-proof"><img src="https://raw.githubusercontent.com/nicolashedoire/kadran-mcp-proof/main/docs/images/quote-and-actions.png" alt="Kadran demonstration using synthetic data" width="320"></a>

A local Mistral agent brings together a fictional inbox, CRM, catalog and quoting service through MCP. The quote service checks customer, quantity and pricing data independently, records tool activity and leaves approval to a human. Built as a Docker demonstrator using synthetic data.

### [Harness Pilot](https://github.com/nicolashedoire/harness-pilot) · A control room for development agents

<a href="https://github.com/nicolashedoire/harness-pilot"><img src="https://raw.githubusercontent.com/nicolashedoire/harness-pilot/main/docs/assets/project-cover.png" alt="Harness Pilot project artwork" width="320"></a>

A self-hosted workspace for persistent project conversations with Claude Code and Codex. It brings together agent discussions, parallel roles, project memory and tasks so people can inspect and guide work as it progresses.

### [Structured World Models](https://github.com/nicolashedoire/structured-world-models) · Looking beyond one-step predictions

<a href="https://github.com/nicolashedoire/structured-world-models"><img src="https://raw.githubusercontent.com/nicolashedoire/structured-world-models/main/world_models_trajectories.png" alt="Structured World Models experimental trajectories" width="320"></a>

A research project investigating how prediction errors accumulate when an agent plans several steps ahead. It compares models and planning on reproducible synthetic systems, with an oracle used to validate the experiments.

### [n8n Docker](https://github.com/nicolashedoire/n8n-docker) · Putting human review into an AI workflow

<a href="https://github.com/nicolashedoire/n8n-docker"><img src="https://raw.githubusercontent.com/nicolashedoire/n8n-docker/main/docs/images/atelier-workflow-n8n.png" alt="n8n workflow demonstration" width="320"></a>

A local n8n setup with an importable workflow for AI-assisted qualification. The example shows how automation and human judgment can work together in a practical process.

## Interactive products & experiences


### [Île des Possibles](https://github.com/nicolashedoire/ile-des-possibles) · Learning by changing the system

<a href="https://github.com/nicolashedoire/ile-des-possibles"><img src="https://raw.githubusercontent.com/nicolashedoire/ile-des-possibles/main/public/cover.png" alt="Illustration of the Ile des Possibles energy simulation" width="320"></a>

An interactive 3D environment for exploring energy trade-offs. Change production, demand and storage across a simulated day, compare scenarios and see where shortages emerge. The model and data are intentionally simplified for learning. [Try the experience ↗](https://nicolashedoire.github.io/ile-des-possibles/)

### [Apple-1 Lab](https://github.com/nicolashedoire/apple-1-lab-site) · Understanding a computer from the inside

<a href="https://github.com/nicolashedoire/apple-1-lab-site"><img src="https://raw.githubusercontent.com/nicolashedoire/apple-1-lab-site/main/docs/apple1-cover.png" alt="Illustration for Apple-1 Lab" width="320"></a>

An interactive journey through the Apple-1, from assembling a 3D board to stepping through 6502 instructions and watching registers and memory change. A teaching tool designed to make the machine tangible. [Explore the lab ↗](https://nicolashedoire.github.io/apple-1-lab-site/)

### [Morphé Motion](https://github.com/nicolashedoire/morphe-motion-poc) · Teaching a correction to a scene

<a href="https://github.com/nicolashedoire/morphe-motion-poc"><img src="https://raw.githubusercontent.com/nicolashedoire/morphe-motion-poc/main/docs/hero.png" alt="Morphe Motion application" width="320"></a>

An editable 2D motion playground that explores whether a correction to an object's orientation can be captured and applied to another character. It uses inverse kinematics and a reusable symbolic rule. [Try the demo ↗](https://nicolashedoire.github.io/morphe-motion-poc/)

### [Vibration AI](https://github.com/nicolashedoire/vibration-ia) · Bringing anomaly detection to the edge

<a href="https://github.com/nicolashedoire/vibration-ia"><img src="assets/projects/vibration-ai.png" alt="Illustration of an embedded vibration sensor" width="320"></a>

An ESP32 and vibration sensor learn a local baseline and score unusual behaviour on the device, with live readings in a web dashboard. The interface distinguishes simulated data from real sensor data.

### [ToitScan](https://github.com/nicolashedoire/toitscan) · A full-stack product prototype

<a href="https://github.com/nicolashedoire/toitscan"><img src="assets/projects/toitscan.png" alt="Illustration of drone-based roof inspection" width="320"></a>

A Next.js website and booking flow for drone-based roof inspection, including local landing pages and a request endpoint. The repository documents which pieces — including payments and notifications — remain to be implemented.

## Developer tools & research

### [Substrat](https://github.com/nicolashedoire/substrat-landing) · Exploring network protocols

<a href="https://github.com/nicolashedoire/substrat-landing"><img src="https://raw.githubusercontent.com/nicolashedoire/substrat-landing/main/images/og-image.png" alt="Substrat project artwork" width="320"></a>

A tool presented for analysing PCAP captures, inferring protocol structure, detecting anomalies and exporting artefacts such as Wireshark dissectors. The public repository contains its website, documentation and binaries. [Visit the site ↗](https://nicolashedoire.github.io/substrat-landing/)

### [Devenir DevOps](https://github.com/nicolashedoire/devenir-devops) · Following one application towards production

<a href="https://www.amazon.fr/dp/B0HKYFCRBK"><img src="https://images-na.ssl-images-amazon.com/images/P/B0HKYFCRBK.01.LZZZZZZZ.jpg" alt="Cover of Devenir DevOps by Nicolas Hedoire" width="160"></a>

The French-language companion to my book follows a TaskBoard application through ten practical milestones: local development, Docker, CI, Kubernetes, observability, security and more, with guides and exercises. [Find the book on Amazon ↗](https://www.amazon.fr/dp/B0HKYFCRBK)

### [Pagecodec Lab](https://github.com/nicolashedoire/pagecodec-lab) · Testing ideas about compression and memory

<a href="https://github.com/nicolashedoire/pagecodec-lab"><img src="https://raw.githubusercontent.com/nicolashedoire/pagecodec-lab/main/assets/banner.png" alt="Pagecodec Lab project banner" width="320"></a>

A low-level lab for lossless page compression, compressed-data queries and memory strategies. It includes reproducible benchmarks, real datasets and negative results, keeping the scope of its findings explicit.

### [ProtoLife](https://github.com/nicolashedoire/protolife) · Simulating building blocks of life

<a href="https://github.com/nicolashedoire/protolife"><img src="https://raw.githubusercontent.com/nicolashedoire/protolife/main/docs/images/protolife-cover.png" alt="ProtoLife project illustration" width="320"></a>

A pre-alpha simulation exploring protocells, chemistry and vesicle growth and division, with a C11 core and a Godot visualisation. An experiment in building and observing simple systems.

### [Drawer Model](https://github.com/nicolashedoire/drawer-model) · Exploring drawing as a program

<a href="https://github.com/nicolashedoire/drawer-model"><img src="assets/projects/drawer-model.png" alt="Illustration of drawing with a stroke program" width="320"></a>

A local experiment that represents drawings as stroke programs, with CLIP-based critique and MCP tools. Its current scope is a limited drawing corpus rather than unrestricted image generation.

---

<sub>Based in France · Applied AI, product thinking and software engineering.</sub>
