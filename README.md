# Olá, eu sou Thiago Belagamba Bueno 👋

**Desenvolvedor Full-Stack** · **Estudante de Ciência da Computação** (7º semestre)

Construo produtos SaaS **self-hosted** de ponta a ponta — APIs hexagonais, frontends React/Next.js, workers assíncronos e infraestrutura Docker. Foco em **automação de backend**, **segurança de APIs**, **web scraping** e **DevOps**.

[English version below](#-hi-im-thiago-belagamba-bueno-)

---

## Sobre mim

Desenvolvedor solo responsável por **três linhas de produto** sob o ecossistema [Publix IA](https://publix.ia.br): **Disparo Rápido**, **Lead Rápido** e **Push Rápido** — da API ao site, passando por CRM, extensão Chrome e painéis administrativos.

Mentalidade **security-first**: JWT com controle de sessões, rate limiting, device fingerprinting, score de risco e RASP. Prefiro **PostgreSQL local**, **Docker** e **workers em background** em vez de dependência de BaaS.

---

## Stack tecnológica

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)

| Área | Tecnologias |
|------|-------------|
| **Backend** | Express, Fastify, Inversify (DI), arquitetura hexagonal, OpenTelemetry |
| **Frontend** | React, Vite, Next.js, Tailwind, shadcn/ui, TanStack Query |
| **Dados** | PostgreSQL, Knex/Prisma, Redis, Supabase |
| **Async** | RabbitMQ, workers dedicados, jobs de reconciliação |
| **Pagamentos** | Asaas (assinaturas, PIX automático, webhooks) |
| **Infra** | Docker, Portainer, Netlify, n8n |
| **Extensões** | Chrome MV3, @wppconnect/wa-js |
| **Docs** | LaTeX / LuaLaTeX (Overleaf), Swagger |

---

## Produtos que construí

### Disparo Rápido — Automação WhatsApp
> [disparorapido.com.br](https://disparorapido.com.br) · Ecossistema completo

| Componente | Descrição |
|------------|-----------|
| **API** | Backend hexagonal com billing Asaas, webhooks, alocação de leads mensais, jobs de reconciliação e OpenTelemetry |
| **CRM** | Console multi-tenant: campanhas, funil, assinaturas, créditos, afiliados, lead-agent com IA |
| **Extensão Chrome** | Disparo em massa no WhatsApp Web — auth JWT, LID resolution, rate limiting e anti-ban |
| **Site** | Landing pages, checkout, funis de afiliados e SEO agent-first |

---

### Lead Rápido — Geração de Leads B2B
> Plataforma comercial de venda de listas empresariais · TCC

| Componente | Descrição |
|------------|-----------|
| **API** | Catálogo público, cotação, checkout Asaas e API interna de alocação de leads |
| **Site** | Catálogo com filtros por estado/segmento, checkout in-page e blog MDX |

---

### Push Rápido — Notificações Web Push
> Plataforma self-hosted de push notifications

| Componente | Descrição |
|------------|-----------|
| **API + Worker** | Monorepo Fastify com filas RabbitMQ, SDK embeddable e dispatch throttled |
| **Admin** | Dashboard Next.js para sites, inscrições e campanhas |

---

### TraceGuard — Observabilidade & Segurança *(TCC)*
> Plataforma APM com tracing distribuído, alertas e RASP

- Ingestão de telemetria com `AsyncLocalStorage` e dashboard em tempo real via WebSocket
- Middleware RASP: detecção de bots, rate limiting e bloqueio de scans sequenciais
- Monorepo pnpm: backend, dashboard, SDK embeddable e módulo de uptime monitoring

---

### Projetos para clientes

| Projeto | Stack | Destaque |
|---------|-------|----------|
| **JECON Consórcios** | Next.js 15, App Router | Simulador de consórcio, captura de leads e webhook de abandono (n8n) |
| **Publix IA** | React, Vite | Landing institucional com animações e formulário de propostas |

---

## O que isso demonstra

- **Full-stack solo**: da modelagem SQL ao deploy em produção
- **Arquitetura limpa**: hexagonal com DI, feature-based modules, separação API/worker
- **Monetização real**: assinaturas, créditos, afiliados, marketplace e venda direta de leads
- **Segurança aplicada**: sessões, fingerprinting, rate limiting, score de risco e RASP
- **Automação em escala**: webhooks, jobs de background, dispatch em massa e push campaigns

---

## Princípios de arquitetura

| Princípio | Abordagem |
|-----------|-----------|
| **Autonomia** | Self-hosted, containerizado, controle total da infra |
| **Segurança** | JWT, rate limiting, device licensing, RASP e métricas de risco |
| **Eficiência** | SQL otimizado, filas assíncronas e workers para carga pesada |
| **Colaboração** | Código tipado, documentado e pronto para revisão em equipe |

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thiago-belagamba-bueno/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/ThiagoBelagamba)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:thiagobelagambacontato@gmail.com)

---

<br />

# 👋 Hi, I'm Thiago Belagamba Bueno

**Full-Stack Developer (Remote)** · **Computer Science Student** (7th semester)

I build **self-hosted SaaS products** end-to-end — hexagonal APIs, React/Next.js frontends, async workers, and Docker infrastructure. Focused on **backend automation**, **API security**, **web scraping**, and **DevOps**.

[Versão em português acima](#-olá-eu-sou-thiago-belagamba-bueno-)

---

## About me

Solo developer behind **three product lines** under the [Publix IA](https://publix.ia.br) ecosystem: **Disparo Rápido**, **Lead Rápido**, and **Push Rápido** — from API to marketing site, CRM, Chrome extension, and admin dashboards.

**Security-first** mindset: JWT session control, rate limiting, device fingerprinting, risk scoring, and RASP. I prefer **local PostgreSQL**, **Docker**, and **background workers** over BaaS dependencies.

---

## Tech stack

| Area | Technologies |
|------|-------------|
| **Backend** | Express, Fastify, Inversify (DI), hexagonal architecture, OpenTelemetry |
| **Frontend** | React, Vite, Next.js, Tailwind, shadcn/ui, TanStack Query |
| **Data** | PostgreSQL, Knex/Prisma, Redis, Supabase |
| **Async** | RabbitMQ, dedicated workers, reconciliation jobs |
| **Payments** | Asaas (subscriptions, automatic PIX, webhooks) |
| **Infra** | Docker, Portainer, Netlify, n8n |
| **Extensions** | Chrome MV3, @wppconnect/wa-js |

---

## Products I built

### Disparo Rápido — WhatsApp Automation
Full ecosystem: hexagonal API with Asaas billing, multi-tenant CRM, Chrome extension for bulk messaging, and conversion-focused marketing site.

### Lead Rápido — B2B Lead Generation
Commercial lead sales platform with public catalog API, in-page checkout, and internal lead allocation — also my graduation thesis.

### Push Rápido — Web Push Notifications
Self-hosted push platform with Fastify API, RabbitMQ workers, embeddable SDK, and Next.js admin dashboard.

### TraceGuard — Observability & Security *(Capstone)*
APM platform with distributed tracing, real-time WebSocket dashboard, alert fatigue mitigation, and RASP middleware.

### Client projects
**JECON Consórcios** (Next.js consortium simulator + lead capture) · **Publix IA** (institutional landing page)

---

## What this demonstrates

- **Solo full-stack**: from SQL modeling to production deployment
- **Clean architecture**: hexagonal with DI, feature modules, API/worker separation
- **Real monetization**: subscriptions, credits, affiliates, marketplace, direct lead sales
- **Applied security**: sessions, fingerprinting, rate limiting, risk scoring, RASP
- **Automation at scale**: webhooks, background jobs, bulk dispatch, push campaigns

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thiago-belagamba-bueno/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/ThiagoBelagamba)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:thiagobelagambacontato@gmail.com)

---

<sub>Last updated: July 2026</sub>
