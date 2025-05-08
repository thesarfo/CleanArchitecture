### Clean Architecture Template

This is a modular .NET solution structured around **Domain-Driven Design (DDD)** principles, with a complete implementation of clean architecture layers:

#### What's Included

* **SharedKernel**: Common DDD abstractions
* **Domain Layer**: Sample entities and core domain logic
* **Application Layer**:

  * CQRS patterns
  * Use case abstractions
  * Cross-cutting concerns (logging, validation)
* **Infrastructure Layer**:

  * Authentication & permission-based authorization
  * EF Core with PostgreSQL
  * Structured logging with Serilog and Seq (`http://localhost:8081`)
  * Distributed caching with Redis
  * OpenTelemetry for observability
  * Outbox pattern for reliable messaging
* **API**:

  * Versioning support
* **Testing**:

  * Unit, functional, and integration tests
  * Architecture tests to enforce DDD boundaries