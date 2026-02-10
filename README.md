### Hey 👋, I'm Renzo Jared

[![](https://img.shields.io/badge/-@renzojared-%23181717?style=flat-square&logo=github)](https://github.com/renzojared)
[![](https://img.shields.io/badge/-Renzo%20Jared-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://linkedin.com/in/renzojared)
[![](https://img.shields.io/badge/-NuGet-004880?style=flat-square&logo=nuget&logoColor=white)](https://www.nuget.org/profiles/renzojared)

**Backend Developer .NET | Software Architecture Specialist**

Building enterprise systems with .NET. Specialized in microservices, event-driven architectures, and database optimization.

## Open Source Libraries

### [DotEmilu](https://github.com/renzojared/DotEmilu) [![NuGet](https://img.shields.io/nuget/v/DotEmilu?style=flat-square&logo=nuget&color=004880)](https://www.nuget.org/packages/DotEmilu)
Simple .NET library for handling HTTP requests and responses using handler-based patterns with Clean Architecture principles.
- **Features**: Handler Pattern, FluentValidation integration, async/await support, RFC 7807 Problem Details
- **Packages**: [DotEmilu](https://www.nuget.org/packages/DotEmilu) | [DotEmilu.Abstractions](https://www.nuget.org/packages/DotEmilu.Abstractions) | [DotEmilu.AspNetCore](https://www.nuget.org/packages/DotEmilu.AspNetCore)
- **Stack**: .NET 8, ASP.NET Core, FluentValidation

### [DotEmilu.EntityFrameworkCore](https://github.com/renzojared/DotEmilu.EntityFrameworkCore) [![NuGet](https://img.shields.io/nuget/v/DotEmilu.EntityFrameworkCore?style=flat-square&logo=nuget&color=004880)](https://www.nuget.org/packages/DotEmilu.EntityFrameworkCore)
EF Core library providing interceptors and auditable entities for enterprise applications.
- **Features**: CREATE/UPDATE/DELETE tracking, Soft delete support, Generic key types, Auditable entities with user context
- **Database Support**: SQL Server, Oracle, PostgreSQL
- **Stack**: .NET 8, Entity Framework Core

### [MCP PoC Collection](https://github.com/renzojared/mcp-poc) [![GHCR](https://img.shields.io/badge/ghcr-mcp--invoice--sync-blue?logo=docker)](https://github.com/renzojared/mcp-poc/pkgs/container/mcp-invoice-sync)
Model Context Protocol (MCP) server implementations using Docker for AI-powered integrations.
- **Features**: Invoice Sync MCP with event status tracking, delivery details, and subscription management
- **Package**: [mcp-invoice-sync](https://github.com/renzojared/mcp-poc/pkgs/container/mcp-invoice-sync) on GitHub Container Registry
- **CI/CD**: Multi-platform containers (linux/amd64, linux/arm64), GitHub Actions, GHCR with artifact attestation
- **Stack**: .NET 10, Docker, GitHub Container Registry

## Featured Projects

### [Clean Architecture Sales System](https://github.com/renzojared/clean-architecture)
Blazor WebAssembly + ASP.NET Core Web API implementing Clean Architecture principles for a sales order system.
- **Stack**: .NET 8, Blazor WASM, ASP.NET Core Web API, Clean Architecture
- **Features**: Order management, NuGet package development

### [Regional Government Document Manager](https://github.com/renzojared/rg-dossier)
Web application for managing government files and dossiers with secure document handling.
- **Stack**: ASP.NET Core, SQL Server, Azure

## Tech Stack

**Backend**: .NET 10/8/6, C#, ASP.NET Core (Minimal APIs & Controllers), Worker Services

**Architecture**: Clean Architecture, Vertical Slice Architecture, Microservices, CQRS, Event-Driven Architecture, DDD

**Data Access**: Entity Framework Core, Dapper, Oracle Database, SQL Server, PostgreSQL, MySQL, Redis

**Messaging & Events**: Apache Kafka, Confluent.Kafka

**Cloud & DevOps**: Azure (VMs, Key Vault, Blob Storage, Functions), AWS (EC2, S3, Lambda, RDS), Docker, GitHub Actions, IIS

**Observability**: OpenTelemetry, Serilog, Polly, Health Checks, Seq

**Tools & Libraries**: FluentValidation, Hangfire, AutoMapper, YARP, Swagger/OpenAPI, NuGet Package Development, Spectre.Console

**Frontend**: Blazor (WebAssembly/Server), MudBlazor, JavaScript, HTML5/CSS3
