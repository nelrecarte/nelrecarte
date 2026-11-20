# Hi, I'm Nelson Recarte

Backend developer based in San Pedro Sula, Honduras. I build APIs and data-driven features for production business software with **C#/.NET**, **Node.js** and **PostgreSQL**, with a focus on correctness and reliability: transactional data handling, tested features, and tracing production issues to their root cause.

- Associate Software Developer at **Creative Information Technologies**
- Studying Ingeniería en Informática (Computer Engineering) at **CEUTEC**
- Fluent in English and Spanish, open to remote opportunities

## Featured project: TCG Marketplace (Honduras)

A trading card marketplace (5 games, singles and sealed) with a seller portal and warehouse consignment, in progress toward an invite-only beta. The repository is private; a walkthrough is available on request.

- **NestJS** API on **PostgreSQL** (Drizzle) with a hexagonal architecture: 13 domain modules, each owning its own schema, connected through a transactional outbox and a background worker
- Money stored as integer minor units with banker's rounding; payments by bank transfer, cash and card (3-D Secure gateway)
- Typed API contracts shared with three Next.js frontends; 199 unit and integration tests on real Postgres, 40 Playwright end-to-end tests, and CI with architecture boundary checks

## Tech stack

**Backend:** C# · ASP.NET Core / .NET 8 · Entity Framework Core · Node.js · NestJS · REST APIs  
**Data:** PostgreSQL · SQL · query optimization · data migrations  
**Cloud & tools:** AWS (Lambda, ECS, S3) · Docker · Git · Azure DevOps · Postman  
**Testing:** Vitest · Playwright · unit, integration and end-to-end testing  
**Frontend (secondary):** TypeScript · Angular · React

## Contact

[LinkedIn](https://www.linkedin.com/in/nelson-recarte)
