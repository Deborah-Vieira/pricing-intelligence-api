# Pricing Intelligence API

API para monitoramento e análise inteligente de preços, aplicando Clean Architecture, padrões de projeto e testes.

## 📌 Objetivo
Desenvolver um sistema capaz de:
- Coletar preços de múltiplos fornecedores
- Filtrar ofertas inválidas
- Eleger a melhor oferta usando diferentes estratégias
- Registrar histórico e detectar variações significativas

## 🛠️ Tecnologias
- .NET 8 / C#
- ASP.NET Core Web API
- MediatR (CQRS)
- EF Core (SQL Server)
- Polly (Resiliência)
- FluentValidation
- Serilog
- xUnit, FluentAssertions

## 📂 Estrutura
- **Domain**: entidades e regras de negócio
- **Application**: casos de uso, validações, handlers
- **Infrastructure**: persistência e integrações
- **WebApi**: endpoints, autenticação, documentação
- **Tests**: unitários e de integração

## 🚀 Como rodar localmente
```bash
dotnet restore
dotnet build
dotnet run --project src/WebApi
