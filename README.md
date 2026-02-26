# dotNet.Basics

> A hands-on learning solution for exploring programming and .NET concepts — powered by **GitHub Copilot**.

---

## About

**dotNet.Basics** is a personal learning repository designed to break down and explain core programming principles and .NET / C# concepts with the help of GitHub Copilot as an AI pair programmer.

Whether you are new to .NET or looking to deepen your understanding, this repo walks through real-world patterns, best practices, and modern .NET features — one concept at a time.

---

## What You Will Find Here

- **ASP.NET Core Web API** fundamentals — routing, controllers, minimal APIs
- **.NET concepts** — dependency injection, middleware, configuration, logging
- **C# language features** — records, pattern matching, async/await, LINQ
- **Clean architecture patterns** — separation of concerns, layered design
- **Testing** — unit tests, integration tests
- **OpenAPI / Scalar** — API documentation and exploration

---

## Tech Stack

| Technology | Version |
|---|---|
| .NET | 10 |
| ASP.NET Core Web API | 10 |
| Scalar (API UI) | Latest |
| C# | 13 |

---

## Getting Started

### Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download)
- [Visual Studio Code](https://code.visualstudio.com/) with the C# extension
- [GitHub Copilot](https://github.com/features/copilot) (recommended)

### Run the API

```bash
# Clone the repository
git clone https://github.com/<your-username>/dotNet.Basics.git
cd dotNet.Basics

# Restore dependencies
dotnet restore

# Run the API
dotnet run --project src/dotNet.Basics.Api
```

### Explore the API

Once running, open your browser at:

- `http://localhost:5117/scalar` — Interactive API browser (Scalar UI)
- `http://localhost:5117/weatherforecast` — Sample endpoint
- `http://localhost:5117/openapi/v1.json` — Raw OpenAPI specification

---

## Project Structure

```
dotNet.Basics/
├── src/
│   └── dotNet.Basics.Api/       # ASP.NET Core Web API project
│       ├── Program.cs
│       ├── appsettings.json
│       └── Properties/
│           └── launchSettings.json
├── dotNet.Basics.sln            # Solution file
├── nuget.config                 # NuGet source configuration
├── .gitignore
└── README.md
```

---

## How GitHub Copilot Is Used

This project is built with **GitHub Copilot** as an AI pair programmer to:

- Generate boilerplate and scaffolding faster
- Explain unfamiliar .NET APIs and patterns inline
- Suggest idiomatic C# code as concepts are explored
- Help write tests and documentation
- Accelerate learning by turning questions into working code

---

## Learning Goals

- [ ] ASP.NET Core minimal API basics
- [ ] Dependency injection and service lifetimes
- [ ] Middleware pipeline
- [ ] Entity Framework Core basics
- [ ] Repository pattern
- [ ] Unit testing with xUnit
- [ ] Docker containerization

---

## License

This project is for personal learning purposes. Feel free to fork and learn along.
