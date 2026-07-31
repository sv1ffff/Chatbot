<p align="center">
  <h1 align="center">Omnichannel Chatbot & AI Platform</h1>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-blue?labelColor=111827">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-111827?logo=nextdotjs&logoColor=white">
  <img alt="Turborepo" src="https://img.shields.io/badge/Turborepo-EF4444?logo=turborepo&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
</p>

<p align="center">
  <strong>An advanced self-hosted omnichannel chat marketing platform and visual bot builder powered by AI.</strong>
</p>

---

## ✨ Features

- **Omnichannel Support:** Connect with major messaging platforms and APIs.
- **Visual Flow Builder:** Drag-and-drop node-based automation builder.
- **AI Integration:** Support for multiple modern LLMs and AI agents.
- **Live Chat Inbox:** Real-time conversation management and team inbox.
- **Contact CRM:** Manage contacts, tags, and automated sequences.
- **Monorepo Architecture:** Built for high scalability using Turborepo and pnpm workspaces.

## Tech Stack

- **Backend & Core:** Node.js, TypeScript, Redis, BullMQ
- **Frontend:** Next.js, React, Tailwind CSS
- **Database:** PostgreSQL (with pgvector)
- **Infrastructure:** Docker & Docker Compose

## Project Structure

```text
.
|-- apps/
|   |-- builder/       # Next.js web application and UI builder
|   |-- worker/        # Background queue workers for automation and AI
|   |-- realtime/      # Realtime messaging server
|   |-- cli/           # Command line utility
|   `-- mcp-server/    # MCP server implementation
|-- integrations/      # Platform-specific webhook & API connectors
|-- packages/          # Shared business logic, database models, and UI components
|-- docker-compose.yml
|-- pnpm-workspace.yaml
`-- turbo.json
