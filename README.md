# Hi, I’m Alex

### Full-Stack Developer · C# / .NET · Backend-focused

I build web applications with a strong focus on backend development using C# and .NET.
I enjoy designing REST APIs, working with databases, and bringing complete products together
from the backend to the user interface.

<p align="left">
  <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js" />
</p>

## Tech I work with

| Area | Technologies |
|---|---|
| Backend | C#, .NET, ASP.NET Core Web API, REST APIs, Entity Framework Core |
| Data & authentication | PostgreSQL, EF Core, JWT |
| Frontend | Blazor Server, Vue.js, HTML, CSS |
| DevOps & tools | Docker, Docker Compose, Git, GitHub Actions, Nginx |

## Featured project

### 📸 [PhotoSite — Photography Portfolio Platform](https://github.com/AlexYakovl/Diploma)

A production-oriented full-stack portfolio with a public gallery and an administration dashboard.

**Stack:** ASP.NET Core Web API · Blazor Server · PostgreSQL · Entity Framework Core · Docker Compose · Nginx

**Highlights:**

- Album and category management
- Image uploads and server-side resizing
- Review moderation
- JWT authentication
- Dockerized three-service deployment
- Automated testing and CI

<p align="left">
  <a href="https://github.com/AlexYakovl/Diploma">
    <img src="https://img.shields.io/badge/View_project-181717?style=for-the-badge&logo=github&logoColor=white" alt="View PhotoSite repository" />
  </a>
  <a href="https://github.com/AlexYakovl/Diploma/actions/workflows/tests.yml">
    <img src="https://github.com/AlexYakovl/Diploma/actions/workflows/tests.yml/badge.svg" alt="PhotoSite test workflow" />
  </a>
</p>

## Testing

The PhotoSite repository includes a **45-case NUnit test suite**:

- **5 unit tests** for model and DTO validation;
- **40 integration API tests** using `WebApplicationFactory`;
- Isolated SQLite in-memory database;
- Test authentication handler that does not alter production authorization;
- GitHub Actions pipeline for restore, build, test execution and TRX artifacts.

API coverage includes login and JWT, protected/public endpoints, categories, albums, photos,
review moderation, Hero and About sections, invalid input and missing resources.

Commands:

```powershell
dotnet test PhotoSite.sln --configuration Debug
dotnet test PhotoSite.Api.Tests/PhotoSite.Api.Tests.csproj --configuration Debug
```

📖 [Testing documentation](https://github.com/AlexYakovl/Diploma/blob/main/docs/TESTING.md)

## Current focus

- Backend architecture and API design
- Data persistence with EF Core and PostgreSQL
- Automated quality gates and CI
- Building practical, maintainable full-stack applications

## Connect

- GitHub: [@AlexYakovl](https://github.com/AlexYakovl)
- Featured repository: [PhotoSite / Diploma](https://github.com/AlexYakovl/Diploma)

<p align="center">
  <i>Thanks for visiting — feel free to explore my repositories.</i>
</p>
