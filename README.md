# Clean Architecture .NET API

This project demonstrates a production-ready ASP.NET Web API built using Clean Architecture principles.

## Architecture
- API: HTTP layer (controllers, filters)
- Application: use cases, DTOs, validation
- Domain: core business rules
- Infrastructure: data access, external services

## Key Design Decisions
- Clean separation of concerns for long-term maintainability
- CQRS-style use cases for clarity
- Dapper used for read-heavy queries, EF Core for writes
- Centralized error handling and validation

## Features
- RESTful API with versioning
- JWT authentication & role-based access
- Pagination, filtering, and sorting
- SQL Server integration

## Testing
- Unit tests for core business logic
- Integration tests for API endpoints

## Why This Project
This repository reflects how I design scalable, maintainable APIs in real-world enterprise and SaaS systems.
