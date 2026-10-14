# ASP.NET Core 5.0 Layered Architecture Project

## About
This project is a web application developed with ASP.NET Core 5.0 and C#.
It demonstrates a layered architecture and separates application responsibilities
into different projects.

## Technologies
- C#
- ASP.NET Core 5.0
- Entity Framework Core
- Microsoft SQL Server
- ASP.NET Core Web API
- Swagger / OpenAPI
- Layered Architecture
- Repository Pattern

## Project Structure
- `Core_Proje` - MVC web application and user interface
- `Core_Proje_Api` - Web API
- `DataAccessLayer` - Data access and Entity Framework Core operations
- `EntityLayer` - Entity classes

## Getting Started
1. Install the .NET 5 SDK.
2. Open the project in Visual Studio.
3. Configure your local database connection if required.
4. Restore NuGet packages and build the projects.
5. Run the application.

## Notes
.NET 5 is out of support. This project was developed using .NET 5.0
and may require dependency updates for production use.
