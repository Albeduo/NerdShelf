# Roadmap — NerdShelf

Este roadmap organiza o projeto em **fases semanais**, com foco em aprendizado técnico e pessoal.

Cada semana só é considerada concluída quando houver:  
**código + teste + documentação + commit + revisão.**

---

## ⏱️ Ritmo

- 6–8 horas por semana  
- Duração estimada: 36–42 semanas  
- Regra: não compensar semanas perdidas dobrando a próxima — apenas registrar e seguir.

---

## 🧭 Fases

| Fase         | Semanas | Objetivo                    |
| ------------ | ------: | --------------------------- |
| Fundação     |     1–2 | Organização e ambiente      |
| Frontend     |     3–6 | React/Next/Tailwind         |
| Backend      |    7–12 | NestJS/PostgreSQL           |
| Coleção      |   13–16 | Inteligência da coleção     |
| Catálogo     |   17–22 | APIs externas               |
| Deck Builder |   23–27 | Regras de TCG               |
| Qualidade    |   28–32 | Testes/CI/segurança         |
| Expansão     |   33–36 | Outros TCGs + colecionáveis |

---

## 🧱 Primeiras semanas

### Semana 01 — Fundação
- Criar documentação inicial:
  - `README.md`
  - `ROADMAP.md`
  - `LICENSE`
  - `CONTRIBUTING.md`
  - `docs/`
  - `.github/`
- Aprendizado: Git, GitHub, Issues, Pull Requests, documentação.
- Commit: `chore: initialize project documentation and workflow`

---

### Semana 02 — Ambiente
- Configurar:
  - Node.js
  - pnpm
  - Next.js
  - TypeScript
  - Tailwind
  - ESLint
  - Prettier
  - Docker
- Commit: `chore: configure development environment`

---

### Semana 03 — Application Shell
- Criar estrutura inicial:
  - Sidebar
  - Header
  - Layout
  - Routing
  - Theme
  - Responsividade
- Commit: `feat: create application shell`

---

### Semana 04 — Design System
- Implementar componentes base com shadcn/ui:
  - Buttons
  - Cards
  - Dialog
  - Inputs
  - Badges
  - Tables
  - Loading
  - Empty states
  - Error states
- Commit: `feat: establish ui component foundation`

---

## 🧩 Weekly Review

Ao final de cada semana, responder:

1. O que eu construí?  
2. O que eu aprendi?  
3. O que deu errado?  
4. O que eu faria diferente?  
5. Qual será meu próximo passo?

Documentar em `docs/weekly/week-XX.md`.

---

## 🚀 MVPs

- **MVP técnico (~12–16 semanas):** frontend + backend + banco + coleção + dashboard.  
- **MVP funcional (~22–27 semanas):** catálogo real + 3 TCGs + wishlist + deck builder.  
- **Projeto completo (~36–42 semanas):** 6 TCGs + Funko + Gundam + testes + CI + documentação.  
