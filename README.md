<div align="center">

# 👋 Hi, I'm Leo!

**Tech Lead & Senior Backend Engineer | AI-Native Engineering | Financial Market**

*Building resilient financial systems — from satellite automation at INPE to payment infrastructure at Núclea*

<p align="center">
  <a href="https://www.linkedin.com/in/leomachadop/?locale=en_US"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:leo.machadop@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://linktr.ee/leomachadop"><img src="https://img.shields.io/badge/Portfolio-39E09B?style=for-the-badge&logo=linktree&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.strava.com/athletes/leomachadop"><img src="https://img.shields.io/badge/Strava-FC4C02?style=for-the-badge&logo=strava&logoColor=white" alt="Strava"></a>
</p>

</div>

***

## 💻 Who I Am

I'm a **Tech Lead and Senior Backend Engineer with 15+ years of experience** (since 2010) building high-scale, resilient systems for the financial sector. Based in Osasco, SP — originally from São José dos Campos — I specialize in the **Java/Kotlin ecosystem**, **Python**, and **AWS cloud-native architecture**.

My career started with aerospace-grade precision at **INPE** (satellite automation) and **Embraer** (structural analysis), then evolved through the Brazilian financial ecosystem — **Getnet**, **Guiabolso**, **Dock**, **Zup**, and now **Núclea**, where I lead cross-functional engineering squads building critical financial infrastructure.

That path shaped a rare combination: **the reliability mindset of aerospace engineering applied to the speed demands of fintech**.

Currently at Núclea, my focus is acting as a **force multiplier** across squads:

- 🚀 **Mentorship & Leadership:** Elevating team performance and ensuring top-tier technical quality — both internally and through the **[Ser + Tech](https://www.sermaistechnology.com.br/)** mentorship program, where I help guide emerging talents into the tech industry.
- 📐 **Architecture:** Designing event-driven, serverless, and cloud-native solutions that power critical financial and digital ecosystems.
- 🤖 **AI-Native Culture:** Embedding AI tools not as productivity hacks, but as **standard engineering practice** — transforming how the squad designs, reviews, and ships code.
- 🛠️ **Engineering Excellence:** Fostering Clean Code, TDD, and DDD mindsets across cross-functional teams.

***

## 🦅 Harpy Finance — Autonomous Financial Planner (AFP)

> *"Most people don't have a financial information problem. They have an emotional aversion to money."*

AFP inverts the equation: the system goes to the user — not the other way around. Transactions captured from any channel (receipt photo, Telegram message, bank CSV, purchase confirmation email) are classified, enriched with real context, and delivered back as natural language analysis.

No forms. No dashboards you need to open. No financial education required.

**Why it works where others fail:** most financial tools are passive. They require the user to open the app precisely in the environment where money already feels emotionally heavy. AFP is built on a different premise: remove friction, reduce emotional load, and let the system act through a neutral, familiar channel.

What makes it unique is not just the stack — it's the behavioral foundation. AFP combines **choice architecture**, **natural language interaction**, and **autonomous AI reasoning** into a system designed for people who avoid money not because they lack information, but because engaging with it hurts.

### Five integrated modules, one Signal Router

A central **Signal Router (LLM)** classifies the intent of every input and routes it to the right module:

- **PFM** — captures, classifies, and enriches transactions from any channel. The heart of the system.
- **Market Analysis** — provides macroeconomic context through sources like BCB, IBGE, and FEBRABAN.
- **Investments** — tracks B3 and Tesouro Direto signals and positions.
- **Conversational Interface** — exposes the entire system through Telegram or CLI in natural language.
- **OPS** — integrates personal organization with Todoist and an automated Daily Planner.

### Behavioral Design Foundation

AFP is not a budgeting app with AI on top. It's a behavioral system built around the idea that the real gap in personal finance is often **motivation**, not information.

Its conceptual base draws from:

- **COM-B** — the problem is usually not capability or opportunity, but motivation.
- **EAST / MINDSPACE** — make interaction easy, timely, emotionally safe, and low-friction.
- **Kahneman** — avoid triggering negative System 1 reactions with stressful financial framing.
- **Commitment devices** — rules, defaults, and conversational contracts that protect the user from emotional decision-making.

This leads to one design principle: **AFP does not educate first. It acts first.**

### Technical Architecture

| Layer | Stack |
|---|---|
| **Core Runtime** | Python · MongoDB · AWS Lambda · SQS FIFO |
| **AI Orchestration** | Signal Router (LLM) · MCP-ready multi-agent patterns · contextual enrichment |
| **Models** | Ollama (local dev) · AWS Bedrock (production) |
| **Interfaces** | Telegram Bot API · CLI |
| **Integrations** | Pluggy · Todoist · email/CSV/receipt ingestion |
| **Analytics** | Metabase |

**Operating principle:** the MVP runs 100% locally — financial data never leaves the machine. Production migration should require changing only environment variables, with zero rewrite.

**Built for Léo first.** One real user, ADHD, real money aversion, real Tech Lead routine. What works in practice becomes product. What doesn't, gets cut.

***

## 🤖 AI Engineering Philosophy

I don't use AI tools — I **engineer with them**. There's a meaningful difference.

Tools like **Aider**, **Cursor**, **Claude Code**, and **GitHub Copilot** are my constant pair-programming partners. Not for autocomplete, but for architectural exploration, adversarial code review, and accelerating the feedback loop from idea to production-grade implementation.

My current areas of deep exploration:

- **MCP (Model Context Protocol)** — building robust agent-to-agent and agent-to-data communication layers
- **RAG architectures** — designing retrieval pipelines that actually work in production, not just demos
- **AI-assisted code review** — using models to enforce architectural standards at scale

***

## 🏦 Domain Expertise: Finance & Banking

With 15+ years in the Brazilian financial ecosystem, I've contributed to:

- **Open Finance Brazil** — Working Group participation shaping API specifications and versioning standards (Guiabolso)
- **BACEN Regulatory Compliance** — Circular 3.952, Resolution 4.734, receivables trading platforms (Getnet)
- **Core Banking Systems** — Card lifecycle management, invoice generation, high-volume transaction processing (Dock/PIER PRO)
- **Digital Payments & Anti-Fraud** — GBPay, PISP capabilities, real-time Kafka-based fraud detection (Guiabolso)
- **Financial Infrastructure** — Cross-functional microservices architecture for critical national financial systems (Núclea)

Two postgraduate specializations back this up: **Finance, Investments & Banking (PUC-RS)** and **Systems Engineering (Mackenzie)** — which lets me bridge technical decisions with real business and regulatory impact.

***

## 🛠️ Technical Stack (2026 Edition)

| Category | Technologies |
|:---|:---|
| **Languages** | Java 21+, Kotlin, Python, Golang, Angular |
| **AI Engineering** | AI Agents · MCP · RAG · Aider · Cursor · Claude Code · Bedrock · Ollama |
| **Backend & Ecosystem** | Spring Boot 4.x · Micronaut · FastAPI · Hibernate · Lombok *(strictly no `@Data`)* |
| **Cloud & Infrastructure** | AWS (EKS, ECS, Lambda, EventBridge, SQS/SNS, API Gateway) · Docker · Kubernetes · Terraform |
| **Data & Messaging** | PostgreSQL (+pgvector) · MongoDB Atlas · DynamoDB (Single-Table Design) · Kafka · Redis |
| **DevOps & Observability** | GitHub Actions · GitLab CI · Harness · Datadog · OpenTelemetry |
| **Architecture & Design** | Hexagonal/Clean Architecture · DDD · Event-Driven · Server-Driven UI |

***

## 🧭 Engineering Principles

These aren't values I list — they're constraints I actually code by:

- **Clarity over cleverness.** Code is written for humans first, machines second.
- **Architecture is a team sport.** The best decisions happen when the whole squad understands the *why*.
- **AI amplifies, it doesn't replace.** I use AI to go deeper, not to skip thinking.
- **Complexity is a debt.** Every abstraction must justify its existence.
- **Technology only scales when people scale with it.** This is why mentorship is non-negotiable for me.

***

## 🌱 Currently Exploring

- DynamoDB advanced patterns beyond Single-Table Design
- LangGraph for stateful multi-agent orchestration
- AI-assisted architectural decision records (ADRs)
- Serverless observability with OpenTelemetry on AWS Lambda

***

## 🏕️ Beyond the Code

When I'm not architecting systems, you'll find me:

- 📸 **Capturing Nature:** Amateur photographer and birdwatching enthusiast. I love exploring trails in places like Petrópolis and Santarém to photograph wildlife — with a profound admiration for the **Harpy Eagle** that inspired both my latest project and my latest tattoo.
- 🚴 **Pushing Limits:** Maintaining a high-performance routine with HIIT and indoor cycling, meticulously tracking every session on my **Garmin**.
- 🎸 **Heavy Rhythms:** Fueled by Technical Death Metal and Power Metal — **Behemoth**, **Lorna Shore**, and **Angra** are always on rotation.
- 🎮 **Gaming:** Nintendo Switch and PC sessions — optimizing builds in *Sonic* games, exploring *The Legend of Zelda*, or revisiting *Saint Seiya*.
- 🚗 **Cuisine & Road Trips:** Crafting homemade breads, exploring the best of Brazilian cuisine, and hitting the road in my **Pulse Abarth** for weekend getaways.

Proud supporter of **São Paulo FC** 🔴⚪⚫ · Happily married to my wonderful wife, **Mara** 💙

***

<div align="center">

*"The Harpy Eagle doesn't chase prey. It waits, sees clearly, and strikes with precision. That's the kind of engineer I try to be."*

</div>
