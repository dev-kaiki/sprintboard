# SprintBoard — Kanban (Trello-like) + Realtime + RBAC

[![CI](https://github.com/dev-kaiki/sprintboard/actions/workflows/ci.yml/badge.svg)](https://github.com/dev-kaiki/sprintboard/actions/workflows/ci.yml)
![Next](https://img.shields.io/badge/next.js-14-222?logo=next.js)
![NestJS](https://img.shields.io/badge/nestjs-10-222?logo=nestjs)
![Postgres](https://img.shields.io/badge/postgres-16-222?logo=postgresql)
![Docker](https://img.shields.io/badge/docker-ready-222?logo=docker)

Projeto “flagship” do portfólio: Kanban estilo Trello com **drag-and-drop**, colaboração e updates em tempo real.

> **Status atual:** repo criado a partir do template (API + Web + Postgres).  
> Endpoints prontos: `/health`, `/users` e Swagger `/docs`.  
> O Kanban + realtime entram no roadmap abaixo.

---

## ✅ Roadmap (MVP do demo)
- [ ] Workspaces + membros
- [ ] Boards/Columns/Cards
- [ ] Drag-and-drop no frontend
- [ ] Realtime (WebSocket) para movimentações/comentários
- [ ] RBAC por workspace (admin/member/viewer)
- [ ] Auditoria de mudanças

---

## ▶️ Rodar local
```powershell
corepack enable
corepack prepare pnpm@latest --activate

pnpm install
docker compose up -d
