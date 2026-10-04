<h1 align="center">Sol Soletti</h1>

<p align="center">
  <strong>Backend & AI Engineer · MCP · Agents · Data systems · Go · Python · TypeScript</strong>
</p>

<p align="center">
  I take ideas from a hunch to production: AI-first, and with the evidence on the table.
</p>

I'm an Information Systems Engineer (UTN) based in Rosario, Argentina, working as an Engineer at **[Teramot](https://teramot.com)**. I build data systems, backend services and applications on top of language models and AI agents, from the query engine and the protocol to the interface people actually use.

I work AI-first: I explore early, prototype fast, measure honestly and keep only what holds up. Outside work, I co-founded **[Legios](https://legios.com.ar)** with [Valentín Torassa Colombero](https://github.com/ValentinTorassa), where we build developer tools and games.

I write about what I build, break and fix at **[solsoletti.com/blog](https://solsoletti.com/blog/)**.

## Current role & focus

### Teramot · Engineer

*Dec. 2025 – present*

**[Teramot Beacon](https://docs.teramot.com/blog/eight-rows-not-twelve-million/)**: I'm the main author of the node, the UI and much of the protocol. Beacon answers business questions in plain language by pulling only the slice of data each question needs into DuckDB, inside the customer's own network: one process, one container, any cloud or on-prem.

- **Slice cache** validated by source version, not by TTL.
- **TLP protocol**: a versioned, cloud-agnostic contract for dashboards, monitors, artifacts, refresh and scheduling.
- **MCP server**: Beacon as tools for agents, plus the node's own assistant loop.
- **Dashboards and alerts**: cross-filtering, small multiples, monitors and stale-data alerts.
- **Data quality**: catches join fan-out, duplicates, mismatched keys and mixed currencies.
- **Next.js UI**: every answer with a narrative, a table, an auto-chart, the SQL and cache provenance.

**Teramot data platform**: backend engineer on Go services, business logic and internal processes, plus the quality, maintainability and performance work that keeps it running.

**Current focus:** MCP servers, read-only agent surfaces, caching over business data, and LLM applications that show where every answer comes from.

Previously, I was an IT Intern at Argental, where I led **[Busquetti](https://busquetti.argental.com.ar/)**, a multi-agent AI product advisor (one agent per machine line), and migrated it from OpenAI agents to a RAG pipeline I built myself.

## Legios

Developer tools and games I build with Valentín. Tools that look at what's already on disk before calling a model. *"Wrong memory is worse than no memory."* We're part of AWS Activate.

- **cartographer** *(private, I lead it)*: charts a repo before anyone sails it. A deterministic symbolic context artifact plus a symbol index on tree-sitter and SQLite. Zero model tokens.
- **pipeline** *(private, built by both of us)*: from an approved spec to a verified PR, with per-run isolation on ECS Fargate.
- **[quartermaster](https://github.com/legiosai/quartermaster)** *(public, Valen leads it)*: how much quota you have left, in every agent account on the machine. Installs with brew, npm, apt, scoop and winget. No network, no credentials.
- **[Sun and Moon](https://sunandmoon.legios.com.ar)**: a two-player cooperative puzzle platformer about the only hour two lovers can share. Playable in the browser.

## Projects & open source

- **[nats-trail](https://github.com/solsolettidev/nats-trail)**: agent-native observability for NATS and JetStream. A web UI, a CLI and an MCP server over one bounded query engine. Follow a `request_id` across four streams without opening four terminals, and let an agent look at production without being able to touch it. Published on [npm](https://www.npmjs.com/package/nats-trail), Apache-2.0. *[How it got there →](https://solsoletti.com/blog/a-flag-is-not-a-guarantee/)*
- **[aeternum](https://github.com/solsolettidev/aeternum)**: a curated personal photo archive: gallery, collections, favorites and friends. React, Supabase and Playwright. **[Open the app →](https://www.aeternumarchive.com/)**

### Contributions

- **[motherduckdb/mcp-server-motherduck #117](https://github.com/motherduckdb/mcp-server-motherduck/pull/117)** *(in review)*: makes the DuckDB/MotherDuck MCP server speak MCP 2026-07-28, with an e2e regression test over raw JSON-RPC.

## Writing

- **[Eight Rows, Not Twelve Million](https://docs.teramot.com/blog/eight-rows-not-twelve-million/)** · Teramot Engineering: the cache behind Teramot Beacon. Pull only the slice a question needs, and invalidate by source version instead of a TTL.
- **[A Flag Is Not a Guarantee](https://solsoletti.com/blog/a-flag-is-not-a-guarantee/)**: how nats-trail went from yet another NATS GUI to a place where an agent can look at production without being able to touch it.

## Technical toolkit

**Backend and data**

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black" alt="DuckDB" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/NATS_%2F_JetStream-27AAE1?style=for-the-badge&logo=natsdotio&logoColor=white" alt="NATS and JetStream" />
  <img src="https://img.shields.io/badge/dlt-59C1D5?style=for-the-badge" alt="dlt" />
</p>

**AI and agents**

<p>
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/RAG-6F42C1?style=for-the-badge" alt="RAG" />
  <img src="https://img.shields.io/badge/AI_Agents-111827?style=for-the-badge" alt="AI agents" />
  <img src="https://img.shields.io/badge/tree--sitter-1F8F3A?style=for-the-badge" alt="tree-sitter" />
</p>

**Frontend**

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white" alt="Astro" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=godotengine&logoColor=white" alt="Godot" />
</p>

**Cloud and operations**

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/ECS_%2F_Fargate-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS ECS and Fargate" />
  <img src="https://img.shields.io/badge/CloudFormation-FF4F8B?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS CloudFormation" />
  <img src="https://img.shields.io/badge/OpenTofu-FFDA18?style=for-the-badge&logo=opentofu&logoColor=black" alt="OpenTofu" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Podman-892CA0?style=for-the-badge&logo=podman&logoColor=white" alt="Podman" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" />
</p>

## Education & languages

- **Information Systems Engineering**, Universidad Tecnológica Nacional (UTN), 2021 – 2026
- **High School Diploma in Computer Science**, E.E.M. N°202 Manuel Leiva, 2015 – 2019

Spanish (native) · English (professional) · Italian (elementary)

<h2 align="center">Find me online</h2>

<p align="center">
  <a href="https://solsoletti.com"><img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=firefoxbrowser&logoColor=white" alt="Portfolio" /></a>
  <a href="https://solsoletti.com/blog/"><img src="https://img.shields.io/badge/Blog-0B1120?style=for-the-badge&logo=rss&logoColor=FF6600" alt="Blog" /></a>
  <a href="https://www.linkedin.com/in/solsoletti"><img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin-white&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://legios.com.ar"><img src="https://img.shields.io/badge/Legios-4CC9FF?style=for-the-badge&logoColor=white" alt="Legios" /></a>
  <a href="mailto:solettisool@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  Rosario, Argentina · UTC-3
</p>
