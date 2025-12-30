<div align="center">

# sprintboard

<a href="https://dev-kaiki-sprintboard.vercel.app"><img src="https://img.shields.io/badge/LIVE%20DEMO-Vercel-111?style=for-the-badge&logo=vercel&logoColor=white"></a>
<a href="https://dev-kaiki-sprintboard-api.onrender.com/docs"><img src="https://img.shields.io/badge/SWAGGER-API%20Docs-111?style=for-the-badge&logo=swagger&logoColor=white"></a>
<a href="https://github.com/dev-kaiki/sprintboard"><img src="https://img.shields.io/badge/REPO-GitHub-111?style=for-the-badge&logo=github&logoColor=white"></a>

</div>

## Quick Links
- Live: https://dev-kaiki-sprintboard.vercel.app
- Swagger: https://dev-kaiki-sprintboard-api.onrender.com/docs

## Deploy (1-click)
- Deploy API (Render): https://render.com/deploy?repo=https://github.com/dev-kaiki/sprintboard
- Deploy Web (Vercel): https://vercel.com/new/clone?repository-url=https://github.com/dev-kaiki/sprintboard

---

# SprintBoard â€” Kanban (Trello-like) + Realtime + RBAC

[![CI](https://github.com/dev-kaiki/sprintboard/actions/workflows/ci.yml/badge.svg)](https://github.com/dev-kaiki/sprintboard/actions/workflows/ci.yml)
![Next](https://img.shields.io/badge/next.js-14-222?logo=next.js)
![NestJS](https://img.shields.io/badge/nestjs-10-222?logo=nestjs)
![Postgres](https://img.shields.io/badge/postgres-16-222?logo=postgresql)
![Docker](https://img.shields.io/badge/docker-ready-222?logo=docker)

Projeto â€œflagshipâ€ do portfÃ³lio: Kanban estilo Trello com **drag-and-drop**, colaboraÃ§Ã£o e updates em tempo real.

> **Status atual:** repo criado a partir do template (API + Web + Postgres).  
> Endpoints prontos: `/health`, `/users` e Swagger `/docs`.  
> O Kanban + realtime entram no roadmap abaixo.

---

## âœ… Roadmap (MVP do demo)
- [ ] Workspaces + membros
- [ ] Boards/Columns/Cards
- [ ] Drag-and-drop no frontend
- [ ] Realtime (WebSocket) para movimentaÃ§Ãµes/comentÃ¡rios
- [ ] RBAC por workspace (admin/member/viewer)
- [ ] Auditoria de mudanÃ§as

---

## â–¶ï¸ Rodar local
```powershell
corepack enable
corepack prepare pnpm@latest --activate

pnpm install
docker compose up -d

