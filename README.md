<div align="center">

# Hi, I'm Ram Namburi 👋

### Senior .NET backend engineer — C# · ASP.NET Core · SQL Server / PostgreSQL · Azure · messaging

13+ years building enterprise backend systems in logistics, financial services, and procurement SaaS.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ramnamburi9-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ramnamburi9/)
[![GitHub](https://img.shields.io/badge/GitHub-RamNamburi9-181717?style=for-the-badge&logo=github)](https://github.com/RamNamburi9)
[![Website](https://img.shields.io/badge/Website-ramnamburi.com-10B981?style=for-the-badge&logo=google-chrome&logoColor=white)](https://ramnamburi.com)

[**Portfolio and engineering case studies**](https://ram-engineering-portfolio.vercel.app)

</div>

## What I build

- ASP.NET Core services and REST APIs with explicit domain boundaries, dependency injection, and tests you can trust
- Data-correct systems on EF Core + SQL Server / PostgreSQL: transactions, isolation levels, optimistic concurrency, idempotent writes
- Event-driven integration — transactional outbox, at-least-once consumers, inbox deduplication — over Azure Service Bus and RabbitMQ, with Kafka in the lab
- Workflow orchestration (Camunda BPMN) and high-volume document pipelines (10,000+ files/day)
- Azure at the application level: App Service, Functions, Logic Apps, Azure DevOps pipelines
- Shared NuGet packages and libraries that make other teams faster

## .NET reference implementations

| Project | What it demonstrates | Stack |
|---|---|---|
| [TraceLedger demo](https://traceledger-demo.onrender.com) | Synthetic embedded-finance workflows, deterministic ledger/holds, tenant-scoped idempotency and reviewed operational AI. Public demo is read-only and labeled Replay; implementation source remains private. | .NET 10, ASP.NET Core, Angular, PostgreSQL |
| [Trade Surveillance Lab](https://github.com/RamNamburi9/trade-surveillance-lab) | Idempotent ingestion, transactional outbox, deterministic rules and immutable alert evidence. The README reports 154 unit tests in CI; the PostgreSQL integration suite has its own local scope. | .NET 10, ASP.NET Core, Angular, EF Core, PostgreSQL |
| [Incident Intelligence Workbench](https://github.com/RamNamburi9/incident-intelligence-workbench) | Auditable imports, controlled review, deterministic dashboards and versioned report snapshots over synthetic incident data. | .NET 10, Razor Pages, EF Core, SQL Server / SQLite, SignalR |
| [Azure App Service API Demo](https://github.com/RamNamburi9/AzureAppSerivce) | Minimal Web API with Microsoft Entra ID authentication, CORS, and App Service hosting | ASP.NET Core, Azure |
| [Secure Blazor Client](https://github.com/RamNamburi9/SecureBlazorUIApp) | Blazor WebAssembly client calling a protected API with MSAL tokens (historical proof of concept) | Blazor, MSAL |

These engineering reference implementations use synthetic data. They show architecture and testing choices, not employer systems, production readiness or regulatory certification. TraceLedger has a bounded public read-only deployment; its full platform backlog remains open.

## Applied AI

[**Evidence Triage Engine**](https://github.com/RamNamburi9/evidence-triage-engine) — a Python prototype with typed evidence, constrained investigation tools, grounding validation, replayable traces and explicit escalation. Its offline fixtures are separate from live model or production-connector claims.

The newer projects use AI-assisted development. I keep generated explanations separate from deterministic decisions, source records and executed checks. A project test result is bounded evidence of software behavior, not a certification of personal mastery.

## Learning and practice

[**Career OS**](https://ramnamburi9.github.io/careeros-portal/) — a backend curriculum covering transactions and isolation, messaging and the outbox pattern, Kafka, memory/GC and system design, with runnable C# labs and drills.

My personal learning labs and practice records stay private. I use a prediction, a small change, a failure/recovery experiment and an explanation in my own words as a practice loop. The [public portfolio](https://ram-engineering-portfolio.vercel.app) carries selected project evidence and current limits.

## Tooling

[ToolPilot](https://github.com/RamNamburi9/ToolPilot) — a VS Code extension I published on the [Marketplace](https://marketplace.visualstudio.com/items?itemName=rnamburi.toolpilot). I use agentic coding tools daily as working practice; the engineering judgment stays mine.

## Technologies

<p>
  <img alt="C#" src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white">
  <img alt=".NET" src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white">
  <img alt="ASP.NET Core" src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white">
  <img alt="SQL Server" src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Azure" src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white">
  <img alt="Azure DevOps" src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
</p>

## Engineering principles

- Correctness first: transactions, idempotency, and auditability are designed in, not patched on.
- Keep private data, credentials, generated files, and environment identifiers out of source control.
- Design automation with dry runs, small blast radiuses, observable results, and recovery paths.
- Publish honest project status, reproducible setup instructions, and known limitations.

<div align="center">

![Ram's GitHub stats](https://github-readme-stats.vercel.app/api?username=RamNamburi9&show_icons=true&hide_border=true&theme=transparent)

</div>
