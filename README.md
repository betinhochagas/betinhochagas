# Roberto Chagas

**Desenvolvedor Full Stack** · TypeScript · Node.js/NestJS · React · C#/.NET · IA aplicada

Blumenau, SC · Fundador da [BNU Tech](https://bnutech.com.br)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-roberto--chagas--dev-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/roberto-chagas-dev)
[![BNU Tech](https://img.shields.io/badge/BNU_Tech-bnutech.com.br-1a3c5e?style=flat-square&logo=googlechrome&logoColor=white)](https://bnutech.com.br)
[![Email](https://img.shields.io/badge/Email-contato-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:robertochagas.ti@gmail.com)

---

## Sobre mim

13 anos de TI. Comecei em suporte e infraestrutura, inclusive em ambiente hospitalar 24x7, e desde
2024 desenvolvo sistemas completos, do banco ao deploy. Construo as ferramentas que eu mesmo precisava
quando estava do outro lado, atendendo o usuário.

Desenvolvo com **Claude Code** no dia a dia, dentro de um método: memória de projeto versionada
(`CLAUDE.md`), sessões com começo e fim, decisões registradas em ADR e CI como portão de qualidade.
A IA acelera; a decisão e a responsabilidade pelo código são minhas.

---

## Sistemas em produção

O código fica em repositório privado porque os sistemas rodam com dados reais de clientes. O que dá para mostrar está linkado.

| Sistema | O que é | Escala | Stack |
|---|---|---|---|
| **RVCAR / Moven** · [vitrine técnica](https://github.com/betinhochagas/rvcar-system-vitrine) | SaaS multi-tenant de gestão de locação de veículos para motoristas de app | 2.965 commits · ~182 mil linhas · +6.700 casos de teste · 60 ADRs | NestJS · React 19 · PostgreSQL · Prisma · BullMQ · Docker |
| **Portal da TI (OrbIT)** · [vitrine](https://github.com/betinhochagas/Portal-da-TI) | Gestão de ~750 estações Windows num hospital, com assistente de IA (function calling) | ~85 mil linhas em C#, TypeScript e PowerShell | ASP.NET Core (.NET 10) · Next.js · Semantic Kernel |
| **Fabiana Beauty Hair** · [site](https://www.fmbeautyhair.com.br) | Agendamento online para salão, com sinal via PIX e painel administrativo | Em produção | Cloudflare Workers · D1 · TanStack Start · Mercado Pago |

---

## Código aberto

| Repositório | O que mostra |
|---|---|
| [**varejo-mcp**](https://github.com/betinhochagas/varejo-mcp) | Servidor **MCP** em TypeScript: tools somente leitura sobre uma base de vendas, sem SQL livre, testes ponta a ponta com o cliente MCP oficial |
| [**prospeccao-ia-claude**](https://github.com/betinhochagas/prospeccao-ia-claude) | Dois agentes em Python com a **API do Claude**: modelo escolhido por custo/tarefa, visão multimodal, contabilidade de token, dry-run de custo zero |
| [**portfolio-analise-varejo**](https://github.com/betinhochagas/portfolio-analise-varejo) | Análise de dados ponta a ponta: ETL em Python, SQL, dbt, BigQuery, Airflow, Power BI e Looker Studio |

---

## IA aplicada

- **Agente com function calling em produção:** Semantic Kernel (.NET), 6 tools, **todas somente leitura**. O backend executa ações remotas, mas nenhuma foi exposta ao modelo.
- **API do Claude:** modelo por tarefa (Haiku × Sonnet), visão multimodal, streaming, controle de custo por chamada.
- **MCP:** servidores configurados em projeto real (Railway, Vercel, Sentry) e um servidor próprio publicado.
- **OCR local por LGPD:** Tesseract.js (WebAssembly) no navegador, para o documento do usuário não sair da máquina.

---

## Stack

**Backend:** TypeScript · Node.js · NestJS · C# / ASP.NET Core · Python · PostgreSQL · Prisma · Redis/BullMQ

**Frontend:** React 19 · Next.js · Vite · TanStack · Tailwind CSS

**Infra:** Docker · GitHub Actions · AWS S3 · Railway · Vercel · Cloudflare

**IA:** Claude API · Claude Code · MCP · Semantic Kernel · Tesseract.js

---

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=betinhochagas&show_icons=true&theme=github_dark&hide_border=true&count_private=true)
