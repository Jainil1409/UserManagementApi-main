# User Management API

A modern, high-performance Minimal API built with .NET 9 for managing user profiles.

## ✨ Features

- **Standard REST Endpoints**: Full CRUD (Create, Read, Update, Delete) for user management.
- **Swagger UI Integration**: Interactive documentation and testing interface at `/swagger`.
- **Bearer Token Authentication**: Simple but effective security layer.
- **Global Error Handling**: Robust middleware to catch and log exceptions gracefully.
- **Request/Response Logging**: Automatic tracking of incoming requests and outgoing responses.

## 🚀 Getting Started

### Prerequisites
- [.NET 9 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)

### Running the API
1. Clone the repository.
2. Navigate to the project directory.
3. Start the application:
   ```powershell
   dotnet run
   ```
4. Access the API documentation at:
   `http://localhost:5055/swagger`

## 🔒 Authentication

All endpoints (except the root) require a Bearer token.
- **Value**: `valid-token`
- **Header**: `Authorization: Bearer valid-token`

## 🧪 Testing

You can test the API directly through the Swagger UI. Click the **Authorize** button, enter the token, and then use the **Try it out** button on any endpoint.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
