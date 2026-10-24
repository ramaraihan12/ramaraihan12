<h1 align="center">Hi, I'm Rama Raihan</h1>

<p align="center">
  Full-stack developer from Salatiga, Indonesia.<br/>
  I build web apps end to end in Laravel and Next.js, with Postgres or MySQL underneath.<br/>
  I also build LLM apps: RAG, agents and the tools around them.
</p>

<p align="center">
  <a href="mailto:ramaraihan97@gmail.com">
    <img src="https://img.shields.io/badge/Email-ramaraihan97@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://ramaraihan.is-a.dev">
    <img src="https://img.shields.io/badge/Portfolio-ramaraihan.is--a.dev-181717?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" />
  </a>
</p>

---

## What I work with

### Frontend

| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Name | Where I use it |
|:----:|:-----|:------------------|
| <img src="https://skillicons.dev/icons?i=nextjs" width="36" alt="Next.js" /> | **Next.js** | Most of my apps run on it. App Router, server components, the usual setup. My offline-first till, warung-pos, is a Next.js 16 PWA. |
| <img src="https://skillicons.dev/icons?i=react" width="36" alt="React" /> | **React** | Building the interface. Components, hooks, client state. Also the frontend of antre, through Inertia. |
| <img src="https://skillicons.dev/icons?i=ts" width="36" alt="TypeScript" /> | **TypeScript** | All my frontend and Node code is TypeScript now. Catches my mistakes before they reach the browser. |
| <img src="https://skillicons.dev/icons?i=tailwind" width="36" alt="Tailwind CSS" /> | **Tailwind CSS** | Styling. Quicker for me than keeping a separate stylesheet in sync. |
| <img src="https://skillicons.dev/icons?i=vite" width="36" alt="Vite" /> | **Vite** | Bundles the frontend assets on my Laravel projects. |
| <img src="https://cdn.simpleicons.org/inertia/9553E9" width="32" alt="Inertia.js" /> | **Inertia.js** | Connects Laravel to a React frontend in antre, so I get React pages without building a separate API. |
| <img src="https://skillicons.dev/icons?i=htmx" width="36" alt="htmx" /> | **htmx** | Small interactions on the server-rendered pages of webhook-inbox, where a full frontend would be too much. |


### Backend

| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Name | Where I use it |
|:----:|:-----|:------------------|
| <img src="https://skillicons.dev/icons?i=laravel" width="36" alt="Laravel" /> | **Laravel** | APIs, Eloquent, queues, auth. Blade when a page is better rendered on the server. |
| <img src="icons/reverb.svg" width="32" alt="Laravel Reverb" /> | **Laravel Reverb** | Websockets for antre. Ticket calls reach the staff console and the waiting room TV without polling. |
| <img src="https://skillicons.dev/icons?i=php" width="36" alt="PHP" /> | **PHP** | The language behind all the Laravel work. |
| <img src="https://skillicons.dev/icons?i=nodejs" width="36" alt="Node.js" /> | **Node.js** | Runs the server side of Next.js, route handlers and server actions. |
| <img src="https://skillicons.dev/icons?i=python" width="36" alt="Python" /> | **Python** | Backend for my AI projects, managed with uv. |
| <img src="https://skillicons.dev/icons?i=rust" width="36" alt="Rust" /> | **Rust** | webhook-inbox: receives webhooks, checks signatures and forwards them with retries. axum, tokio and sqlx. |
| <img src="https://skillicons.dev/icons?i=go" width="36" alt="Go" /> | **Go** | pg-backup: streams a Postgres dump to S3-compatible storage and restores it to check it works. |


### Database

| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Name | Where I use it |
|:----:|:-----|:------------------|
| <img src="https://skillicons.dev/icons?i=postgres" width="36" alt="PostgreSQL" /> | **PostgreSQL** | My default. Relational data, migrations, a bit of PL/pgSQL when a query gets hairy. Row locks with SKIP LOCKED for queues in antre and webhook-inbox. |
| <img src="https://skillicons.dev/icons?i=mysql" width="36" alt="MySQL" /> | **MySQL** | What most of my Laravel projects sit on, especially the ones on shared hosting. |
| <img src="https://skillicons.dev/icons?i=mongodb" width="36" alt="MongoDB" /> | **MongoDB** | Used on an LMS, where the shape of the content kept changing on me. |
| <img src="https://cdn.simpleicons.org/drizzle/888888" width="32" alt="Drizzle ORM" /> | **Drizzle ORM** | Typed queries and migrations on Postgres in warung-pos. |


### Testing

| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Name | Where I use it |
|:----:|:-----|:------------------|
| <img src="icons/pest.svg" width="56" alt="Pest" /> <img src="icons/phpunit.svg" width="56" alt="PHPUnit" /> | **Pest / PHPUnit** | Tests on the Laravel side, feature tests more than unit tests. antre's tests run on Pest; PHPUnit is what it sits on. |
| <img src="https://cdn.simpleicons.org/vitest/6E9F18" width="32" alt="Vitest" /> | **Vitest** | Unit and integration tests in my TypeScript projects, including warung-pos. |
| <img src="https://cdn.simpleicons.org/pytest/0A9EDC" width="32" alt="pytest" /> | **pytest** | Tests in my Python projects. |
| <img src="icons/playwright.svg" width="32" alt="Playwright" /> | **Playwright** | Browser tests. In warung-pos they switch the network off and check that offline sales sync later. In antre they run against a live websocket server. |
| <img src="icons/testcontainers.svg" width="32" alt="Testcontainers" /> | **Testcontainers** | pg-backup tests start a real Postgres 17 and MinIO in Docker instead of mocking them. |


### Deployment and ops

| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Name | Where I use it |
|:----:|:-----|:------------------|
| <img src="https://skillicons.dev/icons?i=docker" width="36" alt="Docker" /> | **Docker** | So the app behaves the same on my laptop as it does on the server. |
| <img src="https://skillicons.dev/icons?i=githubactions" width="36" alt="GitHub Actions" /> | **GitHub Actions** | Runs lint and tests on every push, and deploys my portfolio to GitHub Pages. |
| <img src="https://cdn.simpleicons.org/coolify/8B5CF6" width="32" alt="Coolify" /> | **Coolify** | Deploys my Laravel and Next.js apps to my own VPS instead of renting a platform. |
| <img src="https://skillicons.dev/icons?i=git" width="36" alt="Git" /> | **Git** | Version control, one branch per feature. |
| <img src="https://cdn.simpleicons.org/minio/C72E49" width="32" alt="MinIO" /> | **MinIO / S3** | Where pg-backup stores its backups. I run MinIO locally; it speaks the same S3 API as AWS. |
| <img src="https://cdn.simpleicons.org/prometheus/E6522C" width="32" alt="Prometheus" /> | **Prometheus** | Metrics endpoints on webhook-inbox and pg-backup, so I can see deliveries and backups from outside. |


### Payments

| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Name | Where I use it |
|:----:|:-----|:------------------|
| <img src="icons/midtrans.svg" width="80" alt="Midtrans" /> | **Midtrans** | Checkout and payment handling for the Indonesian projects. webhook-inbox checks its callback signatures. |


### AI

| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Name | Where I use it |
|:----:|:-----|:------------------|
| <img src="https://skillicons.dev/icons?i=fastapi" width="36" alt="FastAPI" /> | **FastAPI** | Serves my docs assistant and research agent, with answers streamed over server-sent events. |
| <img src="https://cdn.simpleicons.org/langchain/888888" width="32" alt="LangChain" /> | **LangChain / LangGraph** | LangGraph runs my research agent: a plan, a human review step, then parallel searches. LangChain handles the model calls in text-to-sql-chat. |
| <img src="icons/llamaindex.png" width="32" alt="LlamaIndex" /> | **LlamaIndex** | Document ingestion and pgvector search in my docs question-answering app. |
| <img src="https://skillicons.dev/icons?i=vercel" width="36" alt="Vercel AI SDK" /> | **Vercel AI SDK** | Streaming chat and tool calls in a Next.js support bot. |
| <img src="icons/prism.webp" width="56" alt="Prism PHP" /> | **Prism PHP** | Reads supplier invoices into typed data inside a Laravel app. |
| <img src="https://cdn.simpleicons.org/ollama/888888" width="32" alt="Ollama" /> | **Ollama and llama.cpp** | Local models. My apps default to Ollama so they cost nothing to run, and I code with llama.cpp on my laptop. |
| <img src="icons/openai.svg" width="24" alt="OpenAI" /> <img src="https://cdn.simpleicons.org/googlegemini/8E75B2" width="24" alt="Gemini" /> <img src="https://cdn.simpleicons.org/claude/D97757" width="24" alt="Claude" /> | **OpenAI, Gemini and Claude APIs** | One setting switches providers in each AI app, and my llm-gateway puts all of them behind one endpoint. |
| <img src="https://cdn.simpleicons.org/postgresql/4169E1" width="32" alt="PostgreSQL (pgvector)" /> | **pgvector** | Vector search inside Postgres, so there is no separate vector database to run. |
| <img src="https://cdn.simpleicons.org/modelcontextprotocol/888888" width="32" alt="MCP" /> | **MCP** | Exposes the guarded SQL tools of text-to-sql-chat to Claude Desktop and Cursor. |

---

## Things I've built lately

Full-stack apps

- [antre](https://github.com/ramaraihan12/antre): queue and booking system for small clinics and barbershops. Customers take a ticket or book a slot, staff call numbers, and a TV in the waiting room shows and announces them live. Laravel, Inertia, React, Reverb, Postgres.
- [warung-pos](https://github.com/ramaraihan12/warung-pos): a point of sale for a small shop that keeps selling when the internet drops and syncs when it comes back. Next.js, Drizzle, Dexie, a service worker.
- [ralaex](https://github.com/ramaraihan12/ralaex): a household finance app my wife and I use. Next.js, Supabase.

Backend and tools

- [webhook-inbox](https://github.com/ramaraihan12/webhook-inbox): receives webhooks from Midtrans, Xendit or GitHub, checks the signature, stores each one and forwards it with retries. Rust, axum, Postgres.
- [pg-backup](https://github.com/ramaraihan12/pg-backup): streams a Postgres dump to S3 or MinIO, compressed and encrypted, and proves each backup by restoring it. Go.
- [llm-gateway](https://github.com/ramaraihan12/llm-gateway): one OpenAI-compatible endpoint in front of OpenAI, Gemini, Claude and Ollama, with fallback, rate limits and cost logs. TypeScript, Hono.
- [issue-triage-action](https://github.com/ramaraihan12/issue-triage-action): a GitHub Action that labels new issues, points out likely duplicates and asks for missing details. TypeScript.
- [local-ai-coding-setup](https://github.com/ramaraihan12/local-ai-coding-setup): the free local coding setup I run on a 6 GB laptop GPU, with scripts and benchmarks. llama.cpp, Ollama.

AI apps

- [docs-rag-assistant](https://github.com/ramaraihan12/docs-rag-assistant): ask questions about your PDF, DOCX and Markdown files and get answers that cite the page. FastAPI, LlamaIndex, pgvector.
- [research-agent](https://github.com/ramaraihan12/research-agent): plans a question, waits for me to approve the plan, searches the web and writes a cited report. LangGraph, FastAPI.
- [shop-support-bot](https://github.com/ramaraihan12/shop-support-bot): support chatbot for a small shop that checks orders and stock, opens tickets and hands over to a human. Next.js, Vercel AI SDK, pgvector.
- [invoice-flow](https://github.com/ramaraihan12/invoice-flow): reads supplier invoices with an LLM, flags what looks wrong and exports approved ones to CSV and a signed webhook. Laravel, Prism PHP.
- [text-to-sql-chat](https://github.com/ramaraihan12/text-to-sql-chat): ask a sales database questions in English or Indonesian, with the SQL checked before it runs. Python, LangChain, Streamlit, MCP.

---

## My contribution graph

Pac-Man is working through my commits.

<!-- pacman -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ramaraihan12/ramaraihan12/output/pacman-contribution-graph-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ramaraihan12/ramaraihan12/output/pacman-contribution-graph.svg" />
  <img alt="Pac-Man contribution graph" src="https://raw.githubusercontent.com/ramaraihan12/ramaraihan12/output/pacman-contribution-graph.svg" />
</picture>

---

<p align="center">
  Want to talk? <a href="mailto:ramaraihan97@gmail.com">ramaraihan97@gmail.com</a>
</p>
