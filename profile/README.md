# 🌸 App Dellas

> **Empoderando a economia local através da tecnologia.**

O **App Dellas** é um ecossistema digital completo projetado para facilitar o marketplace, a conexão e a gestão de serviços e produtos. Com uma arquitetura moderna e robusta, o projeto une a agilidade do Mobile à precisão de um Dashboard administrativo centralizado.

---

## 🏗️ Arquitetura do Ecossistema

O projeto é dividido em **6 pilares fundamentais**, cada um com seu repositório dedicado para garantir escalabilidade e manutenção independente:

| Repositório | Descrição | Stack Principal |
| :--- | :--- | :--- |
| [**Backend**](https://github.com/AppDellas/Backend) | API RESTful central e orquestração de negócios. | FastAPI, PostgreSQL, Redis |
| [**Mobile**](https://github.com/AppDellas/Mobile) | Aplicativo nativo para usuárias finais e profissionais. | Flutter, Riverpod |
| [**DashboardWeb**](https://github.com/AppDellas/DashboardWeb) | Painel administrativo e governança operacional. | Next.js, TypeScript, Tailwind |
| [**Infra**](https://github.com/AppDellas/Infra) | Orquestração, Staging, HTTPS e CI/CD. | Docker, Nginx, Actions |
| [**Intregrations**](https://github.com/AppDellas/Intregrations) | Adaptadores de Pagamento, Push e Webhooks. | SDKs Externos, FastAPI |
| [**Docs**](https://github.com/AppDellas/Docs) | Fonte de verdade documental e marcos do projeto. | Markdown |

---

## ⚡ Stack Tecnológica Consolidada

Trabalhamos com o que há de mais moderno para entregar uma experiência premium:

- **Frontend & Admin**: [Next.js 14+](https://nextjs.org/) com App Router, TypeScript e [Tailwind CSS](https://tailwindcss.com/) para interfaces ultra-rápidas.
- **Mobile**: [Flutter](https://flutter.dev/) para uma experiência fluida em Android e iOS a partir de uma única base de código.
- **Backend API**: [FastAPI](https://fastapi.tiangolo.com/) de alta performance com autenticação JWT e validação Pydantic.
- **Persistência**: [PostgreSQL](https://www.postgresql.org/) para dados relacionais e [Redis](https://redis.io/) para cache e sessões rápidas.
- **DevOps**: [Docker](https://www.docker.com/) e [GitHub Actions](https://github.com/features/actions) para deploy contínuo em VPS Hostinger com SSL Let's Encrypt.

---

## 📅 Roadmap e Estado Atual (Sprint 3)

Atualmente estamos na **Sprint 3**, focada na entrega do **Marketplace e Ferramentas de Moderação**.

- [x] **Sprint 1 (Fundação)**: Ambientes configurados, CI/CD operacional e Autenticação (JWT) funcionando em todas as plataformas.
- [x] **Sprint 2 (Core UI)**: App com Feed/Perfil funcional e Dashboard Admin com KPIs e Gestão de Usuários.
- [/] **Sprint 3 (Marketplace - ATIVA)**:
    - [x] Implementação de Modelos e Endpoints de Anúncios no Backend.
    - [x] Interface de Gestão e Moderação de Anúncios no DashboardWeb.
    - [ ] Listagem e criação de anúncios no App Mobile (Em progresso).
- [ ] **Sprint 4 (Financeiro)**: Pagamentos, Checkout e Integração Stripe.
- [ ] **Sprint 5 (Engajamento)**: Push Notifications e Relatórios Avançados.
- [ ] **Sprint 6 (Polimento)**: Segurança final, Otimização e Go-Live.

---

## 🎨 Identidade Visual

O ecossistema segue o [Guia de Identidade Visual](https://github.com/AppDellas/Docs/blob/main/docs/visual_identity_guide.md) consolidado na Sprint 1:
- **Cores**: Gradientes Pink/Purple, Canvas Silver (`#F8FAFC`).
- **Estética**: Micro-animações, Cards com bordas arredondadas e design *premium glassmorphism*.

---

## 📬 Contato e Governança

Para detalhes operacionais ou acesso à documentação de arquitetura, consulte o repositório [**Docs**](https://github.com/AppDellas/Docs).

---
© 2026 App Dellas — All Rights Reserved.
