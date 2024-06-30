# CSharp-CleanCode-API-SingleProject-Template

## Description
This repository serves as a template for a C# API project with a single-project structure. It follows clean code principles to ensure a maintainable, readable, and scalable codebase. This template is suitable for small to medium-sized API projects where a single project structure is sufficient.

## Features
- **Clean Code Practices:** Ensures code readability and maintainability.
- **Single-Project Structure:** Simplifies project setup and management.
- **RESTful API:** Provides a basic setup for building RESTful services.
- **Dependency Injection:** Built-in support for DI using .NET Core.
- **Error Handling:** Includes basic error handling mechanisms.
- **Swagger Integration:** Easily test API endpoints with Swagger.

## Usage

### Adding a New Controller
1. **Create a new controller** in the `Controllers` folder.
2. **Inherit from `ControllerBase`** and use appropriate HTTP methods (e.g., `HttpGet`, `HttpPost`).
3. **Implement the necessary logic or services** to handle requests.

### Adding a New Service
1. **Define an interface** in the `Services` folder.
2. **Implement the interface** in a class within the same folder.
3. **Register the service** in `Startup.cs` for dependency injection.

### Adding a New Repository
1. **Define an interface** in the `Repositories` folder.
2. **Implement the interface** in a class within the same folder.
3. **Register the repository** in `Startup.cs` for dependency injection.

---

### Additional Notes
- **Clean Code and Maintainability:** Follow the naming conventions and coding standards for clean and maintainable code.
- **Documentation:** Regularly update the documentation to reflect any changes in the project structure or functionality.
