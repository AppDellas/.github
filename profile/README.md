# App Dellas

Della's Community e um ecossistema digital para conectar, apoiar e transformar a jornada de mulheres brasileiras e hispanicas no exterior, com foco inicial nos Estados Unidos.

O produto combina comunidade, feed social, eventos, negocios locais, classificados, notificacoes, moderacao, painel administrativo e infraestrutura de entrega em uma arquitetura multi-repositorio.

## Posicionamento

- Conectar. Apoiar. Transformar.
- Mais que um app: um ecossistema de comunidade, oportunidades e pertencimento.
- MVP V1 orientado por escopo executivo, roadmap Scrum/TDD e documentacao central no repositorio `Docs`.

## Repositorios

| Repositorio | Responsabilidade | Stack atual |
|---|---|---|
| [Backend](https://github.com/AppDellas/Backend) | API central, autenticacao, usuarios, marketplace, pedidos, pagamentos, notificacoes, LGPD, auditoria e contratos administrativos. | FastAPI, SQLAlchemy, Alembic, PostgreSQL, Redis, JWT, Stripe, Pytest |
| [Mobile](https://github.com/AppDellas/Mobile) | Aplicativo Flutter para usuarias finais, com onboarding, auth, perfil, feed, marketplace, pedidos, notificacoes e modulos sociais em evolucao. | Flutter, Dart, Riverpod, go_router |
| [DashboardWeb](https://github.com/AppDellas/DashboardWeb) | Painel administrativo para operacao, moderacao, usuarios, anuncios, pedidos, pagamentos, campanhas, relatorios e LGPD. | Next.js, React, TypeScript, Tailwind, Vitest |
| [Infra](https://github.com/AppDellas/Infra) | Ambientes, Docker, Nginx, HTTPS, pipelines, deploy, backups, observabilidade e runbooks operacionais. | Docker, Nginx, GitHub Actions, VPS Hostinger |
| [Intregrations](https://github.com/AppDellas/Intregrations) | Servicos e adaptadores externos, incluindo dispatch FCM e futuras integracoes transacionais. | FastAPI, Firebase Admin SDK, HTTP interno |
| [Docs](https://github.com/AppDellas/Docs) | Fonte canonica de escopo, roadmap, sprints, contratos, runbooks, auditorias e governanca documental. | Markdown, PDF, scripts de geracao |

> Nota: `Intregrations` preserva a grafia real do repositorio no GitHub. A grafia de dominio esperada e `Integrations`.

## Roadmap e status atual

O roadmap publico anterior indicava Sprint 3 como ativa. A documentacao foi reconciliada em 20/05/2026 com o escopo `Della's Community`, o estado real dos repositorios e o roadmap de conclusao.

Estado consolidado:

- Sprints 1 a 3: base tecnica, autenticacao, dashboard inicial e marketplace principal ja documentados como entregas historicas ou operacionais.
- Sprints 4 a 6: pagamentos, notificacoes, LGPD, seguranca e go-live em consolidacao documental e tecnica.
- Roadmap de conclusao: estende o planejamento operacional para cobrir core social completo, comunidades, eventos, chat, observabilidade, CI/CD, homologacao e go-live assistido.

Fonte de verdade: [Docs](https://github.com/AppDellas/Docs).

## Principios de engenharia

- Documentacao e codigo devem evoluir juntos.
- Backend e o ponto de verdade para seguranca, RBAC, pagamentos, LGPD e auditoria.
- Mobile e DashboardWeb nao devem confirmar pagamentos, privilegios ou status sensiveis sem validacao da API.
- Secrets, `.env`, tokens, chaves, dados pessoais e credenciais reais nunca devem ser versionados.
- Mudancas funcionais devem ter testes, evidencia de validacao e atualizacao documental.

## Documentacao principal

- [Repositorio Docs](https://github.com/AppDellas/Docs)
- [Indice documental](https://github.com/AppDellas/Docs/blob/main/docs/indice.md)
- [Guia de identidade visual](https://github.com/AppDellas/Docs/blob/main/docs/visual_identity_guide.md)
- [Roadmap de conclusao](https://github.com/AppDellas/Docs/blob/main/docs/roadmaps/Roadmap_Conclusao_Projeto_Dellas_Community.pdf)

(c) 2026 App Dellas. All rights reserved.
