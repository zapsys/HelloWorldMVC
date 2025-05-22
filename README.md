# HelloWorldMVC

A simple ASP.NET Core (C#) MVC application.

## Features

- Home and Privacy example pages
- Uses Bootstrap for styling (installed by default)
- Follows the Model-View-Controller (MVC) pattern

## Project Structure

- `Controllers/` - MVC controllers (e.g., HomeController)
- `Views/` - Razor views for each controller/action
- `Models/` - Data models (if needed)
- `wwwroot/` - Static files (CSS, JS, libraries)
- `HelloWorldMVC.csproj` - Project file

## Getting Started

### Prerequisites

- [.NET 9 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)

On Arch Linux, install these packages:

```
sudo pacman -S dotnet-sdk dotnet-runtime aspnet-runtime
```

For other distributions, check your package manager or the official .NET documentation.

### Project Initialization

Create a new MVC app with the name *HelloWorldMVC* and output to the *HelloWorldMVC* folder:

```
dotnet new mvc -n HelloWorldMVC -o HelloWorldMVC
```

### Build and Run

Navigate to the created folder:

```
cd HelloWorldMVC
```

Build and run the project:

```
dotnet build
dotnet run
```

### Execution

The app will be available in your browser at https://localhost:5184 (or the port shown in the terminal).

### License

This project is licensed under the MIT License, allowing use, modification, and redistribution for private or commercial purposes, provided the author is credited.

- [MIT](LICENSE.md)