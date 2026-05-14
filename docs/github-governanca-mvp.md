# Governança GitHub — App Dellas MVP

## Organização

Organização GitHub: `AppDellas`

Repositórios operacionais identificados:

- `Backend`
- `DashboardWeb`
- `Mobile`
- `Infra`
- `Intregrations`
- `Docs`
- `.github`

Observação: o repositório de integrações está nomeado como `Intregrations`. Recomenda-se avaliar renomeação futura para `Integrations`, com cuidado para não quebrar links, automações e referências existentes.

## Fluxo de trabalho

1. Toda tarefa deve nascer como issue.
2. Toda issue deve ter prioridade, área, tipo, repositório e sprint.
3. Nenhuma alteração deve ser feita diretamente em `main`.
4. Desenvolvimento deve ocorrer em branch curta e semântica.
5. Toda entrega deve passar por pull request.
6. PR deve estar vinculado à issue.
7. Alterações sensíveis devem avaliar segurança, LGPD, dados pessoais e logs.
8. Pagamentos só podem ser confirmados pelo backend via webhook validado, com assinatura, idempotência e auditoria.

## Branches

Branches protegidas:

```bash
main
develop
```

Branches de trabalho:

```bash
feature/nome-da-feature
fix/nome-do-bug
refactor/nome-da-refatoracao
docs/nome-da-documentacao
infra/nome-da-infra
hotfix/nome-do-ajuste
chore/nome-ajuste-tecnico
security/nome-ajuste-seguranca
```

## Commits

Usar Conventional Commits em português do Brasil:

```bash
feat(auth): implementa autenticação inicial com JWT
fix(api): corrige validação de payload
docs(readme): atualiza instruções de execução local
refactor(service): reorganiza camada de domínio
test(auth): adiciona testes de autenticação
chore(ci): configura pipeline de validação
security(lgpd): reforça proteção de dados pessoais
```

## Milestones recomendadas

- Sprint 01 — Fundação Técnica
- Sprint 02 — Core do MVP
- Sprint 03 — Expansão Funcional
- Sprint 04 — QA, Segurança e Entrega
- MVP — Entrega Final

## Status do GitHub Projects

Nome sugerido: `Roadmap Técnico — MVP`

Views recomendadas:

- Backlog Geral
- Sprint Atual
- Roadmap por Épico
- Board Kanban
- Por Responsável
- Por Repositório
- Por Prioridade
- Por Status
- MVP
- Pós-MVP

Campos recomendados:

- Status
- Prioridade
- Tipo
- Área
- Sprint
- Épico
- Repositório
- Estimativa
- Responsável
- Fase
- Data de início
- Data de entrega
- Bloqueado
