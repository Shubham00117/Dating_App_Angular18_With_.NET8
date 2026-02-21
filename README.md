# 💕 Dating App — Angular 18 + .NET 8

A full-stack **dating application** built with **Angular 18** on the frontend and **.NET 8 Web API** on the backend, using **Entity Framework Core** with SQLite.

---

## 📖 Overview

This project is a dating application following a course-based approach to learn full-stack web development. It demonstrates building a RESTful API with .NET 8, connecting to a database via Entity Framework Core, and scaffolding the initial backend architecture.

---

## 📂 Project Structure

```
Dating_App_Angular18_With_.NET8/
├── DatingApp.sln                       # .NET Solution file
└── API/
    ├── API.csproj                      # .NET 8 project file
    ├── Program.cs                      # Application entry point
    ├── Controllers/
    │   ├── UsersController.cs          # User API endpoints
    │   └── WeatherForecastController.cs
    ├── Data/
    │   ├── DataContext.cs              # EF Core database context
    │   └── Migrations/                 # Database migrations
    ├── Entities/
    │   └── AppUser.cs                  # User entity model
    ├── Properties/
    │   └── launchSettings.json
    ├── appsettings.Development.json
    └── dating.db                       # SQLite database
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Backend** | .NET 8, C#, ASP.NET Core Web API |
| **ORM** | Entity Framework Core |
| **Database** | SQLite |
| **Frontend** | Angular 18 (planned) |

---

## 🚀 Getting Started

### Prerequisites
- .NET 8 SDK
- Node.js 18+ (for Angular)

### Running the API
```bash
cd API
dotnet restore
dotnet run
```

The API will be available at `https://localhost:5001`

---

## 📜 License

This project is open source and available for educational purposes.
