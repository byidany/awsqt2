# .NET 9 ASP.NET Core Web Application

This repository contains a basic ASP.NET Core MVC web application built with .NET 9. It provides a starting point for developing web applications using the latest .NET technologies.

## Project Structure

The project follows the standard ASP.NET Core MVC structure:

- **Controllers/** - Contains controller classes that handle HTTP requests
- **Models/** - Contains model classes for data representation
- **Views/** - Contains Razor views for rendering HTML
  - **Home/** - Views for the HomeController
  - **Shared/** - Shared layout and partial views
- **wwwroot/** - Static files (CSS, JavaScript, images)

## Features

- Basic MVC architecture
- Responsive layout using Bootstrap
- Simple landing page with application description
- Development environment configuration

## Getting Started

### Prerequisites

- [.NET 9 SDK](https://dotnet.microsoft.com/download)
- Visual Studio 2022 or Visual Studio Code

### Running the Application

1. Clone the repository
   ```
   git clone https://github.com/yourusername/WebApp.git
   ```

2. Navigate to the project directory
   ```
   cd WebApp
   ```

3. Restore dependencies
   ```
   dotnet restore
   ```

4. Run the application
   ```
   dotnet run
   ```

5. Open your browser and navigate to `https://localhost:5001` or `http://localhost:5000`

## Client-Side Libraries

The application uses the following client-side libraries:

- **Bootstrap 5.3.2** - For responsive layout and UI components
- **jQuery 3.7.1** - JavaScript library for DOM manipulation
- **jQuery Validation 1.19.5** - For client-side form validation
- **jQuery Validation Unobtrusive 4.0.0** - For ASP.NET Core integration with jQuery Validation

These libraries are managed using LibMan and will be restored during the build process.

## Development Environment

The development environment is configured in `appsettings.Development.json`. You can modify this file to adjust logging levels and other development-specific settings.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.