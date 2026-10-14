# ASP.NET Core Layered Architecture Project

## About the Project

This project is a web application developed using C# and ASP.NET Core 5.0. It demonstrates a layered architecture by separating the user interface, API, data access operations, and entity models into different projects.

## Technologies

- C#
- ASP.NET Core 5.0
- ASP.NET Core MVC
- ASP.NET Core Web API
- Entity Framework Core
- Microsoft SQL Server
- Swagger / OpenAPI
- Repository Pattern
- Layered Architecture

## Project Structure

- **Core_Proje:** MVC web application and user interface
- **Core_Proje_Api:** Web API project
- **DataAccessLayer:** Data access and Entity Framework Core operations
- **EntityLayer:** Entity classes and data models

## Getting Started

1. Clone this repository.
2. Open the solution in Visual Studio.
3. Configure the database connection string for your local environment.
4. Restore the NuGet packages.
5. Build and run the required projects.

## Notes

This project targets .NET 5.0, which is no longer supported. Updating to a supported .NET version is recommended before using it in production.

## Author

Serhat Öztaş
