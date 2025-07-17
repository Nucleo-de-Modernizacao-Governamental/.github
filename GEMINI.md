# gemini.md

## Linguagem padrão

Sempre responda em **português brasileiro**.

## Tecnologias

- **Linguagem**: TypeScript
- **Frameworks**: React
- **Gerenciador de pacotes**: pnpm
- **Banco de dados**: Nenhum
- **ORM/ODM**: Nenhum
- **API**: Não utiliza

## Regras do projeto

1. Código limpo e padronizado (seguir ESLint/Prettier configurados).
2. Todas as respostas e comentários devem estar em **português brasileiro**.
3. Proibido o uso de bibliotecas externas que fujam do escopo do projeto.
4. Componentes devem ser funcionais e usar hooks, quando necessário.
5. Estrutura de pastas deve seguir o padrão abaixo:

```text
.github/
├── profile/
│   └── README.md            → Aparece na página pública da organização
├── ISSUE_TEMPLATE/
│   ├── bug_report.md        → Template para reportar bugs
│   ├── feature_request.md   → Template para pedir funcionalidades
│   └── config.yml           → Configura como os templates aparecem
├── PULL_REQUEST_TEMPLATE.md → Template padrão para PRs
├── workflows/
│   └── ci.yml               → GitHub Actions: CI, Lint, Build etc.
├── CODEOWNERS               → Define responsáveis por partes do código
├── FUNDING.yml              → Link para doações (opcional)
└── SECURITY.md              → Política de segurança e contato
